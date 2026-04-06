<!-- 💜 CUSTOM SEMI-CIRCLE ANIMATED HEADER -->
<p align="center">
<svg width="100%" height="260" viewBox="0 0 800 260" xmlns="http://www.w3.org/2000/svg">

  <defs>
    <!-- 🌈 Animated Gradient -->
    <linearGradient id="grad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#4b0082">
        <animate attributeName="stop-color" values="#4b0082;#8a2be2;#da70d6;#4b0082" dur="6s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" stop-color="#da70d6">
        <animate attributeName="stop-color" values="#da70d6;#8a2be2;#4b0082;#da70d6" dur="6s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>

    <!-- Glow -->
    <filter id="glow">
      <feGaussianBlur stdDeviation="5" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- 💜 Semi Circle -->
  <path d="M0,200 Q400,0 800,200 L800,260 L0,260 Z"
        fill="url(#grad)" filter="url(#glow)"/>

  <!-- ⚡ Moving Particles -->
  <circle r="4" fill="#ffffff">
    <animateMotion dur="6s" repeatCount="indefinite"
      path="M0,200 Q400,0 800,200"/>
  </circle>

  <circle r="3" fill="#00F7FF">
    <animateMotion dur="8s" repeatCount="indefinite"
      path="M800,200 Q400,0 0,200"/>
  </circle>

  <circle r="5" fill="#da70d6">
    <animateMotion dur="7s" repeatCount="indefinite"
      path="M200,200 Q400,50 600,200"/>
  </circle>

  <!-- 👋 TEXT -->
  <text x="50%" y="120" text-anchor="middle"
        font-size="38"
        fill="white"
        font-family="Arial"
        font-weight="bold">
    Hi I'm Pearl 👋
  </text>

  <!-- ✨ SUBTEXT -->
  <text x="50%" y="155" text-anchor="middle"
        font-size="16"
        fill="#e0e0e0"
        font-family="Arial">
    Welcome to my profile
  </text>

</svg>
</p>

<!-- 👾 PROFILE ICON -->
<p align="center">
  <img src="https://avatars.githubusercontent.com/u/000000?v=4" width="100" style="border-radius:50%; border:3px solid #8a2be2;" />
</p>

<!-- ✨ ANIMATED TEXT -->
<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?color=DA70D6&size=26&center=true&vCenter=true&width=800&lines=AI%2FML+Explorer;Hackathon+Enthusiast;Building+Impactful+Projects;Creative+Developer&duration=2500&pause=800" />
</p>

<!-- 💜 GLOW DIVIDER -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:da70d6,50:8a2be2,100:4b0082&height=3"/>
</p>

---

# 💜 ABOUT ME

I’m an enthusiastic developer passionate about building impactful, real-world tech solutions.  
I enjoy transforming ideas into clean, functional products with modern technologies and intuitive user experiences.

---

# 🚀 CURRENTLY EXPLORING

- ⚡ Hackathons & rapid product building  
- 🧠 Artificial Intelligence & Machine Learning  
- 🌍 Real-world problem solving  

---

# 🌐 CONNECT WITH ME

<p align="center">
  <a href="https://linkedin.com/in/your-linkedin">
    <img src="https://img.shields.io/badge/LinkedIn-4b0082?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:pearlmeht@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-4b0082?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
</p>

---

# ⚡ TECH STACK

<p align="center">
<img src="https://skillicons.dev/icons?i=python,js,dart,java,cpp,c,kotlin,flutter,react,html,css,tailwind,flask,firebase,fastapi,mongodb,mysql,sqlite,supabase,tensorflow,pytorch,sklearn,git,github,vscode,androidstudio,figma,postman&theme=dark" />
</p>

---

# 🎯 WHAT I DO

- Build full-stack applications with modern technologies  
- Explore and implement AI/ML solutions  
- Participate in hackathons and rapid MVP development  
- Focus on clean UI/UX and scalable systems  

---

<!-- 💜 NEON FOOTER -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:da70d6,50:8a2be2,100:4b0082&height=150&section=footer"/>
</p>
