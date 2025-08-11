<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Ayatullahi | Web Developer Portfolio</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Ayatullahi</h1>
    <p>Web Developer & Problem Solver</p>
    <nav>
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#experience">Experience</a>
      <a href="#projects">Projects</a>
      <a href="#testimonials">Testimonials</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>
      Hello! I'm Ayatullahi, a passionate web developer dedicated to crafting beautiful and functional web experiences. With a strong background in both front-end and back-end technologies, I bring ideas to life on the web, focusing on user experience, performance, and scalability.
    </p>
    <ul>
      <li>Location: Lagos, Nigeria</li>
      <li>Education: B.Sc. in Computer Science</li>
      <li>Languages: English, Yoruba</li>
    </ul>
  </section>

  <section id="skills">
    <h2>Skills & Technologies</h2>
    <div class="skills-list">
      <div>
        <h3>Frontend</h3>
        <ul>
          <li>HTML5, CSS3, JavaScript (ES6+)</li>
          <li>React.js, Vue.js</li>
          <li>Bootstrap, Tailwind CSS</li>
        </ul>
      </div>
      <div>
        <h3>Backend</h3>
        <ul>
          <li>Node.js, Express.js</li>
          <li>Python (Django, Flask)</li>
          <li>PHP (Laravel)</li>
        </ul>
      </div>
      <div>
        <h3>Tools & Others</h3>
        <ul>
          <li>Git & GitHub</li>
          <li>REST APIs</li>
          <li>MongoDB, MySQL, PostgreSQL</li>
          <li>Docker, CI/CD</li>
        </ul>
      </div>
    </div>
  </section>

  <section id="experience">
    <h2>Experience</h2>
    <div class="experience-list">
      <div class="experience">
        <h3>Web Developer | Freelance</h3>
        <p><strong>2022 – Present</strong></p>
        <ul>
          <li>Developed and launched dynamic websites for small businesses and startups.</li>
          <li>Worked closely with clients to understand requirements and deliver tailored solutions.</li>
          <li>Optimized sites for SEO and fast load times.</li>
        </ul>
      </div>
      <div class="experience">
        <h3>Intern | Tech Innovations Ltd</h3>
        <p><strong>2021 – 2022</strong></p>
        <ul>
          <li>Collaborated on a team project to build a task management application using React and Node.js.</li>
          <li>Implemented user authentication and role-based access control.</li>
        </ul>
      </div>
    </div>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="project-list">
      <div class="project">
        <h3>Personal Blog</h3>
        <p>A responsive blog built with HTML, CSS, and JavaScript. Features include post categories, comments, and dark mode.</p>
        <a href="#" target="_blank">View Project</a>
      </div>
      <div class="project">
        <h3>Task Manager App</h3>
        <p>A full-stack application to manage daily tasks, built with React and Node.js. Includes user authentication and RESTful API.</p>
        <a href="#" target="_blank">View Project</a>
      </div>
      <div class="project">
        <h3>E-commerce Website</h3>
        <p>An online store built with Laravel and Vue.js, featuring product search, cart, and payment integration.</p>
        <a href="#" target="_blank">View Project</a>
      </div>
    </div>
  </section>

  <section id="testimonials">
    <h2>Testimonials</h2>
    <div class="testimonials-list">
      <blockquote>
        "Ayatullahi delivered our website ahead of schedule and exceeded our expectations. Highly recommended!"<br>
        <span>— Sarah B., Business Owner</span>
      </blockquote>
      <blockquote>
        "Professional, skilled, and a great communicator. Will work with Ayatullahi again."<br>
        <span>— James O., Startup Founder</span>
      </blockquote>
    </div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <form class="contact-form">
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required>
      
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>
      
      <label for="message">Message:</label>
      <textarea id="message" name="message" rows="5" required></textarea>
      
      <button type="submit">Send Message</button>
    </form>
    <p>Email: <a href="mailto:ayatullahi@example.com">ayatullahi@example.com</a></p>
    <p>LinkedIn: <a href="https://www.linkedin.com/in/ayatullahi" target="_blank">linkedin.com/in/ayatullahi</a></p>
    <!-- Add more contact options if needed -->
  </section>

  <footer>
    <p>&copy; 2025 Ayatullahi. All rights reserved.</p>
  </footer>
</body>
</html>
