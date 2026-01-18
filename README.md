<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Arish | Villain Mode</title>

  <style>
    body {
      margin: 0;
      height: 100vh;
      background: #000;
      color: #fff;
      font-family: Arial, Helvetica, sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      overflow: hidden;
    }

    .container {
      position: relative;
      text-align: center;
      max-width: 700px;
      padding: 40px;
      z-index: 2;
    }

    h1 {
      font-size: 52px;
      letter-spacing: 3px;
      margin-bottom: 10px;
    }

    h3 {
      font-weight: normal;
      opacity: 0.8;
      margin-bottom: 30px;
    }

    .bio {
      line-height: 1.8;
      opacity: 0.9;
    }

    .dragon {
      position: absolute;
      width: 280px;
      pointer-events: none;
      animation: orbit 8s linear infinite, float 3s ease-in-out infinite;
      z-index: 1;
      filter: drop-shadow(0 0 25px rgba(255,255,255,0.3));
    }

    @keyframes orbit {
      0%   { transform: translate(-220px, -120px); }
      25%  { transform: translate(220px, -160px); }
      50%  { transform: translate(260px, 120px); }
      75%  { transform: translate(-220px, 160px); }
      100% { transform: translate(-220px, -120px); }
    }

    @keyframes float {
      0%   { transform: translateY(0); }
      50%  { transform: translateY(-15px); }
      100% { transform: translateY(0); }
    }

    .links {
      margin-top: 25px;
      font-size: 14px;
      opacity: 0.8;
    }

    .links a {
      color: #fff;
      text-decoration: none;
      margin: 0 10px;
      border-bottom: 1px solid rgba(255,255,255,0.3);
    }

    .links a:hover {
      opacity: 1;
    }
  </style>
</head>

<body>

  <img 
    class="dragon" 
    src="https://media.giphy.com/media/LmNwrBhejkK9EFP504/giphy.gif" 
    alt="Dragon"
  />

  <div class="container">
    <h1>ARISH</h1>
    <h3>Frontend Developer | AI Builder | Controlled Chaos</h3>

    <div class="bio">
      Working on AI tools, web apps, and ideas that escalate fast.<br><br>
      Collaborating on open-source, dev tools, and controlled chaos.<br><br>
      Learning Next.js, Three.js, Docker, and Prompt Engineering.<br><br>
      Ask me about React, Tailwind, Python.<br><br>
      Most ideas start at 2 AM. Consequences follow.
    </div>

    <div class="links">
      <a href="https://github.com/TROJANmocX" target="_blank">GitHub</a>
      <a href="https://linkedin.com/in/arish-ali-8670341b3" target="_blank">LinkedIn</a>
      <a href="https://instagram.com/trojan_mocx" target="_blank">Instagram</a>
      <a href="https://dev.to/trojanmocx" target="_blank">Dev.to</a>
    </div>
  </div>

</body>
</html>
