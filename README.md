<!-- ════════════════════════════════════════════════════════════════════ -->
<!--  KASHYAP PATEL · GitHub Profile README                              -->
<!--  v3 · Full Redesign · 3D ELEMENTS · MAX ANIMATIONS                  -->
<!-- ════════════════════════════════════════════════════════════════════ -->

<div align="center">

<!-- ────────── 3D ANIMATED HEADER BANNER ────────── -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00d2ff,30:a18cd1,60:f5576c,80:f6d365,100:43e97b&height=240&section=header&text=Kashyap%20Patel&fontSize=48&fontColor=ffffff&animation=twinkling&fontAlignY=34&desc=Full-Stack%20Developer%20%C2%B7%20System%20Architect%20%C2%B7%20Problem%20Solver&descAlignY=56&descSize=16&stroke=00d2ff&strokeWidth=2" width="100%" alt="3D Header Banner" />

<br/>

<!-- ────────── 3D ROTATING CUBE HERO ────────── -->
<svg viewBox="0 0 280 220" width="280" height="220" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- 3D gradient faces -->
    <linearGradient id="cubeTop" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#00d2ff" stop-opacity="0.95"/>
      <stop offset="100%" stop-color="#0080a8" stop-opacity="0.9"/>
    </linearGradient>
    <linearGradient id="cubeLeft" x1="100%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" stop-color="#f5576c" stop-opacity="0.9"/>
      <stop offset="100%" stop-color="#a02038" stop-opacity="0.95"/>
    </linearGradient>
    <linearGradient id="cubeRight" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#43e97b" stop-opacity="0.9"/>
      <stop offset="100%" stop-color="#1a8a3f" stop-opacity="0.95"/>
    </linearGradient>
    <radialGradient id="cubeShadow" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#000" stop-opacity="0.5"/>
      <stop offset="100%" stop-color="#000" stop-opacity="0"/>
    </radialGradient>
    <filter id="cubeGlow">
      <feGaussianBlur stdDeviation="3" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- Drop shadow on ground -->
  <ellipse cx="140" cy="200" rx="70" ry="10" fill="url(#cubeShadow)">
    <animate attributeName="rx" values="70;55;70" dur="3s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.5;0.3;0.5" dur="3s" repeatCount="indefinite"/>
  </ellipse>

  <!-- Floating + rotating 3D cube -->
  <g>
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,-12; 0,0" dur="3s" repeatCount="indefinite"/>
    <!-- Top face (rhombus) -->
    <polygon points="140,40 220,80 140,120 60,80" fill="url(#cubeTop)" stroke="#00d2ff" stroke-width="1.5">
      <animate attributeName="opacity" values="0.95;1;0.95" dur="2s" repeatCount="indefinite"/>
    </polygon>
    <!-- Left face -->
    <polygon points="60,80 140,120 140,200 60,160" fill="url(#cubeLeft)" stroke="#f5576c" stroke-width="1.5"/>
    <!-- Right face -->
    <polygon points="220,80 140,120 140,200 220,160" fill="url(#cubeRight)" stroke="#43e97b" stroke-width="1.5"/>
    <!-- Top face inner glow -->
    <polygon points="140,55 205,87 140,118 75,87" fill="none" stroke="#fff" stroke-width="0.5" opacity="0.4"/>
  </g>

  <!-- Orbiting electron around the cube -->
  <g>
    <animateTransform attributeName="transform" type="rotate" from="0 140 120" to="360 140 120" dur="6s" repeatCount="indefinite"/>
    <circle cx="240" cy="120" r="4" fill="#f6d365">
      <animate attributeName="r" values="4;6;4" dur="1.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="240" cy="120" r="2" fill="#fff" opacity="0.9"/>
  </g>
  <g>
    <animateTransform attributeName="transform" type="rotate" from="180 140 120" to="-180 140 120" dur="8s" repeatCount="indefinite"/>
    <circle cx="40" cy="120" r="3" fill="#a18cd1">
      <animate attributeName="r" values="3;5;3" dur="1.8s" repeatCount="indefinite"/>
    </circle>
  </g>

  <!-- Twinkling background stars -->
  <circle cx="20" cy="30" r="1.2" fill="#fff"><animate attributeName="opacity" values="0.2;1;0.2" dur="2s" repeatCount="indefinite"/></circle>
  <circle cx="260" cy="20" r="1" fill="#fff"><animate attributeName="opacity" values="1;0.2;1" dur="2.5s" repeatCount="indefinite"/></circle>
  <circle cx="240" cy="180" r="1.3" fill="#fff"><animate attributeName="opacity" values="0.3;1;0.3" dur="1.8s" repeatCount="indefinite"/></circle>
  <circle cx="30" cy="180" r="0.9" fill="#fff"><animate attributeName="opacity" values="0.4;1;0.4" dur="2.3s" repeatCount="indefinite"/></circle>
  <circle cx="140" cy="15" r="0.7" fill="#fff"><animate attributeName="opacity" values="1;0.3;1" dur="1.6s" repeatCount="indefinite"/></circle>
</svg>

<br/>

<!-- ────────── TYPING ANIMATION ────────── -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=00D2FF&center=true&vCenter=true&random=false&width=640&lines=Hi+there+%F0%9F%91%8B+I'm+Kashyap+Patel;Full-Stack+Developer;React+%C2%B7+Node+%C2%B7+TypeScript;I+turn+ideas+into+scalable+apps;Always+learning+%F0%9F%9A%80" alt="Typing SVG" />
</a>

<br/><br/>

