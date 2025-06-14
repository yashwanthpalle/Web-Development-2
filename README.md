# Web-Development-2
Prepare calculator using web Development 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f2f2f2;
      color: #333;
    }
    header {
      background-color: #004aad;
      color: white;
      padding: 30px;
      text-align: center;
    }
    section {
      padding: 30px;
      background: white;
      margin: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    img.profile {
      width: 150px;
      border-radius: 50%;
      display: block;
      margin: 0 auto 20px;
    }
    .projects img {
      max-width: 100%;
      height: auto;
    }
    footer {
      background: #004aad;
      color: white;
      text-align: center;
      padding: 15px;
    }
    a {
      color: #004aad;
    }
  </style>
</head>
<body>
  <header>
    <h1>Palle Yashwanth</h1>
    <p>Web Developer | Designer | Learner</p>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <img src="profile.jpg" alt="Your Photo" class="profile" />
    <p>Hello! I'm Palle Yashwanth, a passionate web developer learning HTML and CSS. I love building responsive, creative websites and continuously improving my skills.</p>
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <ul>
      <li>HTML5</li>
      <li>CSS3</li>
      <li>JavaScript (Basic)</li>
      <li>Responsive Design</li>
    </ul>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="projects">
      <h3>Portfolio Website</h3>
      <p>Created a personal portfolio using HTML and CSS.</p>
      <img src="project1.jpg" alt="Project Screenshot" />
    </div>
  </section>

  <section id="resume">
    <h2>Resume</h2>
    <p><a href="resume.pdf" download>Download My Resume (PDF)</a></p>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Email: palleyashwanth33@gmail.com</p>
    <p>Phone: +91 7901503002</p>
  </section>

  <footer>
    <p>&copy; 2025 Palle Yashwanth. All rights reserved.</p>
    <p><a href="#">Additional Links</a></p>
  </footer>
</body>
</html>
