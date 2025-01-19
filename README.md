<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>GitHub Portfolio</title>
  <link rel="stylesheet" href="style.css">
  <script src="https://kit.fontawesome.com/3dd4d3e5d9.js" crossorigin="anonymous"></script>
</head>
<body>
  <header>
    <div class="profile">
      <svg class="avatar" viewBox="0 0 100 100">
        <circle cx="50" cy="50" r="45" fill="#c3c3c3"/>
        <circle cx="50" cy="40" r="20" fill="#666"/>
        <path d="M50 65 Q50 95 80 85 A45 45 0 0 1 20 85 Q50 95 50 65" fill="#666"/>
      </svg>
      <h1>Developer Name</h1>
      <p>Full Stack Developer</p>
    </div>
    <nav>
      <a href="#projects">Projects</a>
      <a href="#skills">Skills</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main>
    <section id="projects">
      <h2>Featured Projects</h2>
      <div class="project-grid">
        <article class="project-card">
          <div class="project-header">
            <i class="fas fa-code-branch"></i>
            <h3>Project One</h3>
          </div>
          <p>A fantastic project that does amazing things</p>
          <div class="project-footer">
            <span class="language"><span class="dot js"></span>JavaScript</span>
            <a href="https://github.com" class="view-repo">View Repo</a>
          </div>
        </article>

        <article class="project-card">
          <div class="project-header">
            <i class="fas fa-code-branch"></i>
            <h3>Project Two</h3>
          </div>
          <p>Another incredible project showcase</p>
          <div class="project-footer">
            <div class="footer-links">
              <span class="language"><span class="dot python"></span>Python</span>
              <a href="https://github.com" class="view-repo">View Repo</a>
              <a href="https://fortnite.com" class="view-repo">Visit Fortnite</a>
            </div>
          </div>
        </article>
      </div>
    </section>

    <section id="skills">
      <h2>Skills</h2>
      <div class="skills-container">
        <div class="skill">
          <i class="fab fa-js"></i>
          <span>JavaScript</span>
        </div>
        <div class="skill">
          <i class="fab fa-react"></i>
          <span>React</span>
        </div>
        <div class="skill">
          <i class="fab fa-node"></i>
          <span>Node.js</span>
        </div>
        <div class="skill">
          <i class="fab fa-python"></i>
          <span>Python</span>
        </div>
      </div>
    </section>

    <section id="contact">
      <h2>Get in Touch</h2>
      <div class="social-links">
        <a href="https://github.com" class="social-link">
          <i class="fab fa-github"></i>
          GitHub
        </a>
        <a href="https://linkedin.com" class="social-link">
          <i class="fab fa-linkedin"></i>
          LinkedIn
        </a>
        <a href="mailto:email@example.com" class="social-link">
          <i class="fas fa-envelope"></i>
          Email
        </a>
      </div>
    </section>
  </main>

  <footer>
    <p> 2024 Developer Name. All rights reserved.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html