<!-- ────────── ANIMATED 3D ORBITING SYSTEM (replaces old orbit) ────────── -->
<svg viewBox="0 0 280 200" width="280" height="200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <radialGradient id="core3D">
      <stop offset="0%" stop-color="#fff" stop-opacity="1"/>
      <stop offset="30%" stop-color="#00d2ff" stop-opacity="1"/>
      <stop offset="70%" stop-color="#00d2ff" stop-opacity="0.4"/>
      <stop offset="100%" stop-color="#00d2ff" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="planet1" cx="35%" cy="35%">
      <stop offset="0%" stop-color="#ffaaaa"/>
      <stop offset="60%" stop-color="#f5576c"/>
      <stop offset="100%" stop-color="#7a0c1f"/>
    </radialGradient>
    <radialGradient id="planet2" cx="35%" cy="35%">
      <stop offset="0%" stop-color="#aaffaa"/>
      <stop offset="60%" stop-color="#43e97b"/>
      <stop offset="100%" stop-color="#0c4a1f"/>
    </radialGradient>
    <radialGradient id="planet3" cx="35%" cy="35%">
      <stop offset="0%" stop-color="#ffeaaa"/>
      <stop offset="60%" stop-color="#f6d365"/>
      <stop offset="100%" stop-color="#7a5a0c"/>
    </radialGradient>
    <radialGradient id="planet4" cx="35%" cy="35%">
      <stop offset="0%" stop-color="#dabbff"/>
      <stop offset="60%" stop-color="#a18cd1"/>
      <stop offset="100%" stop-color="#3a1c6a"/>
    </radialGradient>
    <linearGradient id="orbitStroke" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#00d2ff" stop-opacity="0.1"/>
      <stop offset="50%" stop-color="#00d2ff" stop-opacity="0.6"/>
      <stop offset="100%" stop-color="#00d2ff" stop-opacity="0.1"/>
    </linearGradient>
    <linearGradient id="orbitStroke2" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#43e97b" stop-opacity="0.1"/>
      <stop offset="50%" stop-color="#43e97b" stop-opacity="0.5"/>
      <stop offset="100%" stop-color="#43e97b" stop-opacity="0.1"/>
    </linearGradient>
    <linearGradient id="orbitStroke3" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#f5576c" stop-opacity="0.1"/>
      <stop offset="50%" stop-color="#f5576c" stop-opacity="0.5"/>
      <stop offset="100%" stop-color="#f5576c" stop-opacity="0.1"/>
    </linearGradient>
    <filter id="starGlow">
      <feGaussianBlur stdDeviation="2"/>
    </filter>
  </defs>

  <!-- Orbit rings (3D-tilted ellipses) -->
  <ellipse cx="140" cy="100" rx="120" ry="42" fill="none" stroke="url(#orbitStroke)" stroke-width="1.2" stroke-dasharray="3 4" opacity="0.8"/>
  <ellipse cx="140" cy="100" rx="95" ry="72" fill="none" stroke="url(#orbitStroke2)" stroke-width="1" stroke-dasharray="2 5" opacity="0.7" transform="rotate(30 140 100)"/>
  <ellipse cx="140" cy="100" rx="70" ry="55" fill="none" stroke="url(#orbitStroke3)" stroke-width="0.9" stroke-dasharray="1 6" opacity="0.6" transform="rotate(-25 140 100)"/>

  <!-- Sun core with pulsing glow -->
  <circle cx="140" cy="100" r="50" fill="url(#core3D)">
    <animate attributeName="r" values="50;58;50" dur="3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="140" cy="100" r="14" fill="#0a0a1a" stroke="#00d2ff" stroke-width="2">
    <animate attributeName="stroke-width" values="2;3.5;2" dur="2s" repeatCount="indefinite"/>
  </circle>
  <text x="140" y="105" fill="#00d2ff" font-family="monospace" font-size="12" font-weight="700" text-anchor="middle">KP</text>

  <!-- 3D shaded planets orbiting -->
  <g>
    <animateTransform attributeName="transform" type="rotate" from="0 140 100" to="360 140 100" dur="9s" repeatCount="indefinite"/>
    <circle cx="260" cy="100" r="7" fill="url(#planet1)">
      <animate attributeName="r" values="7;9;7" dur="1.5s" repeatCount="indefinite"/>
    </circle>
    <!-- Planet ring -->
    <ellipse cx="260" cy="100" rx="11" ry="3" fill="none" stroke="#f5576c" stroke-width="0.8" opacity="0.7" transform="rotate(20 260 100)"/>
  </g>
  <g>
    <animateTransform attributeName="transform" type="rotate" from="120 140 100" to="480 140 100" dur="7s" repeatCount="indefinite"/>
    <circle cx="140" cy="28" r="6" fill="url(#planet2)">
      <animate attributeName="r" values="6;8;6" dur="2s" repeatCount="indefinite"/>
    </circle>
  </g>
  <g>
    <animateTransform attributeName="transform" type="rotate" from="240 140 100" to="600 140 100" dur="11s" repeatCount="indefinite"/>
    <circle cx="210" cy="155" r="5" fill="url(#planet3)">
      <animate attributeName="r" values="5;7;5" dur="1.8s" repeatCount="indefinite"/>
    </circle>
  </g>
  <g>
    <animateTransform attributeName="transform" type="rotate" from="60 140 100" to="420 140 100" dur="13s" repeatCount="indefinite"/>
    <circle cx="70" cy="45" r="4.5" fill="url(#planet4)">
      <animate attributeName="r" values="4.5;6.5;4.5" dur="2.2s" repeatCount="indefinite"/>
    </circle>
  </g>

  <!-- Twinkling background stars -->
  <circle cx="20" cy="30" r="1" fill="#fff"><animate attributeName="opacity" values="0.2;1;0.2" dur="2s" repeatCount="indefinite"/></circle>
  <circle cx="260" cy="180" r="1" fill="#fff"><animate attributeName="opacity" values="1;0.2;1" dur="2.5s" repeatCount="indefinite"/></circle>
  <circle cx="40" cy="170" r="0.8" fill="#fff"><animate attributeName="opacity" values="0.3;1;0.3" dur="1.8s" repeatCount="indefinite"/></circle>
  <circle cx="250" cy="30" r="1" fill="#fff"><animate attributeName="opacity" values="0.4;1;0.4" dur="2.3s" repeatCount="indefinite"/></circle>
</svg>

<br/><br/>

<!-- ────────── SKILLS ICONS ────────── -->
<p>
  <img src="https://skillicons.dev/icons?i=react,nextjs,ts,js,tailwind,html,css&theme=dark&perline=14" alt="Frontend Skills" />
  <br/>
  <img src="https://skillicons.dev/icons?i=nodejs,express,py,flask,graphql&theme=dark&perline=14" alt="Backend Skills" />
  <br/>
  <img src="https://skillicons.dev/icons?i=postgres,mongodb,mysql,redis,prisma&theme=dark&perline=14" alt="Database Skills" />
  <br/>
  <img src="https://skillicons.dev/icons?i=git,github,docker,aws,vercel,postman,linux&theme=dark&perline=14" alt="DevOps Skills" />
</p>

<br/>

<!-- ────────── 3D ANIMATED DIVIDER ────────── -->
<svg width="420" height="28" viewBox="0 0 420 28" fill="none" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="divLineL" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#333" stop-opacity="0"/>
      <stop offset="100%" stop-color="#00d2ff" stop-opacity="0.8"/>
    </linearGradient>
    <linearGradient id="divLineR" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#00d2ff" stop-opacity="0.8"/>
      <stop offset="100%" stop-color="#333" stop-opacity="0"/>
    </linearGradient>
    <radialGradient id="divOrb" cx="35%" cy="35%">
      <stop offset="0%" stop-color="#aaf0ff"/>
      <stop offset="60%" stop-color="#00d2ff"/>
      <stop offset="100%" stop-color="#003a4a"/>
    </radialGradient>
  </defs>
  <line x1="0" y1="14" x2="180" y2="14" stroke="url(#divLineL)" stroke-width="0.8"/>
  <line x1="240" y1="14" x2="420" y2="14" stroke="url(#divLineR)" stroke-width="0.8"/>
  <!-- Center 3D orb -->
  <circle cx="210" cy="14" r="6" fill="url(#divOrb)">
    <animate attributeName="r" values="6;9;6" dur="2.5s" repeatCount="indefinite"/>
  </circle>
  <!-- Orbiting dots -->
  <circle cx="170" cy="14" r="1.5" fill="#f5576c">
    <animate attributeName="cx" values="170;250;170" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="cy" values="14;8;14;20;14" dur="4s" repeatCount="indefinite"/>
  </circle>
  <circle cx="250" cy="14" r="1.5" fill="#43e97b">
    <animate attributeName="cx" values="250;170;250" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="cy" values="14;20;14;8;14" dur="4s" repeatCount="indefinite"/>
  </circle>
</svg>

<br/>

<!-- ────────── CONNECT BADGES ────────── -->
<p>
  <a href="https://www.linkedin.com/in/kashyap-p">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://github.com/kashyap-p">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="mailto:kashyappatel0702@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

<p>
  <img src="https://komarev.com/ghpvc/?username=kashyap-p&label=Profile%20Visitors&color=00d2ff&style=for-the-badge&labelColor=08081a" alt="Visitor Count" />
  <img src="https://img.shields.io/github/followers/kashyap-p?label=Followers&style=for-the-badge&color=f5576c&labelColor=08081a" alt="Followers" />
