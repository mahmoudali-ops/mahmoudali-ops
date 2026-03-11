<div align="center">
  <!-- ANIMATED HEADER with typing effect and neon glow -->
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=32&duration=3000&pause=500&color=6A5ACD&center=true&vCenter=true&width=600&lines=Hi+there+%F0%9F%91%8B%2C+I'm+Mahmoud+Ali;Full+Stack+.NET+Developer+%F0%9F%92%BB" alt="Typing SVG" />
  </a>

  <!-- SPACE BACKGROUND (animated via GIF + CSS-friendly stars overlay) -->
  <div style="position: relative; width: 100%; max-width: 900px; margin: 0 auto; border-radius: 20px; overflow: hidden; box-shadow: 0 0 30px rgba(106, 90, 205, 0.5);">
    <!-- Deep space animated GIF background -->
    <img src="https://i.giphy.com/media/v1.Y2lkPTc5MGI3NjExc2t1bmI2d3k0Ymd0cHh6ZHp2d3ZqNnN5c2Nma2h3aXl5cHFhM3g2MiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/l0MYEqE4MWgOzAeFO/giphy.gif" alt="space background" style="width:100%; display: block; filter: brightness(0.8) saturate(1.5);" />
    
    <!-- Overlay twinkling stars (CSS animated) + planets + shooting stars -->
    <div style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; pointer-events: none; background: radial-gradient(circle at 20% 40%, rgba(255,255,255,0.15) 1px, transparent 1px), radial-gradient(circle at 80% 70%, rgba(173,216,230,0.2) 2px, transparent 2px); background-size: 200px 200px, 300px 300px; animation: twinkle 4s infinite alternate;"></div>
    
    <!-- rotating planets (SVG/CSS) using absolutely positioned elements – we'll simulate with simple divs + orbit animations -->
    <div style="position: absolute; top: 20%; left: 10%; width: 40px; height: 40px; border-radius: 50%; background: linear-gradient(145deg, #b8860b, #ffd700); box-shadow: 0 0 30px #ffd700; animation: orbit 20s linear infinite;"></div>
    <div style="position: absolute; bottom: 30%; right: 15%; width: 60px; height: 60px; border-radius: 50%; background: linear-gradient(145deg, #4169e1, #00bfff); box-shadow: 0 0 40px #00bfff; animation: orbitReverse 25s linear infinite;"></div>
    <div style="position: absolute; top: 60%; left: 30%; width: 30px; height: 30px; border-radius: 50%; background: linear-gradient(145deg, #dc143c, #ff69b4); box-shadow: 0 0 30px #ff69b4; animation: orbit 30s linear infinite;"></div>
    
    <!-- nebula clouds (soft glowing) -->
    <div style="position: absolute; top: 10%; left: 50%; width: 200px; height: 100px; background: radial-gradient(circle, rgba(138,43,226,0.3) 0%, transparent 70%); filter: blur(30px); animation: float 15s ease-in-out infinite;"></div>
    <div style="position: absolute; bottom: 5%; left: 20%; width: 250px; height: 120px; background: radial-gradient(circle, rgba(0,191,255,0.2) 0%, transparent 70%); filter: blur(40px); animation: float 18s ease-in-out infinite reverse;"></div>
    
    <!-- shooting stars (pseudo-elements can't be inline, but we can use spans) -->
    <div style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;">
      <span style="position: absolute; top: 15%; left: -10%; width: 150px; height: 2px; background: linear-gradient(90deg, transparent, white, transparent); transform: rotate(20deg); animation: shoot 8s ease-in-out infinite;"></span>
      <span style="position: absolute; top: 60%; left: -5%; width: 200px; height: 2px; background: linear-gradient(90deg, transparent, #ffdead, transparent); transform: rotate(15deg); animation: shoot 12s ease-in-out infinite 3s;"></span>
    </div>
  </div>

  <!-- ANIMATIONS KEYFRAMES (embedded as style) -->
  <style>
    @keyframes twinkle {
      0% { opacity: 0.6; }
      100% { opacity: 1; }
    }
    @keyframes orbit {
      0% { transform: rotate(0deg) translateX(80px) rotate(0deg); }
      100% { transform: rotate(360deg) translateX(80px) rotate(-360deg); }
    }
    @keyframes orbitReverse {
      0% { transform: rotate(0deg) translateX(120px) rotate(0deg); }
      100% { transform: rotate(-360deg) translateX(120px) rotate(360deg); }
    }
    @keyframes float {
      0% { transform: translate(0, 0) scale(1); }
      50% { transform: translate(20px, -20px) scale(1.1); }
      100% { transform: translate(0, 0) scale(1); }
    }
    @keyframes shoot {
      0% { left: -10%; top: 20%; opacity: 1; }
      70% { opacity: 1; }
      100% { left: 110%; top: 50%; opacity: 0; }
    }
    /* progress bar animations */
    .skill-bar { width: 100%; background-color: #2d2d4a; border-radius: 20px; margin: 8px 0; overflow: hidden; }
    .skill-fill { height: 20px; border-radius: 20px; background: linear-gradient(90deg, #6a5acd, #00bfff); box-shadow: 0 0 10px #00bfff; width: 0; animation: fillBar 2s ease-out forwards; }
    @keyframes fillBar { to { width: var(--target); } }
    /* card hover glow */
    .project-card:hover { transform: scale(1.02); box-shadow: 0 0 30px #6a5acd; transition: all 0.3s ease; }
  </style>
</div>

<!-- ABOUT ME SECTION -->
<h2 align="center" style="color: #e0e0ff; text-shadow: 0 0 8px #6a5acd;">✨ About Me ✨</h2>
<p align="center" style="font-size: 1.2rem; background: rgba(10, 10, 30, 0.7); padding: 20px; border-radius: 30px; max-width: 800px; margin: 20px auto; color: #f0f0ff; box-shadow: 0 0 30px #4b0082;">
  Hello! I'm Mahmoud Ali, a passionate Full Stack .NET Developer 💻.<br>
  I love building modern, scalable web applications with clean code and best practices 🚀.<br>
  🌐 Full Stack Development (ASP.NET Core + Angular) | 📊 Dynamic dashboards & systems<br>
  💾 SQL Server & Database Design | ⚡ Always exploring new technologies.
</p>

<!-- SOCIAL LINKS with modern shield badges -->
<h2 align="center" style="color: #e0e0ff;">🤝 Connect with Me 🤝</h2>
<p align="center">
  <a href="https://www.linkedin.com/in/mahmoud-ali-46b872234"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&style=flat&labelColor=0A0A2A&color=6A5ACD" alt="LinkedIn" /></a>
  <a href="https://www.facebook.com/share/18hKrCWC9n/"><img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white&style=flat&labelColor=0A0A2A&color=6A5ACD" alt="Facebook" /></a>
  <a href="https://www.instagram.com/mahmoud.ali._.2000"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white&style=flat&labelColor=0A0A2A&color=6A5ACD" alt="Instagram" /></a>
  <a href="mailto:mahmoua487@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white&style=flat&labelColor=0A0A2A&color=6A5ACD" alt="Email" /></a>
  <a href="https://drive.google.com/file/d/1MtxsFC7PmU1SmqxXXi0F-21PZERSX2DI/view"><img src="https://img.shields.io/badge/Download_CV-00C853?style=for-the-badge&logo=google-drive&logoColor=white&style=flat&labelColor=0A0A2A&color=6A5ACD" alt="CV" /></a>
</p>

<!-- TECH STACK ICONS (skillicons.dev) with hover glow -->
<h2 align="center" style="color: #e0e0ff;">🛠️ Tech Stack 🛠️</h2>
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=dotnet,cs,angular,ts,js,html,css,bootstrap,postman,git,github,visualstudio,vscode,sqlite&perline=7" style="filter: drop-shadow(0 0 10px #6a5acd); transition: filter 0.3s;" onmouseover="this.style.filter='drop-shadow(0 0 20px #00bfff)'" onmouseout="this.style.filter='drop-shadow(0 0 10px #6a5acd)'" />
  </a>
</p>

<!-- SKILLS SECTION (animated progress bars) -->
<h2 align="center" style="color: #e0e0ff;">📈 Skills Proficiency 📈</h2>
<div align="center" style="max-width: 600px; margin: auto;">
  <div style="width: 100%; margin: 10px 0;"><span style="color:#00bfff;">ASP.NET Core</span> <span style="float:right;">90%</span><div class="skill-bar"><div class="skill-fill" style="--target:90%;"></div></div></div>
  <div style="width: 100%; margin: 10px 0;"><span style="color:#00bfff;">Angular</span> <span style="float:right;">85%</span><div class="skill-bar"><div class="skill-fill" style="--target:85%;"></div></div></div>
  <div style="width: 100%; margin: 10px 0;"><span style="color:#00bfff;">C#</span> <span style="float:right;">90%</span><div class="skill-bar"><div class="skill-fill" style="--target:90%;"></div></div></div>
  <div style="width: 100%; margin: 10px 0;"><span style="color:#00bfff;">TypeScript</span> <span style="float:right;">85%</span><div class="skill-bar"><div class="skill-fill" style="--target:85%;"></div></div></div>
  <div style="width: 100%; margin: 10px 0;"><span style="color:#00bfff;">JavaScript</span> <span style="float:right;">75%</span><div class="skill-bar"><div class="skill-fill" style="--target:75%;"></div></div></div>
  <div style="width: 100%; margin: 10px 0;"><span style="color:#00bfff;">HTML & CSS</span> <span style="float:right;">85%</span><div class="skill-bar"><div class="skill-fill" style="--target:85%;"></div></div></div>
  <div style="width: 100%; margin: 10px 0;"><span style="color:#00bfff;">Bootstrap</span> <span style="float:right;">85%</span><div class="skill-bar"><div class="skill-fill" style="--target:85%;"></div></div></div>
  <div style="width: 100%; margin: 10px 0;"><span style="color:#00bfff;">SQL Server</span> <span style="float:right;">80%</span><div class="skill-bar"><div class="skill-fill" style="--target:80%;"></div></div></div>
  <div style="width: 100%; margin: 10px 0;"><span style="color:#00bfff;">Git & GitHub</span> <span style="float:right;">90%</span><div class="skill-bar"><div class="skill-fill" style="--target:90%;"></div></div></div>
  <div style="width: 100%; margin: 10px 0;"><span style="color:#00bfff;">Postman</span> <span style="float:right;">75%</span><div class="skill-bar"><div class="skill-fill" style="--target:75%;"></div></div></div>
  <div style="width: 100%; margin: 10px 0;"><span style="color:#00bfff;">VS Code & Visual Studio</span> <span style="float:right;">90%</span><div class="skill-bar"><div class="skill-fill" style="--target:90%;"></div></div></div>
</div>

<!-- GITHUB STATS + PROFILE VIEWS -->
<h2 align="center" style="color: #e0e0ff;">📊 GitHub Stats 📊</h2>
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=mahmoudali-ops&label=Profile%20views&color=6a5acd&style=flat" alt="profile views" style="box-shadow: 0 0 15px #6a5acd;" />
</p>
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=mahmoudali-ops&show_icons=true&theme=midnight-purple&hide_border=true&bg_color=0A0A2A&title_color=6A5ACD&icon_color=00BFFF&text_color=FFFFFF" alt="GitHub stats" height="170" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=mahmoudali-ops&layout=compact&theme=midnight-purple&hide_border=true&bg_color=0A0A2A&title_color=6A5ACD&text_color=FFFFFF" alt="top langs" height="170" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=mahmoudali-ops&theme=midnight-purple&hide_border=true&background=0A0A2A&stroke=6A5ACD&ring=00BFFF&fire=00BFFF&currStreakNum=FFFFFF" alt="GitHub streak" height="170" />
</p>

<!-- FEATURED PROJECTS (animated cards) -->
<h2 align="center" style="color: #e0e0ff;">🚀 Featured Projects 🚀</h2>
<div align="center" style="display: flex; flex-wrap: wrap; justify-content: center; gap: 25px; margin: 30px 0;">
  <!-- Card 1 -->
  <div class="project-card" style="width: 280px; background: rgba(20, 20, 50, 0.9); border-radius: 30px; padding: 20px; border: 2px solid #6a5acd; box-shadow: 0 0 20px #4b0082; transition: 0.3s; backdrop-filter: blur(5px);">
    <h3 style="color: #00bfff;">🛒 Multi Vendor E-Commerce</h3>
    <p style="color: #ccc;">ASP.NET Core Web API + Angular + Stripe. Full-featured marketplace with payments.</p>
    <a href="https://github.com/mahmoudali-ops?tab=repositories" style="color: #e0e0ff; background: #2d2d6a; padding: 8px 20px; border-radius: 50px; text-decoration: none; display: inline-block; box-shadow: 0 0 10px #6a5acd;">🔗 GitHub</a>
  </div>
  <!-- Card 2 -->
  <div class="project-card" style="width: 280px; background: rgba(20, 20, 50, 0.9); border-radius: 30px; padding: 20px; border: 2px solid #6a5acd; box-shadow: 0 0 20px #4b0082; transition: 0.3s; backdrop-filter: blur(5px);">
    <h3 style="color: #00bfff;">🏥 Clinic Appointment Booking</h3>
    <p style="color: #ccc;">Full stack booking system with calendar integration, patient management.</p>
    <a href="https://github.com/mahmoudali-ops?tab=repositories" style="color: #e0e0ff; background: #2d2d6a; padding: 8px 20px; border-radius: 50px; text-decoration: none; display: inline-block; box-shadow: 0 0 10px #6a5acd;">🔗 GitHub</a>
  </div>
  <!-- Card 3 -->
  <div class="project-card" style="width: 280px; background: rgba(20, 20, 50, 0.9); border-radius: 30px; padding: 20px; border: 2px solid #6a5acd; box-shadow: 0 0 20px #4b0082; transition: 0.3s; backdrop-filter: blur(5px);">
    <h3 style="color: #00bfff;">📚 Student Grades Management</h3>
    <p style="color: #ccc;">Grade management + statistics + PDF reports. Built with ASP.NET Core & Angular.</p>
    <a href="https://github.com/mahmoudali-ops?tab=repositories" style="color: #e0e0ff; background: #2d2d6a; padding: 8px 20px; border-radius: 50px; text-decoration: none; display: inline-block; box-shadow: 0 0 10px #6a5acd;">🔗 GitHub</a>
  </div>
</div>

<!-- DYNAMIC GIF BANNER (space/tech theme) -->
<div align="center">
  <img src="https://i.giphy.com/media/v1.Y2lkPTc5MGI3NjExdWZic3R1bmJ4Y3dubXJkMDV4bWl4ZzRleDdwM2R2eTh0ajM0bWU0dyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/3oKIPnAiaMCws8nOsE/giphy.gif" alt="animated coding" width="80%" style="border-radius: 30px; box-shadow: 0 0 40px #6a5acd;" />
</div>

<!-- FOOTER (with subtle glow) -->
<p align="center" style="color: #6a5acd; text-shadow: 0 0 5px #00bfff;">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=400&size=18&duration=2000&pause=1000&color=6A5ACD&center=true&vCenter=true&width=300&lines=Thanks+for+visiting!;Let's+build+something+great!" alt="footer typing" />
</p>

<!-- Ensure all animations are defined even for older markdown viewers (style block already included) -->
