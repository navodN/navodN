<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Navod N | Portfolio</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css" rel="stylesheet">
  <style>
    :root {
      --bg-color: #0d1117;
      --text-color: #c9d1d9;
      --accent-color: #58a6ff;
    }
    [data-theme="light"] {
      --bg-color: #ffffff;
      --text-color: #0d1117;
      --accent-color: #1f6feb;
    }
    body {
      background-color: var(--bg-color);
      color: var(--text-color);
      transition: background 0.3s ease, color 0.3s ease;
    }
    a {
      color: var(--accent-color);
    }
    .badge-icons img {
      width: 40px;
      margin: 5px;
    }
    .section {
      padding: 3rem 1rem;
    }
    .toggle-btn {
      position: fixed;
      top: 1rem;
      right: 1rem;
      z-index: 1000;
    }
    .social-btn svg {
      width: 20px;
      height: 20px;
      margin-right: 8px;
      vertical-align: middle;
    }
  </style>
</head>
<body data-theme="dark">
  <button class="btn btn-outline-light toggle-btn" onclick="toggleTheme()">
    <i class="bi bi-moon-stars-fill"></i>
  </button>

  <div class="container text-center section">
    <h1 class="fw-bold">👨‍💻 Hey there, I’m Navod!</h1>
    <p class="lead">Tech tinkerer, robot wrangler & web wizard. I love building smart, purposeful tech.</p>
  </div>

  <div class="container section">
    <h3>🚀 Tech Stack</h3>
    <div class="badge-icons">
      <img src="https://skillicons.dev/icons?i=js,php,html,css,java,python,arduino,mysql,bootstrap" alt="Tech Logos">
    </div>
  </div>

  <div class="container section">
    <h3>🔭 Current Projects</h3>
    <ul>
      <li>🕷️ Tarantix Hexapod – Gait system + 3D body fixes</li>
      <li>🌐 Real-time Web Apps – Login dashboards, image uploads</li>
      <li>🗣️ Voice-Controlled Robotics – Arduino + Google Assistant</li>
    </ul>
  </div>

  <div class="container section">
    <h3>📊 GitHub Stats</h3>
    <img src="https://github-readme-stats.vercel.app/api?username=navodN&show_icons=true&theme=tokyonight" class="img-fluid" alt="GitHub Stats">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=navodN&layout=compact&theme=tokyonight" class="img-fluid mt-3" alt="Top Languages">
  </div>

  <div class="container section">
    <h3>🏆 GitHub Trophies</h3>
    <img src="https://github-profile-trophy.vercel.app/?username=navodN&theme=onedark&margin-w=15&row=1" class="img-fluid" alt="Trophies">
  </div>

  <div class="container section">
    <h3>📬 Let’s Connect</h3>
    <p>
      <a href="https://www.linkedin.com/in/navodn/" target="_blank" class="btn btn-outline-primary social-btn">
        <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi bi-linkedin" viewBox="0 0 16 16">
          <path d="M0 1.146C0 .513.526 0 1.175 0h13.65C15.473 0 16 .513 16 1.146v13.708c0 .633-.527 1.146-1.175 1.146H1.175C.527 16 0 15.487 0 14.854V1.146zM4.943 13.447V6.169H2.542v7.278h2.401zm-1.2-8.303c.837 0 1.356-.554 1.356-1.248-.015-.709-.52-1.248-1.342-1.248C3.017 2.648 2.5 3.187 2.5 3.896c0 .694.52 1.248 1.328 1.248h.015zm4.908 8.303V9.359c0-.217.016-.434.08-.588.175-.434.574-.883 1.244-.883.877 0 1.228.666 1.228 1.642v3.917h2.401v-4.195c0-2.243-1.198-3.287-2.794-3.287-1.287 0-1.858.715-2.179 1.215h.016v-1.04H8.652c.03.666 0 7.278 0 7.278h2.401z"/>
        </svg>
        LinkedIn
      </a>
      <a href="https://www.instagram.com/na.vod__" target="_blank" class="btn btn-outline-danger social-btn">
        <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi bi-instagram" viewBox="0 0 16 16">
          <path d="M8 0C5.826 0 5.555.01 4.703.05c-.85.04-1.428.173-1.938.37a3.997 3.997 0 0 0-1.462.95A3.997 3.997 0 0 0 .37 2.765c-.196.51-.33 1.088-.37 1.938C0 5.555 0 5.826 0 8c0 2.174.01 2.445.05 3.297.04.85.173 1.428.37 1.938.178.462.416.87.75 1.204a3.997 3.997 0 0 0 1.204.75c.51.196 1.088.33 1.938.37C5.555 16 5.826 16 8 16c2.174 0 2.445-.01 3.297-.05.85-.04 1.428-.173 1.938-.37a3.997 3.997 0 0 0 1.204-.75 3.997 3.997 0 0 0 .75-1.204c.196-.51.33-1.088.37-1.938C16 10.445 16 10.174 16 8c0-2.174-.01-2.445-.05-3.297-.04-.85-.173-1.428-.37-1.938a3.997 3.997 0 0 0-.75-1.204 3.997 3.997 0 0 0-1.204-.75c-.51-.196-1.088-.33-1.938-.37C10.445 0 10.174 0 8 0zM8 1.44c2.133 0 2.387.01 3.23.047.78.034 1.203.166 1.486.276.37.143.636.314.916.594.28.28.451.546.594.916.11.283.242.707.276 1.486.037.843.047 1.097.047 3.23s-.01 2.387-.047 3.23c-.034.78-.166 1.203-.276 1.486a2.57 2.57 0 0 1-.594.916 2.57 2.57 0 0 1-.916.594c-.283.11-.707.242-1.486.276-.843.037-1.097.047-3.23.047s-2.387-.01-3.23-.047c-.78-.034-1.203-.166-1.486-.276a2.57 2.57 0 0 1-.916-.594 2.57 2.57 0 0 1-.594-.916c-.11-.283-.242-.707-.276-1.486C1.45 10.387 1.44 10.133 1.44 8s.01-2.387.047-3.23c.034-.78.166-1.203.276-1.486.143-.37.314-.636.594-.916.28-.28.546-.451.916-.594.283-.11.707-.242 1.486-.276C5.613 1.45 5.867 1.44 8 1.44zM8 3.84A4.16 4.16 0 1 0 8 12.16 4.16 4.16 0 0 0 8 3.84zm0 6.88A2.72 2.72 0 1 1 8 4.96a2.72 2.72 0 0 1 0 5.76zm4.08-6.96a.96.96 0 1 0 0 1.92.96.96 0 0 0 0-1.92z"/>
        </svg>
        Instagram
      </a>
      <a href="https://web.facebook.com/navod.Ni" target="_blank" class="btn btn-outline-primary social-btn">
        <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi bi-facebook" viewBox="0 0 16 16">
          <path d="M8.94 8H7.5V4h1.5v4zM7.5 10H6V9h1.5v1zM16 8A8 8 0 1 1 0 8a8 8 0 0 1 16 0zM7.5 1C3.91 1 1 3.91 1 7.5S3.91 14 7.5 14 14 11.09 14 7.5 11.09 1 7.5 1z"/>
        </svg>
        Facebook
      </a>
    </p>
  </div>

  <script>
    function toggleTheme() {
      const body = document.body;
      const current = body.getAttribute("data-theme");
      const next = current === "dark" ? "light" : "dark";
      body.setAttribute("data-theme", next);
    }
  </script>
</body>
</html>