</p>

</div>

---

<!-- ════════════════════ ABOUT ME ════════════════════ -->

<div align="center">

<br/>

<!-- Animated 3D quote bubble -->
<svg width="680" height="62" viewBox="0 0 680 62" fill="none" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="quoteBg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0a0a1a"/>
      <stop offset="100%" stop-color="#15101f"/>
    </linearGradient>
    <linearGradient id="quoteBorder" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#00d2ff"/>
      <stop offset="33%" stop-color="#f5576c"/>
      <stop offset="66%" stop-color="#f6d365"/>
      <stop offset="100%" stop-color="#43e97b">
        <animate attributeName="offset" values="1;0.66;1" dur="6s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
    <filter id="quoteGlow">
      <feGaussianBlur stdDeviation="2" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>
  <rect x="1" y="1" width="678" height="60" rx="30" fill="url(#quoteBg)" stroke="url(#quoteBorder)" stroke-width="2"/>
  <text x="340" y="38" fill="#e0e0f0" font-family="system-ui,-apple-system,sans-serif" font-size="14" font-weight="500" text-anchor="middle">⚡ "From UI mockups to database indexing — I build end-to-end applications that scale."</text>
  <!-- 3D corner accents -->
  <circle cx="20" cy="31" r="3" fill="#00d2ff">
    <animate attributeName="opacity" values="1;0.3;1" dur="2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="660" cy="31" r="3" fill="#43e97b">
    <animate attributeName="opacity" values="0.3;1;0.3" dur="2s" repeatCount="indefinite"/>
  </circle>
</svg>

<br/><br/>

## <img src="https://raw.githubusercontent.com/microsoft/fluentui-emoji/main/assets/Rocket/3D/rocket_3d.png" width="42" height="42" alt="🚀" /> <span style="color: #f093fb;">About Me</span>

<br/>

<!-- About me card with 3D animated gradient border -->
<svg width="740" height="260" viewBox="0 0 740 260" fill="none" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="about3DBorder" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#00d2ff"/>
      <stop offset="25%" stop-color="#a18cd1"/>
      <stop offset="50%" stop-color="#f5576c"/>
      <stop offset="75%" stop-color="#f6d365"/>
      <stop offset="100%" stop-color="#43e97b">
        <animate attributeName="offset" values="1;0.75;1" dur="8s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
    <linearGradient id="about3DBg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0a0a1a"/>
      <stop offset="100%" stop-color="#10101f"/>
    </linearGradient>
    <filter id="aboutShadow"><feGaussianBlur stdDeviation="3"/></filter>
  </defs>
  <rect x="1" y="1" width="738" height="258" rx="20" fill="url(#about3DBg)" stroke="url(#about3DBorder)" stroke-width="2"/>

  <text x="30" y="42" fill="#c0c0d0" font-family="system-ui,-apple-system,sans-serif" font-size="14">I am a passionate Full-Stack Developer dedicated to building</text>
  <text x="30" y="66" fill="#c0c0d0" font-family="system-ui,-apple-system,sans-serif" font-size="14">seamless digital experiences. With a strong analytical foundation from</text>
  <text x="30" y="90" fill="#c0c0d0" font-family="system-ui,-apple-system,sans-serif" font-size="14">my engineering background, I love breaking down complex problems into</text>
  <text x="30" y="114" fill="#c0c0d0" font-family="system-ui,-apple-system,sans-serif" font-size="14">clean, scalable code. Whether it's crafting intuitive user interfaces</text>
  <text x="30" y="138" fill="#c0c0d0" font-family="system-ui,-apple-system,sans-serif" font-size="14">or designing robust APIs, I thrive on bringing ideas to life across</text>
  <text x="30" y="162" fill="#c0c0d0" font-family="system-ui,-apple-system,sans-serif" font-size="14">the entire tech stack.</text>

  <line x1="30" y1="186" x2="710" y2="186" stroke="#333" stroke-width="0.6"/>

  <text x="30" y="210" fill="#8888aa" font-family="system-ui,-apple-system,sans-serif" font-size="13">🔭  Building: 3D Portfolio (React Three Fiber)</text>
  <text x="30" y="232" fill="#8888aa" font-family="system-ui,-apple-system,sans-serif" font-size="13">🌱  Exploring: System Design &amp; Cloud Architecture</text>
  <text x="395" y="210" fill="#8888aa" font-family="system-ui,-apple-system,sans-serif" font-size="13">💬  Ask me about: React, Node.js, MongoDB</text>
  <text x="395" y="232" fill="#8888aa" font-family="system-ui,-apple-system,sans-serif" font-size="13">⚡  Fun fact: I debug with console.log &amp; optimism</text>

  <!-- 3D corner orbs -->
  <circle cx="715" cy="22" r="3.5" fill="#00d2ff">
    <animate attributeName="opacity" values="1;0.2;1" dur="2s" repeatCount="indefinite"/>
    <animate attributeName="r" values="3.5;5;3.5" dur="2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="22" cy="238" r="3.5" fill="#f5576c">
    <animate attributeName="opacity" values="0.2;1;0.2" dur="2.5s" repeatCount="indefinite"/>
    <animate attributeName="r" values="3.5;5;3.5" dur="2.5s" repeatCount="indefinite"/>
  </circle>
</svg>

</div>

<br/>

<!-- ════════════════════ CURRENTLY LEARNING (3D Enhanced) ════════════════════ -->

<div align="center">

## <img src="https://raw.githubusercontent.com/microsoft/fluentui-emoji/main/assets/Books/3D/books_3d.png" width="42" height="42" alt="📚" /> <span style="color: #43e97b;">Currently Learning</span>

<br/>

