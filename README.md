<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Dheeraj | Portfolio</title>
  <style>
    body {
      font-family: "Poppins", sans-serif;
      background: #0d1117;
      color: #c9d1d9;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
      padding: 20px;
      text-align: center;
    }

    h1 {
      font-size: 2.5rem;
      color: #58a6ff;
    }

    h2 {
      color: #9be9a8;
      margin-top: 20px;
    }

    p {
      font-size: 1rem;
      line-height: 1.6;
      max-width: 600px;
      margin: 10px auto;
    }

    ul {
      list-style: none;
      padding: 0;
    }

    li {
      margin: 10px 0;
      font-size: 1.1rem;
    }

    li span {
      color: #f0f6fc;
      font-weight: bold;
    }

    .skills {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      margin-top: 15px;
    }

    .skill {
      background: #161b22;
      border: 1px solid #30363d;
      border-radius: 12px;
      padding: 10px 15px;
      margin: 8px;
      color: #f0f6fc;
      transition: transform 0.3s, background 0.3s;
    }

    .skill:hover {
      background: #238636;
      transform: scale(1.05);
    }

    .contact {
      margin-top: 25px;
      background: #161b22;
      padding: 15px 20px;
      border-radius: 12px;
    }

    a {
      color: #58a6ff;
      text-decoration: none;
      transition: color 0.3s;
    }

    a:hover {
      color: #9be9a8;
    }

    .emoji {
      animation: wave 2s infinite;
      display: inline-block;
      transform-origin: 70% 70%;
    }

    @keyframes wave {
      0%, 100% { transform: rotate(0deg); }
      20%, 60% { transform: rotate(-15deg); }
      40%, 80% { transform: rotate(10deg); }
    }
  </style>
</head>
<body>
  <h1>Hi there <span class="emoji">👋</span></h1>
  <h2>I'm Dheeraj</h2>
  <p>
    A passionate developer skilled in <strong>Java</strong>, <strong>HTML</strong>, <strong>CSS</strong>, 
    <strong>JavaScript</strong>, <strong>Spring Boot</strong>, <strong>Hibernate</strong>, and <strong>DevOps</strong>.
  </p>

  <ul>
    <li>🚀 I'm currently working on <span>Spring Boot REST APIs</span></li>
    <li>📘 I'm currently learning <span>DevOps tools (Docker, Jenkins, AWS)</span></li>
    <li>🤝 I'm looking to collaborate on <span>Full Stack projects</span></li>
    <li>💡 Ask me about <span>Backend Development, APIs, and Project Deployment</span></li>
  </ul>

  <h2>🛠️ Skills</h2>
  <div class="skills">
    <div class="skill">Java</div>
    <div class="skill">HTML</div>
    <div class="skill">CSS</div>
    <div class="skill">JavaScript</div>
    <div class="skill">Spring Boot</div>
    <div class="skill">Hibernate</div>
    <div class="skill">MySQL</div>
    <div class="skill">GitHub</div>
    <div class="skill">DevOps</div>
  </div>

  <div class="contact">
    <p>📫 How to reach me: <a href="mailto:dheeraj@example.com">dheeraj@example.com</a></p>
    <p>🌐 GitHub: <a href="https://github.com/dheer31" target="_blank">github.com/dheer31</a></p>
  </div>

  <script>
    // Simple greeting effect
    document.addEventListener("DOMContentLoaded", () => {
      console.log("Welcome to Dheeraj's Portfolio 🚀");
    });
  </script>
</body>
</html>
