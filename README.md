<p align="center">
  <img src="WhatsApp Image 2026-01-04 at 5.30.53 PM.jpeg" alt="Ayesha Younes Cover" />
</p>
<br>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ayesha Younes | Tech Profile</title>
  <link href="https://fonts.googleapis.com/css2?family=Fira+Code:wght@400;600&display=swap" rel="stylesheet">
  <style>
    /* --- GLOBAL STYLES --- */
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      font-family: 'Fira Code', monospace;
      background-color: #0d1117;
      color: #c9d1d9;
      line-height: 1.6;
    }
    a { color: #58a6ff; text-decoration: none; }
    img { max-width: 100%; }

    /* --- HEADER --- */
    header {
      text-align: center;
      padding: 60px 20px 40px;
      background: linear-gradient(135deg, #161b22, #0d1117);
    }
    header h1 {
      font-size: 3rem;
      color: #7a3eff;
    }
    .typing-animation {
      font-size: 1.2rem;
      color: #58a6ff;
      margin-top: 15px;
      white-space: nowrap;
      overflow: hidden;
      border-right: 3px solid #58a6ff;
      width: 22ch;
      animation: typing 4s steps(22), blink 0.75s step-end infinite alternate;
      margin: 0 auto;
    }
    @keyframes typing { from { width: 0 } to { width: 22ch } }
    @keyframes blink { 50% { border-color: transparent; } }

    /* --- SECTIONS --- */
    section { padding: 60px 20px; max-width: 1000px; margin: auto; }
    .section-title { font-size: 2rem; color: #7a3eff; margin-bottom: 20px; text-align: center; }
    .two-column { display: flex; flex-wrap: wrap; align-items: center; justify-content: space-between; gap: 30px; }
    .two-column .text { flex: 1; min-width: 280px; }
    .two-column .image { flex: 1; min-width: 280px; text-align: center; }

    /* --- BADGES --- */
    .badges img { margin: 5px; }

    /* --- SKILLS --- */
    .skill-bar {
      position: relative;
      display: block;
      margin: 10px 0;
      background: #161b22;
      border-radius: 50px;
      overflow: hidden;
      height: 20px;
    }
    .skill-bar span {
      display: block;
      height: 100%;
      background: #7a3eff;
      border-radius: 50px;
    }

    /* --- FOOTER --- */
    footer {
      text-align: center;
      padding: 40px 20px;
      background: linear-gradient(135deg, #161b22, #0d1117);
      color: #58a6ff;
    }

    /* --- ANIMATED LINES --- */
    .wave-line {
      width: 100%;
      height: 3px;
      background: linear-gradient(90deg, #7a3eff, #58a6ff, #7a3eff);
      background-size: 200% 100%;
      animation: wave 2s linear infinite;
      margin: 30px 0;
    }
    @keyframes wave { 0%{background-position:200% 0} 100%{background-position:-200% 0} }

    /* --- RESPONSIVE --- */
    @media(max-width: 768px) {
      .two-column { flex-direction: column; text-align: center; }
    }
  </style>
</head>
<body>

  <!-- HEADER -->
  <header>
    <h1>Ayesha Younes</h1>
    <div class="typing-animation">CS Student | CCNA | Cloud Basics | AI Learner | Designer</div>
  </header>

  <!-- ABOUT -->
  <section>
    <h2 class="section-title">👩‍💻 About Me</h2>
    <div class="two-column">
      <div class="text">
        <p>🎓 Computer Science Student</p>
        <p>📡 CCNA Certified</p>
        <p>☁️ Huawei Cloud (Basic)</p>
        <p>🐍 Learning Python & AI</p>
        <p>🎨 Graphic Designing (Canva) & Sketching</p>
      </div>
      <div class="image">
        <img src="https://cdn-icons-png.flaticon.com/512/1015/1015220.png" alt="Coding Illustration" width="250">
      </div>
    </div>
  </section>

  <div class="wave-line"></div>

  <!-- SKILLS -->
  <section>
    <h2 class="section-title">🛠 Skills</h2>
    <div class="badges" style="text-align:center;">
      <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white"/>
      <img src="https://img.shields.io/badge/C++-004482?style=for-the-badge&logo=cplusplus&logoColor=white"/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
      <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
      <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
      <img src="https://img.shields.io/badge/CCNA-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white"/>
      <img src="https://img.shields.io/badge/Cloud-FF0000?style=for-the-badge&logo=huawei&logoColor=white"/>
      <img src="https://img.shields.io/badge/Canva-00C4CC?style=for-the-badge&logo=canva&logoColor=white"/>
    </div>

    <h3 style="text-align:center;margin-top:30px;">📊 Skill Progress</h3>
    <div style="max-width:600px;margin:auto;">
      <p>C/C++</p><div class="skill-bar"><span style="width:75%"></span></div>
      <p>Networking</p><div class="skill-bar"><span style="width:70%"></span></div>
      <p>Design</p><div class="skill-bar"><span style="width:60%"></span></div>
      <p>Python</p><div class="skill-bar"><span style="width:50%"></span></div>
      <p>Cloud Basics</p><div class="skill-bar"><span style="width:40%"></span></div>
      <p>AI / ML</p><div class="skill-bar"><span style="width:25%"></span></div>
    </div>
  </section>

  <div class="wave-line"></div>

  <!-- CONNECT -->
  <section>
    <h2 class="section-title">📫 Connect With Me</h2>
    <p style="text-align:center;">
      <a href="https://www.linkedin.com/in/ayesha-younes"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin"/></a>
      <a href="https://github.com/Ayesha-younes"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github"/></a>
      <a href="mailto:ayesha.younes@example.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail"/></a>
    </p>
  </section>

  <!-- FOOTER -->
  <footer>
    <p>🌱 Always learning | ⭐ Consistency > Perfection | 💡 Ideas into Reality</p>
    <p>Made with ❤️ by Ayesha Younes</p>
  </footer>

</body>
</html>