<!-- 3D Now section with depth-shaded progress bars -->
<svg width="680" height="280" viewBox="0 0 680 280" fill="none" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="now3DBorder" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#43e97b"/>
      <stop offset="50%" stop-color="#00d2ff"/>
      <stop offset="100%" stop-color="#a18cd1"/>
    </linearGradient>
    <linearGradient id="now3DBg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0a0a1a"/>
      <stop offset="100%" stop-color="#0a2015"/>
    </linearGradient>
    <!-- 3D-looking progress bar gradients -->
    <linearGradient id="bar1" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#1a8a3f"/>
      <stop offset="50%" stop-color="#43e97b"/>
      <stop offset="100%" stop-color="#7fffb0"/>
    </linearGradient>
    <linearGradient id="bar2" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#003a4a"/>
      <stop offset="50%" stop-color="#00d2ff"/>
      <stop offset="100%" stop-color="#7af0ff"/>
    </linearGradient>
    <linearGradient id="bar3" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#7a0c1f"/>
      <stop offset="50%" stop-color="#f5576c"/>
      <stop offset="100%" stop-color="#ff9aab"/>
    </linearGradient>
    <!-- Track gradient -->
    <linearGradient id="trackBg" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" stop-color="#1a1a2e"/>
      <stop offset="50%" stop-color="#0a0a1a"/>
      <stop offset="100%" stop-color="#1a1a2e"/>
    </linearGradient>
    <filter id="nowShadow"><feGaussianBlur stdDeviation="3"/></filter>
  </defs>

  <rect x="1" y="1" width="678" height="278" rx="20" fill="url(#now3DBg)" stroke="url(#now3DBorder)" stroke-width="2"/>

  <!-- Live indicator header -->
  <circle cx="30" cy="28" r="6" fill="#43e97b">
    <animate attributeName="opacity" values="1;0.3;1" dur="1.5s" repeatCount="indefinite"/>
    <animate attributeName="r" values="6;8;6" dur="1.5s" repeatCount="indefinite"/>
  </circle>
  <text x="44" y="33" fill="#43e97b" font-family="system-ui,-apple-system,sans-serif" font-size="14" font-weight="700">/ NOW — Updated Weekly</text>

  <!-- Live pulsing dot (right side) -->
  <circle cx="650" cy="28" r="4" fill="#f5576c">
    <animate attributeName="r" values="4;7;4" dur="1.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="1;0.4;1" dur="1.5s" repeatCount="indefinite"/>
  </circle>
  <text x="640" y="33" fill="#f5576c" font-family="system-ui,sans-serif" font-size="11" font-weight="600" text-anchor="end">LIVE</text>

  <!-- Learning item 1: System Design -->
  <text x="30" y="74" fill="#e0e0f0" font-family="system-ui,-apple-system,sans-serif" font-size="13" font-weight="600">🏗️  System Design &amp; Scalability</text>
  <rect x="30" y="84" width="620" height="14" rx="7" fill="url(#trackBg)" stroke="#333" stroke-width="0.5"/>
  <rect x="30" y="84" width="434" height="14" rx="7" fill="url(#bar1)">
    <animate attributeName="width" values="0;434;434" dur="2s" fill="freeze"/>
    <animate attributeName="opacity" values="0.7;1;0.7" dur="2s" repeatCount="indefinite"/>
  </rect>
  <!-- Shimmering highlight -->
  <rect x="35" y="86" width="425" height="3" rx="1.5" fill="#fff" opacity="0.4">
    <animate attributeName="opacity" values="0.2;0.6;0.2" dur="2s" repeatCount="indefinite"/>
  </rect>
  <text x="650" y="94" fill="#43e97b" font-family="system-ui,sans-serif" font-size="11" font-weight="700" text-anchor="end">70%</text>

  <!-- Learning item 2: Cloud Architecture -->
  <text x="30" y="124" fill="#e0e0f0" font-family="system-ui,-apple-system,sans-serif" font-size="13" font-weight="600">☁️  AWS Cloud Architecture</text>
  <rect x="30" y="134" width="620" height="14" rx="7" fill="url(#trackBg)" stroke="#333" stroke-width="0.5"/>
  <rect x="30" y="134" width="372" height="14" rx="7" fill="url(#bar2)">
    <animate attributeName="width" values="0;372;372" dur="2.2s" fill="freeze"/>
    <animate attributeName="opacity" values="0.7;1;0.7" dur="1.8s" repeatCount="indefinite"/>
  </rect>
  <rect x="35" y="136" width="363" height="3" rx="1.5" fill="#fff" opacity="0.4">
    <animate attributeName="opacity" values="0.2;0.6;0.2" dur="1.8s" repeatCount="indefinite"/>
  </rect>
  <text x="650" y="144" fill="#00d2ff" font-family="system-ui,sans-serif" font-size="11" font-weight="700" text-anchor="end">60%</text>

  <!-- Learning item 3: Three.js / 3D Web -->
  <text x="30" y="174" fill="#e0e0f0" font-family="system-ui,-apple-system,sans-serif" font-size="13" font-weight="600">🎨  Three.js &amp; React Three Fiber</text>
  <rect x="30" y="184" width="620" height="14" rx="7" fill="url(#trackBg)" stroke="#333" stroke-width="0.5"/>
  <rect x="30" y="184" width="465" height="14" rx="7" fill="url(#bar3)">
    <animate attributeName="width" values="0;465;465" dur="2.4s" fill="freeze"/>
    <animate attributeName="opacity" values="0.7;1;0.7" dur="2.2s" repeatCount="indefinite"/>
  </rect>
  <rect x="35" y="186" width="456" height="3" rx="1.5" fill="#fff" opacity="0.4">
    <animate attributeName="opacity" values="0.2;0.6;0.2" dur="2.2s" repeatCount="indefinite"/>
  </rect>
  <text x="650" y="194" fill="#f5576c" font-family="system-ui,sans-serif" font-size="11" font-weight="700" text-anchor="end">75%</text>

  <!-- Next up line -->
  <line x1="30" y1="222" x2="650" y2="222" stroke="#333" stroke-width="0.5" stroke-dasharray="2 3"/>
  <text x="30" y="246" fill="#8888aa" font-family="system-ui,-apple-system,sans-serif" font-size="12" font-style="italic">🎯  Next up: Kubernetes · GraphQL Subscriptions · WebRTC · WebGL Shaders · Rust</text>

  <!-- 3D floating mini-cube decoration -->
  <g transform="translate(615, 240)">
    <animateTransform attributeName="transform" type="translate" values="615,240; 615,232; 615,240" dur="3s" repeatCount="indefinite" additive="sum"/>
    <polygon points="12,0 24,6 12,12 0,6" fill="#43e97b" opacity="0.8"/>
    <polygon points="0,6 12,12 12,24 0,18" fill="#1a8a3f" opacity="0.8"/>
    <polygon points="24,6 12,12 12,24 24,18" fill="#0c4a1f" opacity="0.8"/>
  </g>
</svg>

</div>

<br/>

<!-- ════════════════════ 3D FLOATING SHAPES DIVIDER ════════════════════ -->

<div align="center">

