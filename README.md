<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio | Developer</title>
  <link rel="stylesheet" href="style.css">
</head>

<body>

  <header>
    <nav class="navbar">
      <a href="#" class="logo">My<span>Portfolio</span></a>

      <ul class="nav-links">
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>

      <button id="menuBtn">☰</button>
    </nav>
  </header>

  <main>

    <!-- Hero -->
    <section id="home" class="hero">
      <div class="hero-content">
        <p class="small-title">WELCOME TO MY PORTFOLIO</p>

        <h1>Hi, I'm <span>Your Name</span></h1>

        <h2>Web Developer & AI Enthusiast</h2>

        <p>
          I create modern, responsive and user-friendly websites
          using the latest web technologies.
        </p>

        <div class="hero-buttons">
          <a href="#projects" class="btn">View Projects</a>
          <a href="#contact" class="btn secondary">Contact Me</a>
        </div>
      </div>

      <div class="hero-card">
        <div class="code-card">
          <span>&lt;/&gt;</span>
          <h3>Code. Create. Innovate.</h3>
          <p>Building ideas into digital experiences.</p>
        </div>
      </div>
    </section>


    <!-- About -->
    <section id="about" class="section">
      <div class="section-title">
        <p>GET TO KNOW ME</p>
        <h2>About Me</h2>
      </div>

      <div class="about-content">
        <div class="about-box">
          <h3>Who I Am</h3>
          <p>
            I'm a passionate developer interested in web development,
            artificial intelligence and modern digital technologies.
            I enjoy learning new technologies and turning ideas into
            useful projects.
          </p>
        </div>

        <div class="about-box">
          <h3>My Goal</h3>
          <p>
            My goal is to build clean, fast and professional digital
            experiences while continuously improving my development
            and problem-solving skills.
          </p>
        </div>
      </div>
    </section>


    <!-- Skills -->
    <section id="skills" class="section">
      <div class="section-title">
        <p>WHAT I KNOW</p>
        <h2>My Skills</h2>
      </div>

      <div class="skills-grid">
        <div class="skill">
          <h3>HTML</h3>
          <div class="progress"><span style="width: 95%"></span></div>
        </div>

        <div class="skill">
          <h3>CSS</h3>
          <div class="progress"><span style="width: 90%"></span></div>
        </div>

        <div class="skill">
          <h3>JavaScript</h3>
          <div class="progress"><span style="width: 80%"></span></div>
        </div>

        <div class="skill">
          <h3>AI Tools</h3>
          <div class="progress"><span style="width: 85%"></span></div>
        </div>
      </div>
    </section>


    <!-- Projects -->
    <section id="projects" class="section">
      <div class="section-title">
        <p>MY RECENT WORK</p>
        <h2>Projects</h2>
      </div>

      <div class="projects-grid">

        <div class="project-card">
          <div class="project-icon">🤖</div>
          <h3>AI Chatbot</h3>
          <p>
            A modern chatbot interface designed for AI-powered
            conversations.
          </p>
          <a href="#" class="project-link">View Project →</a>
        </div>

        <div class="project-card">
          <div class="project-icon">🌐</div>
          <h3>Portfolio Website</h3>
          <p>
            A responsive personal portfolio website built with
            HTML, CSS and JavaScript.
          </p>
          <a href="#" class="project-link">View Project →</a>
        </div>

        <div class="project-card">
          <div class="project-icon">📊</div>
          <h3>Dashboard</h3>
          <p>
            A clean and responsive dashboard interface for displaying
            important information.
          </p>
          <a href="#" class="project-link">View Project →</a>
        </div>

      </div>
    </section>


    <!-- Contact -->
    <section id="contact" class="section contact-section">
      <div class="section-title">
        <p>LET'S CONNECT</p>
        <h2>Contact Me</h2>
      </div>

      <form id="contactForm">

        <input
          type="text"
          id="name"
          placeholder="Your Name"
          required
        >

        <input
          type="email"
          id="email"
          placeholder="Your Email"
          required
        >

        <textarea
          id="message"
          rows="6"
          placeholder="Your Message"
          required
        ></textarea>

        <button type="submit" class="btn">
          Send Message
        </button>

        <p id="formMessage"></p>

      </form>
    </section>

  </main>


  <footer>
    <p>© 2026 Your Name. All Rights Reserved.</p>
  </footer>


  <script src="script.js"></script>

</body>
</html>
