# TASK-1
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>My Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      line-height: 1.6;
      background-color: #f5f5f5;
      color: #333;
    }

    header {
      background-color: #333;
      color: white;
      padding: 20px 0;
      text-align: center;
    }

    header h1 {
      margin: 0;
    }

    nav {
      text-align: center;
      padding: 10px;
      background: #444;
    }

    nav a {
      margin: 0 15px;
      color: white;
      text-decoration: none;
    }

    section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
      background-color: white;
      margin-bottom: 20px;
      border-radius: 8px;
    }

    .about img {
      width: 150px;
      border-radius: 50%;
      float: left;
      margin-right: 20px;
    }

    .skills ul, .projects ul {
      list-style: none;
      padding: 0;
    }

    .skills li, .projects li {
      background: #e7e7e7;
      margin: 5px 0;
      padding: 10px;
      border-radius: 4px;
    }

    .projects img {
      width: 100%;
      max-width: 400px;
      margin-top: 10px;
      border-radius: 5px;
    }

    .resume a {
      display: inline-block;
      padding: 10px 20px;
      background: #333;
      color: white;
      text-decoration: none;
      border-radius: 5px;
      margin-top: 10px;
    }

    .contact p {
      margin: 10px 0;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #333;
      color: white;
    }

    @media (max-width: 600px) {
      .about img {
        float: none;
        display: block;
        margin: 0 auto 20px;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Your Name</h1>
    <p>Web Developer | Designer | Tech Enthusiast</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#resume">Resume</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about" class="about">
    <h2>About Me</h2>
    <img src="your-image.jpg" alt="Your Photo">
    <p>Hello! I am a passionate web developer with experience in HTML, CSS, and JavaScript. I enjoy creating user-friendly and responsive websites. I am always eager to learn and take on new challenges in web development.</p>
  </section>

  <section id="skills" class="skills">
    <h2>My Skills</h2>
    <ul>
      <li>HTML5 & CSS3</li>
      <li>JavaScript & DOM</li>
      <li>Responsive Web Design</li>
      <li>Git & GitHub</li>
      <li>Basic C Programming</li>
    </ul>
  </section>

  <section id="projects" class="projects">
    <h2>My Projects</h2>
    <ul>
      <li>
        <strong>Portfolio Website</strong><br>
        A responsive personal website built with HTML and CSS.
        <br>
        <img src="portfolio-project.jpg" alt="Project Image">
      </li>
      <li>
        <strong>To-Do List App</strong><br>
        A basic to-do list application made using JavaScript.
        <br>
        <img src="todo-project.jpg" alt="Project Image">
      </li>
    </ul>
  </section>

  <section id="resume" class="resume">
    <h2>My Resume</h2>
    <p>Click below to download my resume:</p>
    <a href="resume.pdf" download>Download Resume (PDF)</a>
  </section>

  <section id="contact" class="contact">
    <h2>Contact Me</h2>
    <p>Email: manoharpasupuleti24@gmail.com</p>
    <p>Phone: +91-9392140544</p>
  </section>

  <footer>
    <p>&copy; 2025 Your Name. P.Manohar.</p>
  </footer>

</body>
</html>