<!-- 3D floating geometric shapes scene -->
<svg viewBox="0 0 800 80" width="100%" height="80" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="shapeA1" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#00d2ff" stop-opacity="0.9"/>
      <stop offset="100%" stop-color="#003a4a" stop-opacity="0.9"/>
    </linearGradient>
    <linearGradient id="shapeA2" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#f5576c" stop-opacity="0.9"/>
      <stop offset="100%" stop-color="#7a0c1f" stop-opacity="0.9"/>
    </linearGradient>
    <linearGradient id="shapeA3" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#43e97b" stop-opacity="0.9"/>
      <stop offset="100%" stop-color="#0c4a1f" stop-opacity="0.9"/>
    </linearGradient>
    <linearGradient id="shapeA4" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#f6d365" stop-opacity="0.9"/>
      <stop offset="100%" stop-color="#7a5a0c" stop-opacity="0.9"/>
    </linearGradient>
    <linearGradient id="shapeA5" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#a18cd1" stop-opacity="0.9"/>
      <stop offset="100%" stop-color="#3a1c6a" stop-opacity="0.9"/>
    </linearGradient>
  </defs>

  <!-- Floating 3D cube 1 -->
  <g transform="translate(80, 25)">
    <animateTransform attributeName="transform" type="translate" values="80,25; 80,15; 80,25" dur="3s" repeatCount="indefinite"/>
    <g transform="rotate(15)">
      <polygon points="20,0 40,10 20,20 0,10" fill="url(#shapeA1)" opacity="0.9"/>
      <polygon points="0,10 20,20 20,40 0,30" fill="#0080a8" opacity="0.9"/>
      <polygon points="40,10 20,20 20,40 40,30" fill="#003a4a" opacity="0.9"/>
    </g>
  </g>

  <!-- Floating 3D sphere 1 -->
  <circle cx="180" cy="40" r="14" fill="url(#shapeA2)">
    <animate attributeName="cy" values="40;30;40" dur="2.5s" repeatCount="indefinite"/>
  </circle>
  <ellipse cx="176" cy="36" rx="4" ry="2.5" fill="#fff" opacity="0.6"/>

  <!-- Floating pyramid -->
  <g transform="translate(280, 25)">
    <animateTransform attributeName="transform" type="translate" values="280,25; 280,18; 280,25" dur="3.5s" repeatCount="indefinite"/>
    <polygon points="20,0 40,40 0,40" fill="url(#shapeA3)" opacity="0.9"/>
    <polygon points="20,0 0,40 20,40" fill="#0c4a1f" opacity="0.9"/>
  </g>

  <!-- Floating 3D cube 2 (rotating) -->
  <g transform="translate(390, 25)">
    <animateTransform attributeName="transform" type="translate" values="390,25; 390,15; 390,25" dur="3s" repeatCount="indefinite"/>
    <g>
      <animateTransform attributeName="transform" type="rotate" values="0 20 20; 360 20 20" dur="12s" repeatCount="indefinite"/>
      <polygon points="20,0 40,10 20,20 0,10" fill="url(#shapeA4)" opacity="0.9"/>
      <polygon points="0,10 20,20 20,40 0,30" fill="#7a5a0c" opacity="0.9"/>
      <polygon points="40,10 20,20 20,40 40,30" fill="#3a2c05" opacity="0.9"/>
    </g>
  </g>

  <!-- Floating diamond -->
  <g transform="translate(490, 25)">
    <animateTransform attributeName="transform" type="translate" values="490,25; 490,17; 490,25" dur="2.8s" repeatCount="indefinite"/>
    <polygon points="20,0 35,20 20,40 5,20" fill="url(#shapeA5)" opacity="0.9"/>
    <polygon points="20,0 35,20 20,20" fill="#dabbff" opacity="0.7"/>
    <polygon points="20,0 5,20 20,20" fill="#a18cd1" opacity="0.9"/>
  </g>

  <!-- Floating 3D sphere 2 -->
  <circle cx="600" cy="40" r="11" fill="url(#shapeA1)">
    <animate attributeName="cy" values="40;32;40" dur="2.2s" repeatCount="indefinite"/>
  </circle>
  <ellipse cx="597" cy="37" rx="3" ry="2" fill="#fff" opacity="0.6"/>

  <!-- Floating pyramid 2 -->
  <g transform="translate(680, 25)">
    <animateTransform attributeName="transform" type="translate" values="680,25; 680,18; 680,25" dur="3.2s" repeatCount="indefinite"/>
    <polygon points="20,0 40,40 0,40" fill="url(#shapeA2)" opacity="0.9"/>
    <polygon points="20,0 0,40 20,40" fill="#7a0c1f" opacity="0.9"/>
  </g>

  <!-- Connecting lines (subtle network effect) -->
  <line x1="120" y1="45" x2="180" y2="40" stroke="#333" stroke-width="0.3" opacity="0.5"/>
  <line x1="220" y1="40" x2="300" y2="45" stroke="#333" stroke-width="0.3" opacity="0.5"/>
  <line x1="340" y1="45" x2="410" y2="45" stroke="#333" stroke-width="0.3" opacity="0.5"/>
  <line x1="450" y1="45" x2="510" y2="45" stroke="#333" stroke-width="0.3" opacity="0.5"/>
  <line x1="550" y1="45" x2="600" y2="40" stroke="#333" stroke-width="0.3" opacity="0.5"/>
  <line x1="620" y1="40" x2="700" y2="45" stroke="#333" stroke-width="0.3" opacity="0.5"/>
</svg>

</div>

<br/>

<!-- ════════════════════ TECH STACK ════════════════════ -->

<div align="center">

## <img src="https://raw.githubusercontent.com/microsoft/fluentui-emoji/main/assets/Hammer%20and%20wrench/Color/hammer_and_wrench_color.svg" width="42" height="42" alt="🛠️" /> <span style="color: #43e97b;">Tech Stack &amp; Ecosystem</span>

<br/>

<table>
  <tr>
    <td width="50%" style="border: 1px solid #00d2ff; border-radius: 14px; padding: 18px 22px; background: linear-gradient(135deg, #08081a 0%, #0a1525 100%); box-shadow: 0 4px 18px rgba(0,210,255,0.25);">
      <b><span style="color: #00d2ff; font-size: 1.05em;">🖥️  Frontend</span></b>
      <br/><br/>
      <code style="color: #00d2ff;">JavaScript (ES6+)</code> · <code style="color: #43e97b;">TypeScript</code> · <code style="color: #f5576c;">React.js</code> · <code style="color: #f6d365;">Next.js</code> · <code style="color: #a18cd1;">HTML5/CSS3</code> · <code style="color: #00d2ff;">Tailwind CSS</code> · <code style="color: #43e97b;">Redux</code>
    </td>
    <td width="50%" style="border: 1px solid #43e97b; border-radius: 14px; padding: 18px 22px; background: linear-gradient(135deg, #08081a 0%, #0a251a 100%); box-shadow: 0 4px 18px rgba(67,233,123,0.25);">
      <b><span style="color: #43e97b; font-size: 1.05em;">⚙️  Backend &amp; APIs</span></b>
      <br/><br/>
      <code style="color: #43e97b;">Node.js</code> · <code style="color: #00d2ff;">Express.js</code> · <code style="color: #f6d365;">RESTful APIs</code> · <code style="color: #f5576c;">GraphQL</code> · <code style="color: #a18cd1;">Python</code> · <code style="color: #43e97b;">Flask</code>
    </td>
  </tr>
  <tr>
    <td width="50%" style="border: 1px solid #f6d365; border-radius: 14px; padding: 18px 22px; background: linear-gradient(135deg, #08081a 0%, #251a0a 100%); box-shadow: 0 4px 18px rgba(246,211,101,0.2);">
      <b><span style="color: #f6d365; font-size: 1.05em;">🗄️  Databases &amp; Caching</span></b>
      <br/><br/>
      <code style="color: #f6d365;">PostgreSQL</code> · <code style="color: #43e97b;">MongoDB</code> · <code style="color: #00d2ff;">MySQL</code> · <code style="color: #f5576c;">Redis</code> · <code style="color: #a18cd1;">Prisma ORM</code>
    </td>
    <td width="50%" style="border: 1px solid #f5576c; border-radius: 14px; padding: 18px 22px; background: linear-gradient(135deg, #08081a 0%, #250a15 100%); box-shadow: 0 4px 18px rgba(245,87,108,0.25);">
      <b><span style="color: #f5576c; font-size: 1.05em;">☁️  DevOps &amp; Tools</span></b>
      <br/><br/>
      <code style="color: #f5576c;">Git &amp; GitHub</code> · <code style="color: #00d2ff;">Docker</code> · <code style="color: #f6d365;">AWS (S3/EC2)</code> · <code style="color: #43e97b;">Vercel</code> · <code style="color: #a18cd1;">Postman</code> · <code style="color: #00d2ff;">Linux</code>
    </td>
  </tr>
</table>

</div>

<br/>

<!-- ════════════════════ FEATURED PROJECTS (3D Card Style) ════════════════════ -->

<div align="center">

## <img src="https://raw.githubusercontent.com/microsoft/fluentui-emoji/main/assets/Pushpin/3D/pushpin_3d.png" width="42" height="42" alt="📌" /> <span style="color: #f5576c;">Featured Projects</span>

