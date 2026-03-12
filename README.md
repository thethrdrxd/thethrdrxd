<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Radcliff Unabia III Portfolio</title>
<style>
  /* Pthalo green background */
  body {
    margin: 0;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background-color: #123524; /* pthalo green */
    color: #ffffff;
    overflow-x: hidden;
    position: relative;
  }

  /* Subtle moving gradient animation */
  body::before {
    content: '';
    position: fixed;
    top: 0;
    left: -50%;
    width: 200%;
    height: 100%;
    background: linear-gradient(120deg, rgba(255,255,255,0.05), rgba(0,0,0,0.05), rgba(255,255,255,0.05));
    animation: moveGradient 15s linear infinite;
    pointer-events: none;
  }

  @keyframes moveGradient {
    0% { transform: translateX(0); }
    50% { transform: translateX(50%); }
    100% { transform: translateX(0); }
  }

  h1, h2, h3, h4 {
    text-align: center;
  }

  p, ul {
    max-width: 800px;
    margin: 0 auto 20px auto;
    line-height: 1.6;
  }

  ul {
    list-style: none;
    padding: 0;
  }

  ul li {
    margin-bottom: 10px;
  }

  a img {
    transition: transform 0.3s;
  }

  a img:hover {
    transform: scale(1.1);
  }

  /* Section cards for better readability */
  section {
    padding: 40px 20px;
    backdrop-filter: blur(10px);
    background-color: rgba(0, 0, 0, 0.2);
    margin: 20px auto;
    border-radius: 15px;
    max-width: 1000px;
  }
</style>
</head>
<body>

<h1>Hello, I'm Radcliff Unabia III 👋</h1>
<p>IT Student • Aspiring UI/UX Designer • Developer</p>
<p>Building ideas through code and design.</p>

<section>
  <h2>🟢 About Me</h2>
  <p>I am an <strong>IT student and aspiring UI/UX designer</strong> passionate about creating <strong>clean, user-friendly, and impactful digital experiences</strong>.</p>
  <p>I enjoy building systems that combine <strong>functionality, design, and real-world usefulness</strong>.</p>
  <h3>Main Interests</h3>
  <ul>
    <li>💻 Software Development</li>
    <li>🎨 UI/UX Design</li>
    <li>📱 Mobile Application Development</li>
    <li>🌐 Web Systems</li>
  </ul>
</section>

<section>
  <h2>🟢 Tech Stack</h2>
  <p><img src="https://skillicons.dev/icons?i=python,js,java,html,css,php,nodejs,dart,flutter" alt="Programming Languages"></p>
  <p><img src="https://skillicons.dev/icons?i=mysql,firebase,supabase" alt="Databases"></p>
  <p>Additional Tools: XAMPP, Firestore, Git, VS Code, Figma, Canva</p>
</section>

<section>
  <h2>🟢 Capstone Project</h2>
  <h3>BantayBaha</h3>
  <p><strong>BantayBaha</strong> is an <strong>IoT-based flood monitoring system</strong> designed to provide <strong>real-time water level monitoring and early warning notifications</strong>.</p>
  <ul>
    <li>📡 Water level monitoring using sensors</li>
    <li>☁ Real-time cloud data storage</li>
    <li>📊 Data visualization and history logs</li>
    <li>📱 SMS notifications for flood alerts</li>
    <li>🗺 Interactive map monitoring</li>
  </ul>
  <p>Technologies Used: ESP32, JSN-SR04T Sensor, Firebase, Leaflet, Arduino IDE, Web Dashboard</p>
</section>

<section>
  <h2>🟢 Connect With Me</h2>
  <p>
    <a href="https://www.facebook.com/"><img src="https://img.shields.io/badge/Facebook-000000?style=for-the-badge&logo=facebook"></a>
    <a href="https://mail.google.com/mail/u/0/#inbox"><img src="https://img.shields.io/badge/Gmail-000000?style=for-the-badge&logo=gmail"></a>
    <a href="https://www.linkedin.com/"><img src="https://img.shields.io/badge/LinkedIn-000000?style=for-the-badge&logo=linkedin"></a>
  </p>
</section>

<p style="text-align:center; margin-top:40px;">I once dreamed of building structures that touch the sky. Now I build systems that live quietly behind the screen.</p>

</body>
</html>
