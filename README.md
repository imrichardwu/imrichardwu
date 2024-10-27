<!DOCTYPE html>
<html>
<head>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap');
  
  body {
    font-family: 'Inter', sans-serif;
    line-height: 1.6;
    max-width: 900px;
    margin: 0 auto;
    padding: 20px;
    color: #1F2937;
    background-color: #F9FAFB;
  }
  
  .header {
    text-align: center;
    margin-bottom: 2rem;
  }
  
  .badge-container {
    display: flex;
    gap: 1rem;
    justify-content: center;
    flex-wrap: wrap;
    margin: 1rem 0;
  }
  
  .section {
    margin: 2.5rem 0;
    padding: 1.5rem;
    border-radius: 12px;
    background: white;
    box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1);
  }
  
  .grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 1.5rem;
    margin: 1rem 0;
  }
  
  .skill-category {
    padding: 1rem;
    border-radius: 8px;
    background: #F3F4F6;
  }
  
  .skill-list {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
  }
  
  .skill-tag {
    background: #E5E7EB;
    padding: 0.25rem 0.75rem;
    border-radius: 9999px;
    font-size: 0.875rem;
    color: #4B5563;
  }
  
  .stats-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 1rem;
    margin-top: 1rem;
  }
  
  .connect-grid {
    display: flex;
    justify-content: center;
    gap: 1rem;
    flex-wrap: wrap;
    margin-top: 1rem;
  }
  
  .connect-button {
    padding: 0.5rem 1rem;
    border-radius: 8px;
    color: white;
    text-decoration: none;
    font-weight: 500;
    transition: opacity 0.2s;
  }
  
  .connect-button:hover {
    opacity: 0.9;
  }
</style>
</head>
<body>

<div class="header">
  <h1>👋 Hey, I'm Richard!</h1>
  <div class="badge-container">
    <img src="https://komarev.com/ghpvc/?username=imrichardwu&color=blueviolet&style=for-the-badge" alt="Profile Views" />
    <img src="https://img.shields.io/github/followers/imrichardwu?label=Followers&style=for-the-badge&logo=github" alt="GitHub Followers" />
  </div>
  <p>
    Computer Science Student at <strong>University of Alberta</strong> | Full Stack Developer | AI Enthusiast
  </p>
</div>

<div class="section">
  <h2>👨‍💻 About Me</h2>
  <div class="grid">
    <div>
      <ul>
        <li>📍 From Calgary, based in Edmonton, AB</li>
        <li>🎓 Sophomore at University of Alberta</li>
        <li>🌱 Currently diving deep into AI and game development</li>
        <li>💡 Passionate about solving complex problems</li>
        <li>🌐 Portfolio: <a href="https://richardwu.netlify.app/">richardwu.netlify.app</a></li>
      </ul>
    </div>
    <img src="https://raw.githubusercontent.com/mikecodeur/mikecodeur/main/code.gif" width="100%" style="max-width: 350px; border-radius: 8px;" />
  </div>
</div>

<div class="section">
  <h2>🛠️ Technology Stack</h2>
  <div class="grid">
    <div class="skill-category">
      <h3>Languages</h3>
      <div class="skill-list">
        <span class="skill-tag">Python</span>
        <span class="skill-tag">JavaScript/TypeScript</span>
        <span class="skill-tag">Java</span>
        <span class="skill-tag">C/C++</span>
        <span class="skill-tag">SQL</span>
        <span class="skill-tag">R</span>
      </div>
    </div>
    
    <div class="skill-category">
      <h3>Frameworks & Libraries</h3>
      <div class="skill-list">
        <span class="skill-tag">React</span>
        <span class="skill-tag">Node.js</span>
        <span class="skill-tag">Next.js</span>
        <span class="skill-tag">Tailwind</span>
        <span class="skill-tag">Django</span>
        <span class="skill-tag">Bootstrap</span>
        <span class="skill-tag">PrismaORM</span>
        <span class="skill-tag">OpenGL</span>
      </div>
    </div>
    
    <div class="skill-category">
      <h3>Tools & Platforms</h3>
      <div class="skill-list">
        <span class="skill-tag">Git</span>
        <span class="skill-tag">GitHub</span>
        <span class="skill-tag">Linux</span>
        <span class="skill-tag">Android Studio</span>
        <span class="skill-tag">Figma</span>
        <span class="skill-tag">LaTeX</span>
      </div>
    </div>
  </div>
</div>

<div class="section">
  <h2>📊 GitHub Stats</h2>
  <div class="stats-grid">
    <img src="https://github-readme-stats.vercel.app/api?username=imrichardwu&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" style="width: 100%; border-radius: 8px;" />
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=imrichardwu&theme=tokyonight&hide_border=true" alt="GitHub Streak" style="width: 100%; border-radius: 8px;" />
  </div>
</div>

<div class="section">
  <h2>🌐 Let's Connect</h2>
  <div class="connect-grid">
    <a href="https://www.linkedin.com/in/imrichardwu/" class="connect-button" style="background-color: #0077B5;">
      LinkedIn
    </a>
    <a href="mailto:Richard9@ualberta.ca" class="connect-button" style="background-color: #D14836;">
      Email
    </a>
    <a href="https://richardwu.netlify.app/" class="connect-button" style="background-color: #000000;">
      Portfolio
    </a>
  </div>
</div>

<div style="text-align: center; margin-top: 2rem; color: #6B7280;">
  <p>👀 Visitor Count</p>
  <img src="https://profile-counter.glitch.me/imrichardwu/count.svg" alt="Visitor Count" />
  <p><i>Happy Coding! 👨‍💻</i></p>
</div>

</body>
</html>
