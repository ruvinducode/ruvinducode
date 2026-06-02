<!-- ╔══════════════════════════════════════════════════════════════╗ -->
<!--        RUVINDU NAVODYA — PREMIUM DEVELOPER PORTFOLIO         -->
<!--         Enterprise-Grade Full Stack Solutions                 -->
<!-- ╚══════════════════════════════════════════════════════════════╝ -->

<!-- Bootstrap & Custom Styling -->
<link href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.0/css/bootstrap.min.css" rel="stylesheet">
<link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">

<style>
  :root {
    --primary-color: #00d4ff;
    --secondary-color: #0066cc;
    --dark-bg: #0D1117;
    --card-bg: #1a1f35;
    --accent: #FF6B35;
  }

  body { background-color: var(--dark-bg); color: #fff; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; }
  
  .hero-section {
    background: linear-gradient(135deg, #0066cc 0%, #0a0a2e 50%, #000000 100%);
    padding: 60px 20px;
    border-bottom: 2px solid var(--primary-color);
    animation: slideDown 0.8s ease-out;
  }

  @keyframes slideDown {
    from { opacity: 0; transform: translateY(-20px); }
    to { opacity: 1; transform: translateY(0); }
  }

  .hero-section h1 {
    font-size: 3.5rem;
    font-weight: 800;
    color: var(--primary-color);
    text-shadow: 0 0 20px rgba(0, 212, 255, 0.5);
    margin-bottom: 15px;
  }

  .hero-section .subtitle {
    font-size: 1.3rem;
    color: #fff;
    letter-spacing: 0.5px;
  }

  .role-badge {
    display: inline-block;
    background: rgba(0, 212, 255, 0.1);
    border: 2px solid var(--primary-color);
    padding: 8px 16px;
    border-radius: 25px;
    margin: 5px;
    font-weight: 600;
    animation: fadeInUp 0.6s ease-out;
  }

  .card-professional {
    background: var(--card-bg);
    border: 2px solid rgba(0, 212, 255, 0.2);
    border-radius: 12px;
    padding: 30px;
    margin: 20px 0;
    transition: all 0.3s ease;
    animation: fadeInUp 0.7s ease-out;
  }

  .card-professional:hover {
    border-color: var(--primary-color);
    box-shadow: 0 0 30px rgba(0, 212, 255, 0.3);
    transform: translateY(-5px);
  }

  @keyframes fadeInUp {
    from { opacity: 0; transform: translateY(20px); }
    to { opacity: 1; transform: translateY(0); }
  }

  .skill-category {
    margin-bottom: 30px;
  }

  .skill-item {
    background: rgba(0, 212, 255, 0.05);
    border-left: 4px solid var(--primary-color);
    padding: 15px 20px;
    margin-bottom: 10px;
    border-radius: 5px;
    transition: all 0.3s ease;
  }

  .skill-item:hover {
    background: rgba(0, 212, 255, 0.15);
    transform: translateX(5px);
  }

  .skill-badge {
    display: inline-block;
    background: rgba(255, 107, 53, 0.2);
    color: var(--accent);
    padding: 6px 12px;
    border-radius: 20px;
    margin-right: 8px;
    margin-top: 8px;
    font-size: 0.85rem;
    border: 1px solid var(--accent);
  }

  .progress-bar-custom {
    background: linear-gradient(90deg, var(--primary-color), var(--secondary-color));
    height: 8px;
    border-radius: 10px;
  }

  .stat-box {
    background: linear-gradient(135deg, rgba(0, 212, 255, 0.1), rgba(0, 102, 204, 0.1));
    border: 2px solid var(--primary-color);
    border-radius: 10px;
    padding: 20px;
    text-align: center;
    transition: all 0.3s ease;
  }

  .stat-box:hover {
    transform: scale(1.05);
    box-shadow: 0 0 20px rgba(0, 212, 255, 0.3);
  }

  .stat-value {
    font-size: 2rem;
    font-weight: 800;
    color: var(--primary-color);
  }

  .stat-label {
    font-size: 0.9rem;
    color: #aaa;
    margin-top: 5px;
  }

  .code-block {
    background: #0a0e27;
    border-left: 4px solid var(--primary-color);
    border-radius: 8px;
    padding: 20px;
    margin: 20px 0;
    overflow-x: auto;
    font-family: 'Courier New', monospace;
    font-size: 0.9rem;
  }

  .section-title {
    font-size: 2.2rem;
    font-weight: 700;
    color: var(--primary-color);
    border-bottom: 3px solid var(--accent);
    padding-bottom: 15px;
    margin-bottom: 30px;
    display: inline-block;
  }

  .service-card {
    background: var(--card-bg);
    border: 2px solid rgba(255, 107, 53, 0.3);
    border-radius: 12px;
    padding: 25px;
    text-align: center;
    transition: all 0.3s ease;
    height: 100%;
  }

  .service-card:hover {
    border-color: var(--accent);
    box-shadow: 0 0 25px rgba(255, 107, 53, 0.3);
    transform: translateY(-8px);
  }

  .service-icon {
    font-size: 2.5rem;
    color: var(--accent);
    margin-bottom: 15px;
  }

  .btn-primary-custom {
    background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
    border: none;
    padding: 12px 30px;
    border-radius: 25px;
    color: #000;
    font-weight: 700;
    transition: all 0.3s ease;
    cursor: pointer;
  }

  .btn-primary-custom:hover {
    transform: scale(1.05);
    box-shadow: 0 0 20px rgba(0, 212, 255, 0.5);
  }

  .experience-timeline {
    position: relative;
    padding: 20px 0;
  }

  .timeline-item {
    padding-left: 40px;
    position: relative;
    margin-bottom: 30px;
  }

  .timeline-item::before {
    content: '';
    position: absolute;
    left: 10px;
    top: 0;
    width: 20px;
    height: 20px;
    background: var(--primary-color);
    border-radius: 50%;
    box-shadow: 0 0 15px rgba(0, 212, 255, 0.5);
  }

  .timeline-item::after {
    content: '';
    position: absolute;
    left: 19px;
    top: 20px;
    width: 2px;
    height: 60px;
    background: linear-gradient(to bottom, var(--primary-color), transparent);
  }

  .timeline-item:last-child::after {
    display: none;
  }

  .tech-stack-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
    gap: 15px;
    margin: 20px 0;
  }

  .tech-tag {
    background: rgba(0, 212, 255, 0.1);
    border: 2px solid var(--primary-color);
    padding: 12px 16px;
    border-radius: 8px;
    text-align: center;
    font-weight: 600;
    transition: all 0.3s ease;
    cursor: pointer;
  }

  .tech-tag:hover {
    background: var(--primary-color);
    color: #000;
    transform: scale(1.05);
  }

  .social-icon-btn {
    width: 50px;
    height: 50px;
    border-radius: 50%;
    background: rgba(0, 212, 255, 0.1);
    border: 2px solid var(--primary-color);
    display: flex;
    align-items: center;
    justify-content: center;
    color: var(--primary-color);
    transition: all 0.3s ease;
    margin: 10px;
  }

  .social-icon-btn:hover {
    background: var(--primary-color);
    color: #000;
    transform: translateY(-5px);
    box-shadow: 0 10px 20px rgba(0, 212, 255, 0.3);
  }

  .divider {
    height: 2px;
    background: linear-gradient(90deg, transparent, var(--primary-color), transparent);
    margin: 40px 0;
  }
</style>

<!-- ┌─────────────────────────────────────────────────────────────┐ -->
<!--                    HERO SECTION                                -->
<!-- └─────────────────────────────────────────────────────────────┘ -->
<div class="hero-section">
  <div class="container">
    <h1>RUVINDU NAVODYA</h1>
    <p class="subtitle">Full Stack Developer | Machine Learning Specialist | IoT Systems Engineer</p>
    <div style="margin-top: 20px;">
      <span class="role-badge">Software Developer</span>
      <span class="role-badge">ML & IoT Specialist</span>
      <span class="role-badge">Tech Entrepreneur</span>
      <span class="role-badge">Founder @ IR Fusions</span>
    </div>
  </div>
</div>

<!-- ┌─────────────────────────────────────────────────────────────┐ -->
<!--                   PROFESSIONAL OVERVIEW                       -->
<!-- └─────────────────────────────────────────────────────────────┘ -->
<div class="container" style="margin-top: 50px;">
  <div class="card-professional">
    <h2 class="section-title">Professional Overview</h2>
    
    <div class="row" style="margin-top: 30px;">
      <div class="col-md-8">
        <div style="line-height: 1.8;">
          <p><strong>Location:</strong> Kaduwela, Colombo, Sri Lanka (Remote-Friendly)</p>
          <p><strong>Current Role:</strong> Software Developer & Founder</p>
          <p><strong>Specialization:</strong> Full-Stack Development | Machine Learning | IoT Systems</p>
          <p><strong>Current Project:</strong> Samat Tour - Smart Tourism Management Platform</p>
          <p><strong>Focus Areas:</strong> Enterprise Applications, Real-World Problem Solving, Scalable Architecture</p>
          
          <div style="margin-top: 25px;">
            <h5 style="color: var(--primary-color); margin-bottom: 15px;">Core Competencies</h5>
            <div class="tech-stack-grid">
              <span class="tech-tag">Python + Flask</span>
              <span class="tech-tag">React.js</span>
              <span class="tech-tag">Node.js</span>
              <span class="tech-tag">PostgreSQL</span>
              <span class="tech-tag">MongoDB</span>
              <span class="tech-tag">TensorFlow</span>
              <span class="tech-tag">IoT Systems</span>
              <span class="tech-tag">Docker</span>
            </div>
          </div>
        </div>
      </div>
      
      <div class="col-md-4">
        <div class="row">
          <div class="col-12">
            <div class="stat-box">
              <div class="stat-value">Enterprise</div>
              <div class="stat-label">Grade Projects</div>
            </div>
          </div>
          <div class="col-12" style="margin-top: 15px;">
            <div class="stat-box">
              <div class="stat-value">Full</div>
              <div class="stat-label">Stack Expert</div>
            </div>
          </div>
          <div class="col-12" style="margin-top: 15px;">
            <div class="stat-box">
              <div class="stat-value">Production</div>
              <div class="stat-label">Ready Code</div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<div class="divider"></div>

<!-- ┌─────────────────────────────────────────────────────────────┐ -->
<!--                 TECHNICAL EXPERTISE & SKILLS                  -->
<!-- └─────────────────────────────────────────────────────────────┘ -->
<div class="container" style="margin-top: 50px;">
  <div class="card-professional">
    <h2 class="section-title">Technical Expertise</h2>
    
    <div class="row" style="margin-top: 30px;">
      <div class="col-md-6">
        <div class="skill-category">
          <h5 style="color: var(--primary-color); margin-bottom: 15px;">Frontend Development</h5>
          <div class="skill-item">
            <strong>React.js</strong>
            <div style="margin-top: 8px;">
              <div style="width: 100%; background: rgba(255,255,255,0.1); border-radius: 10px; height: 6px;">
                <div class="progress-bar-custom" style="width: 75%; height: 100%;"></div>
              </div>
              <small style="color: #aaa;">75% - Enterprise Components & State Management</small>
            </div>
          </div>
          
          <div class="skill-item">
            <strong>Flutter Mobile</strong>
            <div style="margin-top: 8px;">
              <div style="width: 100%; background: rgba(255,255,255,0.1); border-radius: 10px; height: 6px;">
                <div class="progress-bar-custom" style="width: 52%; height: 100%;"></div>
              </div>
              <small style="color: #aaa;">52% - Cross-Platform Development</small>
            </div>
          </div>

          <div class="skill-item">
            <strong>HTML5 / CSS3 / JavaScript</strong>
            <div style="margin-top: 8px;">
              <div style="width: 100%; background: rgba(255,255,255,0.1); border-radius: 10px; height: 6px;">
                <div class="progress-bar-custom" style="width: 88%; height: 100%;"></div>
              </div>
              <small style="color: #aaa;">88% - Advanced Frontend Architecture</small>
            </div>
          </div>
        </div>
      </div>

      <div class="col-md-6">
        <div class="skill-category">
          <h5 style="color: var(--primary-color); margin-bottom: 15px;">Backend Development</h5>
          <div class="skill-item">
            <strong>Python + Flask</strong>
            <div style="margin-top: 8px;">
              <div style="width: 100%; background: rgba(255,255,255,0.1); border-radius: 10px; height: 6px;">
                <div class="progress-bar-custom" style="width: 78%; height: 100%;"></div>
              </div>
              <small style="color: #aaa;">78% - RESTful APIs & Microservices</small>
            </div>
          </div>

          <div class="skill-item">
            <strong>Node.js + Express</strong>
            <div style="margin-top: 8px;">
              <div style="width: 100%; background: rgba(255,255,255,0.1); border-radius: 10px; height: 6px;">
                <div class="progress-bar-custom" style="width: 72%; height: 100%;"></div>
              </div>
              <small style="color: #aaa;">72% - Real-time Applications</small>
            </div>
          </div>

          <div class="skill-item">
            <strong>Database Design</strong>
            <div style="margin-top: 8px;">
              <div style="width: 100%; background: rgba(255,255,255,0.1); border-radius: 10px; height: 6px;">
                <div class="progress-bar-custom" style="width: 82%; height: 100%;"></div>
              </div>
              <small style="color: #aaa;">82% - PostgreSQL, MongoDB, MySQL</small>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div style="margin-top: 30px;">
      <div class="row">
        <div class="col-md-4">
          <div class="skill-category">
            <h5 style="color: var(--accent); margin-bottom: 15px;">Machine Learning</h5>
            <span class="skill-badge">TensorFlow</span>
            <span class="skill-badge">Scikit-learn</span>
            <span class="skill-badge">Data Science</span>
            <span class="skill-badge">NLP</span>
            <span class="skill-badge">Predictive Analytics</span>
          </div>
        </div>
        <div class="col-md-4">
          <div class="skill-category">
            <h5 style="color: var(--accent); margin-bottom: 15px;">IoT Systems</h5>
            <span class="skill-badge">Arduino</span>
            <span class="skill-badge">Real-time Processing</span>
            <span class="skill-badge">Sensor Integration</span>
            <span class="skill-badge">Hardware Control</span>
            <span class="skill-badge">Edge Computing</span>
          </div>
        </div>
        <div class="col-md-4">
          <div class="skill-category">
            <h5 style="color: var(--accent); margin-bottom: 15px;">DevOps & Tools</h5>
            <span class="skill-badge">Docker</span>
            <span class="skill-badge">Git / GitHub</span>
            <span class="skill-badge">Linux</span>
            <span class="skill-badge">CI/CD</span>
            <span class="skill-badge">AWS</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<div class="divider"></div>

<!-- ┌─────────────────────────────────────────────────────────────┐ -->
<!--           PRODUCTION CODE EXAMPLES & ARCHITECTURE            -->
<!-- └─────────────────────────────────────────────────────────────┘ -->
<div class="container" style="margin-top: 50px;">
  <h2 class="section-title">Production Code Examples</h2>
  
  <div class="row" style="margin-top: 30px;">
    <div class="col-md-6">
      <div class="card-professional">
        <h5 style="color: var(--primary-color); margin-bottom: 15px;">React Component Architecture</h5>
        <p style="color: #aaa; font-size: 0.9rem;">Smart Tour Booking Interface</p>
        <div class="code-block">
<pre style="margin: 0; color: #00d4ff;">const TourBookingComponent = ({ tours }) => {
  const [selectedTour, setSelectedTour] = useState(null);
  
  const handleBooking = async () => {
    const response = await fetch('/api/bookings', {
      method: 'POST',
      headers: { 'Content-Type': 'application/json' },
      body: JSON.stringify(selectedTour)
    });
    return response.json();
  };
  
  return (
    &lt;section className="booking-interface"&gt;
      &lt;ToursList tours={tours} /&gt;
      &lt;button onClick={handleBooking}&gt;
        Reserve Now
      &lt;/button&gt;
    &lt;/section&gt;
  );
};</pre>
        </div>
      </div>
    </div>

    <div class="col-md-6">
      <div class="card-professional">
        <h5 style="color: var(--primary-color); margin-bottom: 15px;">Flask API Development</h5>
        <p style="color: #aaa; font-size: 0.9rem;">ML Recommendations Engine</p>
        <div class="code-block">
<pre style="margin: 0; color: #00d4ff;">@app.route('/api/recommendations', 
          methods=['POST'])
def get_recommendations():
  user_profile = request.json
  user_vector = preprocess_user_data(
    user_profile)
  
  recommendations = ml_model.predict(
    user_vector)
  
  return jsonify({
    'status': 'success',
    'recommendations': format_tours(
      recommendations),
    'timestamp': datetime.now()
  })</pre>
        </div>
      </div>
    </div>
  </div>

  <div class="row" style="margin-top: 20px;">
    <div class="col-12">
      <div class="card-professional">
        <h5 style="color: var(--primary-color); margin-bottom: 15px;">IoT Real-Time Tracking System</h5>
        <p style="color: #aaa; font-size: 0.9rem;">Arduino + HTTP Integration</p>
        <div class="code-block">
<pre style="margin: 0; color: #00d4ff;">void updateGuideLocation() {
  if(WiFi.status() == WL_CONNECTED) {
    float lat = gps.location.lat();
    float lng = gps.location.lng();
    
    HTTPClient http;
    String payload = "{\"lat\":" + 
      String(lat) + ",\"lng\":" + String(lng) + "}";
    
    http.begin(API_ENDPOINT);
    http.addHeader("Content-Type", 
      "application/json");
    http.POST(payload);
    http.end();
  }
}</pre>
        </div>
      </div>
    </div>
  </div>
</div>

<div class="divider"></div>

---

<!-- ┌─────────────────────────────────────────────────────────────┐ -->
<!--              GITHUB ANALYTICS DASHBOARD                      -->
<!-- └─────────────────────────────────────────────────────────────┘ -->
<div class="container" style="margin-top: 50px;">
  <h2 class="section-title">GitHub Analytics</h2>
  
  <div class="card-professional" style="margin-top: 30px;">
    <div class="row">
      <div class="col-md-6">
        <div style="text-align: center;">
          <img height="190em" src="https://github-readme-stats.vercel.app/api?username=ruvinducode&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00d4ff&icon_color=FFD700&text_color=FFFFFF&count_private=true&include_all_commits=true&rank_icon=github"/>
        </div>
      </div>
      <div class="col-md-6">
        <div style="text-align: center;">
          <img height="190em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ruvinducode&layout=donut&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00d4ff&text_color=FFFFFF&langs_count=8"/>
        </div>
      </div>
    </div>
  </div>

  <div class="card-professional" style="margin-top: 30px; text-align: center;">
    <h5 style="color: var(--primary-color); margin-bottom: 20px;">Contribution Streak</h5>
    <img width="100%" src="https://github-readme-streak-stats.herokuapp.com/?user=ruvinducode&theme=tokyonight&hide_border=true&background=0D1117&stroke=00d4ff&ring=00d4ff&fire=FF4500&currStreakNum=FFFFFF&sideNums=FFFFFF&currStreakLabel=00d4ff&sideLabels=00d4ff&dates=888888"/>
  </div>

  <div class="card-professional" style="margin-top: 30px; text-align: center;">
    <h5 style="color: var(--primary-color); margin-bottom: 20px;">Achievements</h5>
    <img src="https://github-profile-trophy.vercel.app/?username=ruvinducode&theme=tokyonight&no-frame=true&margin-w=8&margin-h=8&row=2&column=4" width="100%"/>
  </div>
</div>

<div class="divider"></div>

---

---

<!-- ┌─────────────────────────────────────────────────────────────┐ -->
<!--           FEATURED VIDEO & CONTENT SHOWCASE                  -->
<!-- └─────────────────────────────────────────────────────────────┘ -->
<div class="container" style="margin-top: 50px;">
  <h2 class="section-title">Featured Content</h2>
  
  <div class="card-professional" style="margin-top: 30px;">
    <div class="row align-items-center">
      <div class="col-md-6">
        <h4 style="color: var(--primary-color); margin-bottom: 15px;">Samat Tour Project Walkthrough</h4>
        <p style="color: #aaa; line-height: 1.6;">Complete demonstration of the Smart Tourism Management Platform showcasing architecture, features, and real-world implementation.</p>
        
        <div style="margin-top: 20px;">
          <strong style="color: #fff;">What You'll Learn:</strong>
          <ul style="color: #aaa; margin-top: 10px; margin-left: 20px;">
            <li>Complete platform architecture & design patterns</li>
            <li>Full-stack implementation with React + Flask + PostgreSQL</li>
            <li>Real-world booking & reservation system</li>
            <li>AI-powered destination recommendations</li>
            <li>Secure authentication & payment integration</li>
          </ul>
        </div>

        <div style="margin-top: 25px;">
          <a href="https://youtu.be/T9oHJLy2acA?si=j5YNyYkt4Bw9cB23" style="display: inline-block;">
            <button class="btn-primary-custom">Watch Full Demo on YouTube</button>
          </a>
        </div>
      </div>

      <div class="col-md-6">
        <div style="background: linear-gradient(135deg, rgba(0,212,255,0.1), rgba(0,102,204,0.1)); border: 2px solid var(--primary-color); border-radius: 12px; padding: 20px; text-align: center;">
          <a href="https://youtu.be/T9oHJLy2acA?si=j5YNyYkt4Bw9cB23">
            <img src="https://img.youtube.com/vi/T9oHJLy2acA/maxresdefault.jpg" style="border-radius: 8px; width: 100%; max-width: 400px;" alt="Samat Tour Demo">
          </a>
          <div style="margin-top: 15px;">
            <span class="skill-badge">Video Demo</span>
            <span class="skill-badge">45 Minutes</span>
            <span class="skill-badge">Technical Deep Dive</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<div class="divider"></div>
<!-- ┌─────────────────────────────────────────────────────────────┐ -->
<!--           PROFESSIONAL SERVICES & CAPABILITIES               -->
<!-- └─────────────────────────────────────────────────────────────┘ -->
<div class="container" style="margin-top: 50px;">
  <h2 class="section-title">Professional Services</h2>
  
  <div class="row" style="margin-top: 30px;">
    <div class="col-md-4">
      <div class="service-card">
        <div class="service-icon"><i class="fas fa-code"></i></div>
        <h5>Full-Stack Development</h5>
        <p style="color: #aaa;">Enterprise applications with React, Flask, PostgreSQL</p>
        <span class="skill-badge">React</span>
        <span class="skill-badge">Python</span>
        <span class="skill-badge">PostgreSQL</span>
      </div>
    </div>

    <div class="col-md-4">
      <div class="service-card">
        <div class="service-icon"><i class="fas fa-brain"></i></div>
        <h5>AI & Machine Learning</h5>
        <p style="color: #aaa;">TensorFlow, predictive analytics, recommendation engines</p>
        <span class="skill-badge">TensorFlow</span>
        <span class="skill-badge">ML Models</span>
        <span class="skill-badge">Analytics</span>
      </div>
    </div>

    <div class="col-md-4">
      <div class="service-card">
        <div class="service-icon"><i class="fas fa-microchip"></i></div>
        <h5>IoT Solutions</h5>
        <p style="color: #aaa;">Arduino, real-time systems, connected devices</p>
        <span class="skill-badge">Arduino</span>
        <span class="skill-badge">Real-time</span>
        <span class="skill-badge">Hardware</span>
      </div>
    </div>

    <div class="col-md-4" style="margin-top: 20px;">
      <div class="service-card">
        <div class="service-icon"><i class="fas fa-mobile-alt"></i></div>
        <h5>Mobile Development</h5>
        <p style="color: #aaa;">Cross-platform applications with Flutter</p>
        <span class="skill-badge">Flutter</span>
        <span class="skill-badge">Cross-platform</span>
        <span class="skill-badge">Mobile UI</span>
      </div>
    </div>

    <div class="col-md-4" style="margin-top: 20px;">
      <div class="service-card">
        <div class="service-icon"><i class="fas fa-layer-group"></i></div>
        <h5>System Architecture</h5>
        <p style="color: #aaa;">Microservices, Docker, scalable infrastructure</p>
        <span class="skill-badge">Docker</span>
        <span class="skill-badge">Microservices</span>
        <span class="skill-badge">DevOps</span>
      </div>
    </div>

    <div class="col-md-4" style="margin-top: 20px;">
      <div class="service-card">
        <div class="service-icon"><i class="fas fa-chart-bar"></i></div>
        <h5>Data Analytics</h5>
        <p style="color: #aaa;">Python dashboards, business intelligence</p>
        <span class="skill-badge">Python</span>
        <span class="skill-badge">Analytics</span>
        <span class="skill-badge">BI</span>
      </div>
    </div>
  </div>
</div>

<div class="divider"></div>

> 🎓 *Your digital classroom for IT and Data Science — breaking down complex concepts into simple, friendly sessions!*

<div align="center">

[![KuppiLab Badge](https://img.shields.io/badge/📚_Kuppi_Lab-IT_%26_Data_Science_Education-FF6B35?style=for-the-badge&logo=telegram&logoColor=white&labelColor=7B3010)](https://t.me/Kuppi_Lab)

**Topics Covered:**

![Database](https://img.shields.io/badge/🗄️_Database_Systems-0D1117?style=flat-square&color=FF6B35)
![Programming](https://img.shields.io/badge/💻_Programming_%26_Frameworks-0D1117?style=flat-square&color=FF6B35)
![Networks](https://img.shields.io/badge/🌐_Network_Design-0D1117?style=flat-square&color=FF6B35)
![IT PM](https://img.shields.io/badge/📋_IT_Project_Mgmt-0D1117?style=flat-square&color=FF6B35)
![ML](https://img.shields.io/badge/🤖_Machine_Learning-0D1117?style=flat-square&color=FF6B35)

<br/>

[![Join KuppiLab](https://img.shields.io/badge/🔔_Join_Kuppi_Lab_Community-FF6B35?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/Kuppi_Lab)
[![Website](https://img.shields.io/badge/📖_Official_Website-00D4FF?style=for-the-badge&logo=firefox&logoColor=white)](https://kuppilab.is-best.net/)

> 💡 *Turning study sessions into productive "Kuppi" time! 🎓*

</div>

---

<!-- ┌─────────────────────────────────────────────────────────────┐ -->
<!--                      FLAGSHIP PROJECTS                        -->
<!-- └─────────────────────────────────────────────────────────────┘ -->
<div class="container" style="margin-top: 50px;">
  <h2 class="section-title">Flagship Projects</h2>
  
  <div class="row" style="margin-top: 30px;">
    <div class="col-12">
      <div class="card-professional">
        <div class="row align-items-center">
          <div class="col-md-8">
            <h4 style="color: var(--primary-color);">Samat Tour - Smart Tourism Platform</h4>
            <p style="color: #aaa; margin: 10px 0;">Digital ecosystem connecting tourists, tour operators, guides, hotels, and transportation</p>
            
            <div style="margin: 15px 0;">
              <strong>Key Features:</strong>
              <div style="margin-top: 10px;">
                <span class="skill-badge">Tour Package Management</span>
                <span class="skill-badge">Online Booking System</span>
                <span class="skill-badge">Itinerary Planning</span>
                <span class="skill-badge">AI Recommendations</span>
                <span class="skill-badge">Payment Gateway</span>
                <span class="skill-badge">Real-time Tracking</span>
              </div>
            </div>

            <div style="margin-top: 15px;">
              <strong>Tech Stack:</strong>
              <div style="margin-top: 10px;">
                <span class="skill-badge">React.js</span>
                <span class="skill-badge">Python Flask</span>
                <span class="skill-badge">PostgreSQL</span>
                <span class="skill-badge">TensorFlow</span>
                <span class="skill-badge">RESTful APIs</span>
              </div>
            </div>
          </div>
          <div class="col-md-4" style="text-align: center;">
            <div style="background: rgba(0,212,255,0.1); border: 2px solid var(--primary-color); border-radius: 10px; padding: 20px;">
              <div style="font-size: 3rem; color: var(--primary-color); margin-bottom: 10px;">✓</div>
              <p style="font-weight: 700; color: var(--primary-color);">Live</p>
              <p style="color: #aaa; font-size: 0.9rem;">Production Ready</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div class="row" style="margin-top: 20px;">
    <div class="col-md-6">
      <div class="card-professional">
        <h5 style="color: var(--primary-color);">Tour Package Management</h5>
        <p style="color: #aaa;">Seamless booking & itinerary planning</p>
        <div style="margin-top: 15px;">
          <div style="background: rgba(255,107,53,0.1); padding: 12px; border-radius: 8px; border-left: 4px solid var(--accent);">
            <p style="margin: 0;"><strong>Status:</strong> <span style="color: var(--primary-color);">Core Complete</span></p>
          </div>
        </div>
        <div style="margin-top: 12px;">
          <span class="skill-badge">MERN Stack</span>
          <span class="skill-badge">Database</span>
          <span class="skill-badge">API</span>
        </div>
      </div>
    </div>

    <div class="col-md-6">
      <div class="card-professional">
        <h5 style="color: var(--primary-color);">Destination Discovery Engine</h5>
        <p style="color: #aaa;">AI-powered recommendations & analytics</p>
        <div style="margin-top: 15px;">
          <div style="background: rgba(255,107,53,0.1); padding: 12px; border-radius: 8px; border-left: 4px solid var(--accent);">
            <p style="margin: 0;"><strong>Status:</strong> <span style="color: var(--primary-color);">In Development</span></p>
          </div>
        </div>
        <div style="margin-top: 12px;">
          <span class="skill-badge">ML Model</span>
          <span class="skill-badge">React</span>
          <span class="skill-badge">Analytics</span>
        </div>
      </div>
    </div>
  </div>
</div>

<div class="divider"></div>

<!-- ┌─────────────────────────────────────────────────────────────┐ -->
<!--                  CURRENTLY LEARNING                          -->
<!-- └─────────────────────────────────────────────────────────────┘ -->
<!-- ┌─────────────────────────────────────────────────────────────┐ -->
<!--                  LEARNING ROADMAP                            -->
<!-- └─────────────────────────────────────────────────────────────┘ -->
<div class="container" style="margin-top: 50px;">
  <h2 class="section-title">Currently Exploring</h2>
  
  <div class="row" style="margin-top: 30px;">
    <div class="col-md-3">
      <div class="card-professional">
        <h6 style="color: var(--primary-color);">Advanced AI/ML</h6>
        <p style="color: #aaa; font-size: 0.9rem;">Deep Learning, NLP, Computer Vision</p>
        <div style="margin-top: 10px;">
          <span class="skill-badge">PyTorch</span>
          <span class="skill-badge">NLP</span>
        </div>
      </div>
    </div>

    <div class="col-md-3">
      <div class="card-professional">
        <h6 style="color: var(--primary-color);">Enterprise Architecture</h6>
        <p style="color: #aaa; font-size: 0.9rem;">Microservices, Kubernetes, Cloud Native</p>
        <div style="margin-top: 10px;">
          <span class="skill-badge">K8s</span>
          <span class="skill-badge">AWS</span>
        </div>
      </div>
    </div>

    <div class="col-md-3">
      <div class="card-professional">
        <h6 style="color: var(--primary-color);">DevOps & Cloud</h6>
        <p style="color: #aaa; font-size: 0.9rem;">CI/CD, Infrastructure as Code</p>
        <div style="margin-top: 10px;">
          <span class="skill-badge">Docker</span>
          <span class="skill-badge">Terraform</span>
        </div>
      </div>
    </div>

    <div class="col-md-3">
      <div class="card-professional">
        <h6 style="color: var(--primary-color);">Mobile Optimization</h6>
        <p style="color: #aaa; font-size: 0.9rem;">Cross-platform Performance</p>
        <div style="margin-top: 10px;">
          <span class="skill-badge">React Native</span>
          <span class="skill-badge">Flutter+</span>
        </div>
      </div>
    </div>
  </div>
</div>

<div class="divider"></div>

<!-- ┌─────────────────────────────────────────────────────────────┐ -->
<!--         KUPPI LAB — EDUCATIONAL INITIATIVE                   -->
<!-- └─────────────────────────────────────────────────────────────┘ -->
<div class="container" style="margin-top: 50px;">
  <h2 class="section-title">Kuppi Lab — Educational Initiative</h2>
  <p style="color: #aaa; text-align: center; margin-top: 15px; font-size: 1.1rem;">
    <strong>Your digital classroom for IT & Data Science</strong><br>
    Breaking down complex concepts into simple, friendly learning sessions
  </p>
  
  <div class="card-professional" style="margin-top: 30px; text-align: center;">
    <div style="margin-bottom: 20px;">
      <i class="fas fa-graduation-cap" style="font-size: 2.5rem; color: var(--accent);"></i>
    </div>
    
    <h4 style="color: var(--primary-color); margin-bottom: 20px;">Topics Covered</h4>
    
    <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(180px, 1fr)); gap: 15px; margin-bottom: 25px;">
      <div style="background: rgba(255,107,53,0.1); padding: 15px; border-radius: 8px; border-left: 4px solid var(--accent);">
        <strong style="color: var(--accent);">Database Systems</strong>
        <p style="color: #aaa; font-size: 0.9rem;">SQL, NoSQL, Query Optimization</p>
      </div>
      <div style="background: rgba(255,107,53,0.1); padding: 15px; border-radius: 8px; border-left: 4px solid var(--accent);">
        <strong style="color: var(--accent);">Programming</strong>
        <p style="color: #aaa; font-size: 0.9rem;">Web Dev, Frameworks & APIs</p>
      </div>
      <div style="background: rgba(255,107,53,0.1); padding: 15px; border-radius: 8px; border-left: 4px solid var(--accent);">
        <strong style="color: var(--accent);">Networks</strong>
        <p style="color: #aaa; font-size: 0.9rem;">Design & Architecture</p>
      </div>
      <div style="background: rgba(255,107,53,0.1); padding: 15px; border-radius: 8px; border-left: 4px solid var(--accent);">
        <strong style="color: var(--accent);">IT Project Mgmt</strong>
        <p style="color: #aaa; font-size: 0.9rem;">Agile, Scrum, Leadership</p>
      </div>
      <div style="background: rgba(255,107,53,0.1); padding: 15px; border-radius: 8px; border-left: 4px solid var(--accent);">
        <strong style="color: var(--accent);">Machine Learning</strong>
        <p style="color: #aaa; font-size: 0.9rem;">AI, Algorithms, Analytics</p>
      </div>
    </div>

    <div style="display: flex; justify-content: center; gap: 15px; flex-wrap: wrap; margin-top: 25px;">
      <a href="https://t.me/Kuppi_Lab" style="text-decoration: none;">
        <button class="btn-primary-custom">Join Telegram Community</button>
      </a>
      <a href="https://kuppilab.is-best.net/" style="text-decoration: none;">
        <button class="btn-primary-custom">Visit Website</button>
      </a>
    </div>
  </div>
</div>

<div class="divider"></div>

```
╔══════════════════════════════════════════════════════════════════╗
║  "Technology should solve real problems,                         ║
║   not create more noise in the world."                           ║
║                                       — Ruvindu Navodya 🇱🇰      ║
╚══════════════════════════════════════════════════════════════════╝
```

</div>

---

<!-- ┌─────────────────────────────────────────────────────────────┐ -->
<!--               SNAKE + WORKFLOW (ALL IN ONE)                  -->
<!--                                                               -->
<!--  ⚠️  HOW THE SNAKE WORKS (built into this README):           -->
<!--                                                               -->
<!--  1. Create the folder: .github/workflows/                     -->
<!--  2. Create file:       snake.yml  (code block below)          -->
<!--  3. Go to Actions tab → Run "Generate Snake Animation"        -->
<!--  4. Snake SVG auto-generates to the `output` branch           -->
<!--  5. The <picture> tag below auto-displays it!                 -->
<!--                                                               -->
<!--  SNAKE WORKFLOW CODE — save as .github/workflows/snake.yml:   -->
<!--                                                               -->
<!--  name: Generate Snake Animation                               -->
<!--  on:                                                          -->
<!--    schedule:                                                   -->
<!--      - cron: "0 */12 * * *"                                   -->
<!--    workflow_dispatch:                                          -->
<!--    push:                                                       -->
<!--      branches: [main]                                         -->
<!--  jobs:                                                        -->
<!--    generate:                                                   -->
<!--      permissions:                                             -->
<!--        contents: write                                        -->
<!--      runs-on: ubuntu-latest                                   -->
<!--      steps:                                                    -->
<!--        - name: Generate Snake SVGs                            -->
<!--          uses: Platane/snk/svg-only@v3                        -->
<!--          with:                                                 -->
<!--            github_user_name: ${{ github.repository_owner }}   -->
<!--            outputs: |                                          -->
<!--              dist/github-contribution-grid-snake.svg           -->
<!--              dist/github-contribution-grid-snake-dark.svg     -->
<!--                ?palette=github-dark                            -->
<!--        - name: Push to output branch                          -->
<!--          uses: crazy-max/ghaction-github-pages@v3.1.0         -->
<!--          with:                                                 -->
<!--            target_branch: output                              -->
<!--            build_dir: dist                                    -->
<!--          env:                                                  -->
<!--            GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}          -->
<!-- └─────────────────────────────────────────────────────────────┘ -->

## 🐍 Contribution Snake

<div align="center">
  <picture>
    <source
      media="(prefers-color-scheme: dark)"
      srcset="https://raw.githubusercontent.com/ruvinducode/ruvinducode/output/github-contribution-grid-snake-dark.svg"/>
    <source
      media="(prefers-color-scheme: light)"
      srcset="https://raw.githubusercontent.com/ruvinducode/ruvinducode/output/github-contribution-grid-snake.svg"/>
    <img
      alt="🐍 contribution snake animation"
      src="https://raw.githubusercontent.com/ruvinducode/ruvinducode/output/github-contribution-grid-snake-dark.svg"
      width="95%"/>
  </picture>
</div>

> ⚙️ *Snake auto-updates every 12 hours via GitHub Actions. See comments in source for setup.*

<!-- ┌─────────────────────────────────────────────────────────────┐ -->
<!--                  CONTACT & COLLABORATION                      -->
<!-- └─────────────────────────────────────────────────────────────┘ -->
<div class="container" style="margin-top: 50px; margin-bottom: 40px;">
  <h2 class="section-title">Get in Touch</h2>
  
  <div class="row" style="margin-top: 30px;">
    <div class="col-md-6">
      <div class="card-professional">
        <h5 style="color: var(--primary-color); margin-bottom: 15px;">Availability</h5>
        <div style="margin-top: 15px;">
          <div style="margin-bottom: 15px;">
            <strong>Current Status:</strong> <span style="color: var(--primary-color);">Open for Partnerships</span>
          </div>
          <div style="margin-bottom: 15px;">
            <strong>Location:</strong> <span style="color: #aaa;">Kaduwela, Colombo, Sri Lanka (Remote)</span>
          </div>
          <div style="margin-bottom: 15px;">
            <strong>Response Time:</strong> <span style="color: #aaa;">Within 24 Hours</span>
          </div>
          <div>
            <strong>Focus:</strong> <span style="color: #aaa;">Enterprise Solutions, Startups, Innovation Projects</span>
          </div>
        </div>
      </div>
    </div>

    <div class="col-md-6">
      <div class="card-professional">
        <h5 style="color: var(--primary-color); margin-bottom: 15px;">Connect</h5>
        <div style="display: flex; justify-content: center; flex-wrap: wrap; margin-top: 20px;">
          <a href="https://linkedin.com/in/ruvindu-navodya" style="text-decoration: none;">
            <div class="social-icon-btn">
              <i class="fab fa-linkedin"></i>
            </div>
          </a>
          <a href="https://t.me/Kuppi_Lab" style="text-decoration: none;">
            <div class="social-icon-btn">
              <i class="fab fa-telegram"></i>
            </div>
          </a>
          <a href="https://kuppilab.is-best.net/" style="text-decoration: none;">
            <div class="social-icon-btn">
              <i class="fas fa-globe"></i>
            </div>
          </a>
          <a href="mailto:ruvindu@irfusions.com" style="text-decoration: none;">
            <div class="social-icon-btn">
              <i class="fas fa-envelope"></i>
            </div>
          </a>
          <a href="https://github.com/ruvinducode" style="text-decoration: none;">
            <div class="social-icon-btn">
              <i class="fab fa-github"></i>
            </div>
          </a>
        </div>
      </div>
    </div>
  </div>

  <!-- Quick Stats -->
  <div class="row" style="margin-top: 30px;">
    <div class="col-md-3">
      <div class="stat-box">
        <div class="stat-value">100%</div>
        <div class="stat-label">Code Quality</div>
      </div>
    </div>
    <div class="col-md-3">
      <div class="stat-box">
        <div class="stat-value">8+</div>
        <div class="stat-label">Years Experience</div>
      </div>
    </div>
    <div class="col-md-3">
      <div class="stat-box">
        <div class="stat-value">50+</div>
        <div class="stat-label">Projects</div>
      </div>
    </div>
    <div class="col-md-3">
      <div class="stat-box">
        <div class="stat-value">∞</div>
        <div class="stat-label">Dedication</div>
      </div>
    </div>
  </div>
</div>

<div style="background: linear-gradient(135deg, #0066cc 0%, #0a0a2e 100%); padding: 40px 0; margin-top: 50px; text-align: center; border-top: 2px solid var(--primary-color);">
  <div class="container">
    <h3 style="margin-bottom: 15px;">Crafting Enterprise Solutions</h3>
    <p style="color: #aaa; margin-bottom: 25px;">Transforming complex challenges into scalable, elegant solutions through innovation and technical excellence.</p>
    
    <p style="color: #aaa; font-size: 0.9rem;">
      <strong style="color: var(--primary-color);">Ruvindu Navodya</strong> | Full Stack Developer | Machine Learning Specialist | IoT Engineer<br>
      <strong style="color: var(--accent);">IR Fusions</strong> - Founder & Innovation Lead<br>
      <strong style="color: var(--primary-color);">Colombo, Sri Lanka</strong> (Remote-Friendly)
    </p>
  </div>
</div>

<!-- ═══════════════════════════════════════════════ -->
<!--           🥚 EASTER EGG FOR CURIOUS DEVS 🥚    -->
<!--  ██╗███╗░░░███╗███████╗░██████╗██╗░░██╗        -->
<!--  ██║████╗░████║██╔════╝██╔════╝██║░██╔╝        -->
<!--  ██║██╔████╔██║█████╗░░╚█████╗░███████║        -->
<!--  ██║██║╚██╔╝██║██╔══╝░░░╚═══██╗██╔═██╗░        -->
<!--  ██║██║░╚═╝░██║███████╗██████╔╝██║░╚██╗        -->
<!--  ╚═╝╚═╝░░░░╚═╝╚══════╝╚═════╝░╚═╝░░╚═╝        -->
<!--  🎉 You found the easter egg! Star ⭐ the repo! -->
<!-- ═══════════════════════════════════════════════ -->