<br/>

<table>
  <tr>
    <!-- Project 1: Portfolio 3D -->
    <td width="50%" style="border: 1px solid #a18cd1; border-radius: 14px; padding: 20px 22px; background: linear-gradient(135deg, #08081a 0%, #100a25 100%); box-shadow: 0 6px 22px rgba(0,210,255,0.3);">
      <b><span style="color: #00d2ff; font-size: 1.15em;">🎨  Portfolio (3D)</span></b>
      <br/>
      <sub><span style="color: #777788;">React 18 · Three.js · React Three Fiber · Vite</span></sub>
      <br/><br/>
      <span style="color: #9999aa;">Immersive 3D portfolio experience with interactive scenes and smooth animations.</span>
      <br/><br/>
      <a href="https://github.com/kashyap-p/portfolioNEW"><img src="https://img.shields.io/badge/View_Repo-08081a?style=flat-square&logo=github&logoColor=00d2ff" alt="Repo" /></a>
      <img src="https://img.shields.io/badge/React_18-61DAFB?style=flat-square&logo=react&logoColor=white" alt="React" />
      <img src="https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=three.js&logoColor=white" alt="Three.js" />
    </td>
    <!-- Project 2: Tech News -->
    <td width="50%" style="border: 1px solid #a18cd1; border-radius: 14px; padding: 20px 22px; background: linear-gradient(135deg, #08081a 0%, #102510 100%); box-shadow: 0 6px 22px rgba(67,233,123,0.3);">
      <b><span style="color: #43e97b; font-size: 1.15em;">📰  Tech News</span></b>
      <br/>
      <sub><span style="color: #777788;">HTML · CSS · JavaScript</span></sub>
      <br/><br/>
      <span style="color: #9999aa;">Static tech news demo site with curated articles, responsive layout, and dynamic content filtering.</span>
      <br/><br/>
      <a href="https://github.com/kashyap-p/tech-news"><img src="https://img.shields.io/badge/View_Repo-08081a?style=flat-square&logo=github&logoColor=43e97b" alt="Repo" /></a>
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JS" />
      <img src="https://img.shields.io/badge/Responsive-Yes-success?style=flat-square" alt="Responsive" />
    </td>
  </tr>
  <tr>
    <!-- Project 3: Todo App -->
    <td width="50%" style="border: 1px solid #a18cd1; border-radius: 14px; padding: 20px 22px; background: linear-gradient(135deg, #08081a 0%, #25200a 100%); box-shadow: 0 6px 22px rgba(246,211,101,0.25);">
      <b><span style="color: #f6d365; font-size: 1.15em;">✅  Todo App</span></b>
      <br/>
      <sub><span style="color: #777788;">HTML · CSS · JavaScript · localStorage</span></sub>
      <br/><br/>
      <span style="color: #9999aa;">Client-side todo list with add/delete/filter tasks, localStorage persistence, and responsive UI.</span>
      <br/><br/>
      <a href="https://github.com/kashyap-p/todo-app"><img src="https://img.shields.io/badge/View_Repo-08081a?style=flat-square&logo=github&logoColor=f6d365" alt="Repo" /></a>
      <img src="https://img.shields.io/badge/vanilla_JS-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JS" />
      <img src="https://img.shields.io/badge/Persistence-localStorage-orange?style=flat-square" alt="localStorage" />
    </td>
    <!-- Project 4: Weather Tracker -->
    <td width="50%" style="border: 1px solid #43e97b; border-radius: 14px; padding: 20px 22px; background: linear-gradient(135deg, #08081a 0%, #0a201a 100%); box-shadow: 0 6px 22px rgba(245,87,108,0.25);">
      <b><span style="color: #43e97b; font-size: 1.15em;">🌤️  Weather Tracker</span></b>
      <br/>
      <sub><span style="color: #777788;">React · Vite · JavaScript</span></sub>
      <br/><br/>
      <span style="color: #9999aa;">Live weather dashboard with glassmorphism UI, powered by Open-Meteo API — no API key required.</span>
      <br/><br/>
      <a href="https://github.com/kashyap-p/weather-tracker"><img src="https://img.shields.io/badge/View_Repo-08081a?style=flat-square&logo=github&logoColor=43e97b" alt="Repo" /></a>
      <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React" />
      <img src="https://img.shields.io/badge/API-Open--Meteo-00D2FF?style=flat-square" alt="API" />
    </td>
  </tr>
</table>

</div>

<br/>

<!-- ════════════════════ 3D ANIMATED TERMINAL ════════════════════ -->

<div align="center">

## <img src="https://raw.githubusercontent.com/microsoft/fluentui-emoji/main/assets/Laptop/3D/laptop_3d.png" width="42" height="42" alt="💻" /> <span style="color: #00d2ff;">Quick Stats Terminal</span>

<br/>

<!-- Animated terminal window — GitHub-safe (no filters, single-line text, solid fills) -->
<svg width="680" height="180" viewBox="0 0 680 180" xmlns="http://www.w3.org/2000/svg">
  <rect x="1" y="1" width="678" height="178" rx="10" fill="#0a0a1a" stroke="#00d2ff" stroke-width="1.5"/>
  <rect x="1" y="1" width="678" height="28" rx="10" fill="#15152a"/>
  <rect x="1" y="20" width="678" height="9" fill="#15152a"/>
  <circle cx="20" cy="15" r="5" fill="#ff5f56"><animate attributeName="opacity" values="1;0.6;1" dur="3s" repeatCount="indefinite"/></circle>
  <circle cx="38" cy="15" r="5" fill="#ffbd2e"><animate attributeName="opacity" values="1;0.6;1" dur="3s" begin="0.5s" repeatCount="indefinite"/></circle>
  <circle cx="56" cy="15" r="5" fill="#27c93f"><animate attributeName="opacity" values="1;0.6;1" dur="3s" begin="1s" repeatCount="indefinite"/></circle>
  <text x="340" y="19" fill="#8888aa" font-family="monospace" font-size="11" text-anchor="middle">~/kashyap-p — zsh</text>
  <text x="20" y="55" fill="#43e97b" font-family="monospace" font-size="12" font-weight="600">$</text>
  <text x="32" y="55" fill="#e0e0f0" font-family="monospace" font-size="12" font-weight="600">whoami</text>
  <text x="40" y="73" fill="#c0c0d0" font-family="monospace" font-size="11">kashyap-p · full-stack developer · open-source contributor</text>
  <text x="20" y="98" fill="#43e97b" font-family="monospace" font-size="12" font-weight="600">$</text>
  <text x="32" y="98" fill="#e0e0f0" font-family="monospace" font-size="12" font-weight="600">cat skills.json</text>
  <text x="40" y="116" fill="#00d2ff" font-family="monospace" font-size="11">{ "frontend": ["React","Next.js","TypeScript","Tailwind"],</text>
  <text x="40" y="131" fill="#00d2ff" font-family="monospace" font-size="11">  "backend":  ["Node.js","Express","GraphQL","Python"],</text>
  <text x="40" y="146" fill="#00d2ff" font-family="monospace" font-size="11">  "devops":   ["Docker","AWS","Vercel","Linux"] }</text>
  <text x="20" y="166" fill="#43e97b" font-family="monospace" font-size="12" font-weight="600">$</text>
  <rect x="32" y="156" width="8" height="14" fill="#43e97b"><animate attributeName="opacity" values="1;0;1" dur="1s" repeatCount="indefinite"/></rect>
</svg>

</div>

<br/>

<!-- ════════════════════ GITHUB ACTIVITY ════════════════════ -->

<div align="center">

## <img src="https://raw.githubusercontent.com/microsoft/fluentui-emoji/main/assets/Bar%20chart/Color/bar_chart_color.svg" width="42" height="42" alt="📊" /> <span style="color: #f6d365;">GitHub Activity &amp; Insights</span>

<br/>

<!-- GitHub Stats + Top Languages — using a community-maintained mirror since the official vercel deployment is paused -->
<table>
  <tr>
    <td style="padding: 8px;">
      <img src="https://github-readme-stats-one-bice.vercel.app/api?username=kashyap-p&show_icons=true&theme=dark&hide_border=true&count_private=true&bg_color=08081a&title_color=00d2ff&icon_color=f5576c&text_color=ffffff" alt="GitHub Stats" onerror="this.style.display='none'" />
    </td>
    <td style="padding: 8px;">
      <img src="https://github-readme-stats-one-bice.vercel.app/api/top-langs/?username=kashyap-p&layout=compact&theme=dark&hide_border=true&bg_color=08081a&title_color=43e97b&text_color=ffffff" alt="Top Languages" onerror="this.style.display='none'" />
    </td>
  </tr>
</table>

<!-- Profile Summary Cards as a reliable fallback for trophy showcase -->
<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=kashyap-p&theme=2077&count_private=true" alt="Profile Summary" onerror="this.style.display='none'" />

<br/>

<img src="https://streak-stats.demolab.com/?user=kashyap-p&theme=dark&hide_border=true&background=08081a&stroke=00d2ff&ring=f5576c&fire=f6d365&currStreakLabel=43e97b" alt="GitHub Streak" onerror="this.style.display='none'" />

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=kashyap-p&bg_color=08081a&color=00d2ff&line=43e97b&point=f5576c&area=true&hide_border=true&radius=8&title_color=f6d365" width="95%" alt="Contribution Graph" onerror="this.style.display='none'" />

<br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/kashyap-p/kashyap-p/master/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/kashyap-p/kashyap-p/master/github-contribution-grid-snake.svg" />
  <img src="https://raw.githubusercontent.com/kashyap-p/kashyap-p/master/github-contribution-grid-snake.svg" alt="Contribution Snake" width="95%" onerror="this.style.display='none'" />
</picture>

<br/>

<!-- 3D-style rotating dev quote with gradient border -->
<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark" width="80%" alt="Dev Quote" onerror="this.style.display='none'" />

<br/>

<p>
  <img src="https://img.shields.io/github/last-commit/kashyap-p/kashyap-p?label=Last%20Profile%20Update&color=f5576c&style=for-the-badge&labelColor=08081a" alt="Last Commit" />
  <img src="https://img.shields.io/github/created-at/kashyap-p/kashyap-p?label=Profile%20Since&color=43e97b&style=for-the-badge&labelColor=08081a" alt="Profile Created" />
</p>

</div>

<br/>

<!-- ════════════════════ ANIMATED 3D WAVE DIVIDER ════════════════════ -->

<svg viewBox="0 0 800 50" width="100%" height="50" style="display: block; margin: 10px auto;" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="wg3d" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#00d2ff" stop-opacity="0.15"/>
      <stop offset="25%" stop-color="#a18cd1" stop-opacity="0.22"/>
      <stop offset="50%" stop-color="#f5576c" stop-opacity="0.18"/>
      <stop offset="75%" stop-color="#f6d365" stop-opacity="0.22"/>
      <stop offset="100%" stop-color="#43e97b" stop-opacity="0.15"/>
    </linearGradient>
    <linearGradient id="wg3dTop" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" stop-color="#fff" stop-opacity="0.3"/>
      <stop offset="100%" stop-color="#fff" stop-opacity="0"/>
    </linearGradient>
  </defs>
  <path d="M0,25 Q50,7 100,25 T200,25 T300,25 T400,25 T500,25 T600,25 T700,25 T800,25 L800,50 L0,50 Z" fill="url(#wg3d)">
    <animate attributeName="d" dur="7s" repeatCount="indefinite" values="
      M0,25 Q50,7 100,25 T200,25 T300,25 T400,25 T500,25 T600,25 T700,25 T800,25 L800,50 L0,50 Z;
      M0,30 Q50,45 100,30 T200,30 T300,30 T400,30 T500,30 T600,30 T700,30 T800,30 L800,50 L0,50 Z;
      M0,25 Q50,7 100,25 T200,25 T300,25 T400,25 T500,25 T600,25 T700,25 T800,25 L800,50 L0,50 Z
    "/>
  </path>
  <!-- Highlight overlay -->
  <path d="M0,25 Q50,7 100,25 T200,25 T300,25 T400,25 T500,25 T600,25 T700,25 T800,25" fill="none" stroke="url(#wg3dTop)" stroke-width="1.5">
    <animate attributeName="d" dur="7s" repeatCount="indefinite" values="
      M0,25 Q50,7 100,25 T200,25 T300,25 T400,25 T500,25 T600,25 T700,25 T800,25;
      M0,30 Q50,45 100,30 T200,30 T300,30 T400,30 T500,30 T600,30 T700,30 T800,30;
      M0,25 Q50,7 100,25 T200,25 T300,25 T400,25 T500,25 T600,25 T700,25 T800,25
    "/>
  </path>
</svg>

<!-- ════════════════════ LET'S CONNECT ════════════════════ -->

<div align="center">

## <img src="https://raw.githubusercontent.com/microsoft/fluentui-emoji/main/assets/Handshake/3D/handshake_3d.png" width="42" height="42" alt="🤝" /> <span style="color: #a18cd1;">Let's Connect!</span>

<br/>

<table>
  <tr>
    <td style="border: 1px solid #a18cd1; border-radius: 16px; padding: 22px 32px; background: linear-gradient(135deg, #08081a 0%, #15101f 100%); box-shadow: 0 6px 24px rgba(161,140,209,0.35);">
      <b>🔍  Looking for:</b> Full-Time opportunities, freelance projects, or open-source collaborations.
      <br/><br/>
      <b>📖  Core Philosophy:</b> &ldquo;Write code that is easy to read, easier to test, and built to scale.&rdquo;
      <br/><br/>
      <b>⚡  Response Time:</b> Usually within 24 hours on weekdays.
    </td>
  </tr>
</table>

<br/>

<!-- Animated 3D connect buttons -->
<p>
  <a href="https://www.linkedin.com/in/kashyap-p">
    <img src="https://img.shields.io/badge/Connect_on_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=08081a" alt="LinkedIn" />
  </a>
  <a href="https://github.com/kashyap-p">
    <img src="https://img.shields.io/badge/Follow_on_GitHub-100000?style=for-the-badge&logo=github&logoColor=white&labelColor=08081a" alt="GitHub" />
  </a>
  <a href="mailto:kashyappatel0702@gmail.com">
    <img src="https://img.shields.io/badge/Send_an_Email-D14836?style=for-the-badge&logo=gmail&logoColor=white&labelColor=08081a" alt="Email" />
  </a>
</p>

<br/>

<!-- Animated 3D star prompt with rotating cube -->
<svg width="560" height="68" viewBox="0 0 560 68" fill="none" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="starBg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#08081a"/>
      <stop offset="100%" stop-color="#15101f"/>
    </linearGradient>
    <linearGradient id="starBorder" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#00d2ff"/>
      <stop offset="50%" stop-color="#43e97b"/>
      <stop offset="100%" stop-color="#f5576c"/>
      <animate attributeName="x1" values="0%;100%;0%" dur="5s" repeatCount="indefinite"/>
      <animate attributeName="x2" values="100%;200%;100%" dur="5s" repeatCount="indefinite"/>
    </linearGradient>
    <filter id="starGlowF"><feGaussianBlur stdDeviation="3"/></filter>
    <!-- Mini 3D cube gradient -->
    <linearGradient id="miniCube1" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#f6d365"/>
      <stop offset="100%" stop-color="#7a5a0c"/>
    </linearGradient>
    <linearGradient id="miniCube2" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#43e97b"/>
      <stop offset="100%" stop-color="#0c4a1f"/>
    </linearGradient>
    <linearGradient id="miniCube3" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#f5576c"/>
      <stop offset="100%" stop-color="#7a0c1f"/>
    </linearGradient>
  </defs>

  <rect x="1" y="1" width="558" height="66" rx="33" fill="url(#starBg)" stroke="url(#starBorder)" stroke-width="1.8"/>

  <!-- Left rotating mini 3D cube -->
  <g transform="translate(28, 22)">
    <g>
      <animateTransform attributeName="transform" type="rotate" values="0 12 12; 360 12 12" dur="8s" repeatCount="indefinite"/>
      <polygon points="12,0 24,6 12,12 0,6" fill="url(#miniCube1)"/>
      <polygon points="0,6 12,12 12,24 0,18" fill="url(#miniCube2)"/>
      <polygon points="24,6 12,12 12,24 24,18" fill="url(#miniCube3)"/>
    </g>
  </g>

  <!-- Right rotating mini 3D cube (reverse) -->
  <g transform="translate(520, 22)">
    <g>
      <animateTransform attributeName="transform" type="rotate" values="360 12 12; 0 12 12" dur="8s" repeatCount="indefinite"/>
      <polygon points="12,0 24,6 12,12 0,6" fill="url(#miniCube3)"/>
      <polygon points="0,6 12,12 12,24 0,18" fill="url(#miniCube1)"/>
      <polygon points="24,6 12,12 12,24 24,18" fill="url(#miniCube2)"/>
    </g>
  </g>

  <text x="280" y="40" fill="#c0c0d0" font-family="system-ui,-apple-system,sans-serif" font-size="14" font-weight="600" text-anchor="middle">
    ⭐  Drop a star on my repositories if you find my work helpful!
  </text>

  <!-- Twinkling stars inside the badge -->
  <circle cx="80" cy="20" r="1.5" fill="#f6d365">
    <animate attributeName="opacity" values="1;0.2;1" dur="1.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="480" cy="48" r="1.5" fill="#f6d365">
    <animate attributeName="opacity" values="0.2;1;0.2" dur="1.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="120" cy="48" r="1" fill="#43e97b">
    <animate attributeName="opacity" values="1;0.3;1" dur="1.8s" repeatCount="indefinite"/>
  </circle>
  <circle cx="440" cy="20" r="1" fill="#43e97b">
    <animate attributeName="opacity" values="0.3;1;0.3" dur="1.8s" repeatCount="indefinite"/>
  </circle>
</svg>

</div>

<br/>

<!-- ════════════════════ 3D PARTICLE NETWORK FOOTER ════════════════════ -->

<svg viewBox="0 0 800 60" width="100%" height="60" style="display: block;" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <radialGradient id="particleRed" cx="35%" cy="35%">
      <stop offset="0%" stop-color="#ffaaaa"/>
      <stop offset="100%" stop-color="#f5576c"/>
    </radialGradient>
    <radialGradient id="particleCyan" cx="35%" cy="35%">
      <stop offset="0%" stop-color="#aaf0ff"/>
      <stop offset="100%" stop-color="#00d2ff"/>
    </radialGradient>
    <radialGradient id="particleGreen" cx="35%" cy="35%">
      <stop offset="0%" stop-color="#aaffaa"/>
      <stop offset="100%" stop-color="#43e97b"/>
    </radialGradient>
    <radialGradient id="particleYellow" cx="35%" cy="35%">
      <stop offset="0%" stop-color="#ffeaaa"/>
      <stop offset="100%" stop-color="#f6d365"/>
    </radialGradient>
    <radialGradient id="particlePurple" cx="35%" cy="35%">
      <stop offset="0%" stop-color="#dabbff"/>
      <stop offset="100%" stop-color="#a18cd1"/>
    </radialGradient>
  </defs>

  <!-- Floating 3D particles with size pulsing -->
  <circle cx="80" cy="30" r="3" fill="url(#particleCyan)">
    <animate attributeName="cx" from="-30" to="830" dur="14s" repeatCount="indefinite"/>
    <animate attributeName="r" values="3;5;3" dur="2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="200" cy="20" r="2.5" fill="url(#particleRed)">
    <animate attributeName="cx" from="-30" to="830" dur="18s" repeatCount="indefinite"/>
    <animate attributeName="r" values="2.5;4;2.5" dur="2.3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="350" cy="40" r="3" fill="url(#particleGreen)">
    <animate attributeName="cx" from="-30" to="830" dur="16s" repeatCount="indefinite"/>
    <animate attributeName="r" values="3;5;3" dur="2.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="500" cy="15" r="2" fill="url(#particleYellow)">
    <animate attributeName="cx" from="-30" to="830" dur="20s" repeatCount="indefinite"/>
  </circle>
  <circle cx="650" cy="35" r="3" fill="url(#particlePurple)">
    <animate attributeName="cx" from="-30" to="830" dur="15s" repeatCount="indefinite"/>
    <animate attributeName="r" values="3;5;3" dur="1.8s" repeatCount="indefinite"/>
  </circle>
  <circle cx="280" cy="45" r="2" fill="url(#particleCyan)">
    <animate attributeName="cx" from="-30" to="830" dur="22s" repeatCount="indefinite"/>
  </circle>
  <circle cx="600" cy="50" r="2.5" fill="url(#particleRed)">
    <animate attributeName="cx" from="-30" to="830" dur="17s" repeatCount="indefinite"/>
    <animate attributeName="r" values="2.5;4;2.5" dur="2.1s" repeatCount="indefinite"/>
  </circle>

  <!-- Faint network lines -->
  <line x1="80" y1="30" x2="200" y2="20" stroke="#333" stroke-width="0.3" opacity="0.4"/>
  <line x1="200" y1="20" x2="350" y2="40" stroke="#333" stroke-width="0.3" opacity="0.4"/>
  <line x1="350" y1="40" x2="500" y2="15" stroke="#333" stroke-width="0.3" opacity="0.4"/>
  <line x1="500" y1="15" x2="650" y2="35" stroke="#333" stroke-width="0.3" opacity="0.4"/>
</svg>

<!-- ────────── 3D CAPSULE FOOTER BANNER ────────── -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:43e97b,25:f6d365,50:f5576c,75:a18cd1,100:00d2ff&height=160&section=footer&fontSize=0&stroke=00d2ff&strokeWidth=2" width="100%" alt="3D Footer Banner" />

<!-- ════════════════════════════════════════════════════════════════════ -->
<!--  README v3 · designed & maintained by Kashyap Patel                 -->
<!--  Last redesigned: July 2026 · 3D & animations enhanced              -->
<!-- ════════════════════════════════════════════════════════════════════ -->
