<div align="center">

<!-- ANIMATED HEADER BANNER -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d0221,30:0a0a2e,60:1a0533,100:0d0221&height=200&section=header&text=PURNANSH%20PATEL&fontSize=55&fontColor=00f5ff&animation=fadeIn&fontAlignY=38&desc=Aspiring%20Web%20Developer%20%7C%20Problem%20Solver&descAlignY=60&descSize=18&descColor=bd00ff" />

<!-- TYPING ANIMATION -->
<a href="https://github.com/purnanshpatel">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=22&duration=3000&pause=1000&color=00F5FF&center=true&vCenter=true&multiline=false&repeat=true&width=600&height=50&lines=Hello+World!+I'm+Purnansh+Patel+%F0%9F%91%8B;Building+the+Web%2C+One+Line+at+a+Time+%F0%9F%9A%80;Code.+Create.+Conquer.+%E2%9A%A1;Turning+Coffee+into+Code+%E2%98%95%F0%9F%92%BB" alt="Typing SVG" />
</a>

<br/>

<!-- PROFILE VIEWS + FOLLOWERS + STARS BADGES -->
<p>
  <img src="https://komarev.com/ghpvc/?username=purnanshpatel&label=Profile+Views&color=00f5ff&style=for-the-badge" alt="Profile Views"/>
  &nbsp;
  <img src="https://img.shields.io/github/followers/purnanshpatel?label=Followers&style=for-the-badge&color=bd00ff&labelColor=0d0221" />
  &nbsp;
  <img src="https://img.shields.io/github/stars/purnanshpatel?label=Total+Stars&style=for-the-badge&color=00f5ff&labelColor=0d0221" />
</p>

</div>

---

<!-- ABOUT ME SECTION -->
<div align="center">

## ◈ ABOUT ME ◈

</div>

```js
const purnansh = {
  name        : "Purnansh Patel",
  role        : "Aspiring Web Developer & Problem Solver",
  location    : "India 🇮🇳",
  learning    : ["React.js", "Node.js", "DSA with C++"],
  passionate  : ["Clean Code", "Open Source", "Building Cool Things"],
  goal        : "To craft digital experiences that matter 🚀",
  funFact     : "I debug with console.log and I'm proud of it 😄",
};
```

<div align="center">

<table>
<tr>
<td>

- 🔭 Currently building **awesome web projects**
- 🌱 Learning **React, Node.js & Advanced C++**
- 💡 Love solving **challenging problems**
- 🎯 Goal: **Contribute to impactful Open Source projects**
- ⚡ Fun fact: **The best code is the one that works!**

</td>
<td>

<img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="250" alt="coding gif"/>

</td>
</tr>
</table>

</div>

---

<!-- ANIMATED TECH STACK ORBIT -->
<div align="center">

## ◈ TECH STACK ◈

<!-- Orbit Animation using SVG -->
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 500 500" width="420" height="420">
  <defs>
    <radialGradient id="bgGrad" cx="50%" cy="50%" r="50%">
      <stop offset="0%" style="stop-color:#1a0533;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#0d0221;stop-opacity:1" />
    </radialGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <filter id="glow2">
      <feGaussianBlur stdDeviation="5" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- Background -->
  <rect width="500" height="500" fill="url(#bgGrad)" rx="20"/>

  <!-- Orbit Rings -->
  <ellipse cx="250" cy="250" rx="170" ry="170" fill="none" stroke="#00f5ff" stroke-width="0.5" stroke-dasharray="4 6" opacity="0.3"/>
  <ellipse cx="250" cy="250" rx="120" ry="120" fill="none" stroke="#bd00ff" stroke-width="0.5" stroke-dasharray="3 5" opacity="0.3"/>

  <!-- Center Circle -->
  <circle cx="250" cy="250" r="55" fill="#0d0221" stroke="#00f5ff" stroke-width="2" filter="url(#glow)"/>
  <circle cx="250" cy="250" r="48" fill="none" stroke="#bd00ff" stroke-width="1" opacity="0.6"/>
  <text x="250" y="244" text-anchor="middle" fill="#00f5ff" font-size="11" font-family="monospace" font-weight="bold" filter="url(#glow)">TECH</text>
  <text x="250" y="260" text-anchor="middle" fill="#bd00ff" font-size="11" font-family="monospace" font-weight="bold" filter="url(#glow)">STACK</text>

  <!-- Outer orbit dots (decorative) -->
  <circle cx="250" cy="80" r="3" fill="#00f5ff" opacity="0.5"/>
  <circle cx="420" cy="250" r="3" fill="#bd00ff" opacity="0.5"/>
  <circle cx="250" cy="420" r="3" fill="#00f5ff" opacity="0.5"/>
  <circle cx="80" cy="250" r="3" fill="#bd00ff" opacity="0.5"/>

  <!-- JS Icon - orbit outer ring -->
  <g>
    <animateTransform attributeName="transform" type="rotate" from="0 250 250" to="360 250 250" dur="12s" repeatCount="indefinite"/>
    <circle cx="420" cy="250" r="28" fill="#f7df1e" opacity="0.95" filter="url(#glow)"/>
    <text x="420" y="246" text-anchor="middle" fill="#000" font-size="9" font-family="monospace" font-weight="bold">JS</text>
    <text x="420" y="258" text-anchor="middle" fill="#000" font-size="7" font-family="monospace">Script</text>
  </g>

  <!-- HTML Icon -->
  <g>
    <animateTransform attributeName="transform" type="rotate" from="60 250 250" to="420 250 250" dur="12s" repeatCount="indefinite"/>
    <circle cx="420" cy="250" r="28" fill="#e34f26" opacity="0.95" filter="url(#glow)"/>
    <text x="420" y="246" text-anchor="middle" fill="#fff" font-size="9" font-family="monospace" font-weight="bold">HTML</text>
    <text x="420" y="258" text-anchor="middle" fill="#fff" font-size="7" font-family="monospace">5</text>
  </g>

  <!-- CSS Icon -->
  <g>
    <animateTransform attributeName="transform" type="rotate" from="120 250 250" to="480 250 250" dur="12s" repeatCount="indefinite"/>
    <circle cx="420" cy="250" r="28" fill="#1572b6" opacity="0.95" filter="url(#glow)"/>
    <text x="420" y="246" text-anchor="middle" fill="#fff" font-size="9" font-family="monospace" font-weight="bold">CSS</text>
    <text x="420" y="258" text-anchor="middle" fill="#fff" font-size="7" font-family="monospace">3</text>
  </g>

  <!-- C++ Icon -->
  <g>
    <animateTransform attributeName="transform" type="rotate" from="180 250 250" to="540 250 250" dur="12s" repeatCount="indefinite"/>
    <circle cx="420" cy="250" r="28" fill="#00599c" opacity="0.95" filter="url(#glow)"/>
    <text x="420" y="254" text-anchor="middle" fill="#fff" font-size="10" font-family="monospace" font-weight="bold">C++</text>
  </g>

  <!-- Node.js Icon -->
  <g>
    <animateTransform attributeName="transform" type="rotate" from="240 250 250" to="600 250 250" dur="12s" repeatCount="indefinite"/>
    <circle cx="420" cy="250" r="28" fill="#339933" opacity="0.95" filter="url(#glow)"/>
    <text x="420" y="246" text-anchor="middle" fill="#fff" font-size="8" font-family="monospace" font-weight="bold">Node</text>
    <text x="420" y="258" text-anchor="middle" fill="#fff" font-size="7" font-family="monospace">.js</text>
  </g>

  <!-- Git Icon -->
  <g>
    <animateTransform attributeName="transform" type="rotate" from="300 250 250" to="660 250 250" dur="12s" repeatCount="indefinite"/>
    <circle cx="420" cy="250" r="28" fill="#f05032" opacity="0.95" filter="url(#glow)"/>
    <text x="420" y="254" text-anchor="middle" fill="#fff" font-size="10" font-family="monospace" font-weight="bold">Git</text>
  </g>

  <!-- Inner orbit: GitHub -->
  <g>
    <animateTransform attributeName="transform" type="rotate" from="0 250 250" to="-360 250 250" dur="8s" repeatCount="indefinite"/>
    <circle cx="370" cy="250" r="22" fill="#181717" stroke="#00f5ff" stroke-width="1.5" filter="url(#glow)"/>
    <text x="370" y="253" text-anchor="middle" fill="#fff" font-size="7" font-family="monospace" font-weight="bold">GitHub</text>
  </g>

  <!-- Connecting lines (decorative) -->
  <line x1="250" y1="80" x2="250" y2="195" stroke="#00f5ff" stroke-width="0.3" opacity="0.2" stroke-dasharray="3 4"/>
  <line x1="420" y1="250" x2="305" y2="250" stroke="#00f5ff" stroke-width="0.3" opacity="0.2" stroke-dasharray="3 4"/>
</svg>

</div>

---

<!-- SKILLS SECTION -->
<div align="center">

## ◈ SKILLS & TECHNOLOGIES ◈

### 🌐 Frontend
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

### ⚙️ Backend & Languages
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)

### 🛠️ Tools & Platforms
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

### 📚 Currently Learning
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

</div>

---

<!-- GITHUB STATS -->
<div align="center">

## ◈ GITHUB STATS ◈

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=purnanshpatel&show_icons=true&theme=radical&hide_border=true&bg_color=0d0221&title_color=00f5ff&icon_color=bd00ff&text_color=ffffff&border_radius=10" />
<img width="49%" src="https://github-readme-streak-stats.herokuapp.com/?user=purnanshpatel&theme=radical&hide_border=true&background=0d0221&ring=00f5ff&fire=bd00ff&currStreakLabel=00f5ff&sideLabels=ffffff&border_radius=10" />

<br/>

<img width="40%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=purnanshpatel&layout=compact&theme=radical&hide_border=true&bg_color=0d0221&title_color=00f5ff&text_color=ffffff&border_radius=10&langs_count=6" />

</div>

---

<!-- CONTRIBUTION GRAPH -->
<div align="center">

## ◈ CONTRIBUTION GRAPH ◈

<img src="https://github-readme-activity-graph.vercel.app/graph?username=purnanshpatel&bg_color=0d0221&color=00f5ff&line=bd00ff&point=ffffff&area=true&area_color=00f5ff&hide_border=true" width="95%"/>

</div>

---

<!-- TROPHIES -->
<div align="center">

## ◈ ACHIEVEMENTS ◈

<img src="https://github-profile-trophy.vercel.app/?username=purnanshpatel&theme=radical&no-frame=true&no-bg=true&margin-w=6&column=7" width="95%"/>

</div>

---

<!-- QUOTE -->
<div align="center">

## ◈ DEV QUOTE OF THE DAY ◈

<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical" width="70%"/>

</div>

---

<!-- CONNECT WITH ME -->
<div align="center">

## ◈ CONNECT WITH ME ◈

<a href="https://github.com/purnanshpatel">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>
&nbsp;
<a href="https://linkedin.com/in/purnanshpatel">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
&nbsp;
<a href="mailto:purnanshpatel@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
&nbsp;
<a href="https://twitter.com/purnanshpatel">
  <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" />
</a>

<br/><br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=16&duration=4000&pause=1000&color=BD00FF&center=true&vCenter=true&width=500&lines=Always+open+to+collaborate+%F0%9F%A4%9D;Let's+build+something+amazing+together!+%F0%9F%9A%80;Drop+me+a+message+anytime+%F0%9F%92%AC" alt="connect typing" />

</div>

---

<!-- SNAKE CONTRIBUTION ANIMATION -->
<div align="center">

## ◈ CONTRIBUTION SNAKE ◈

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/purnanshpatel/purnanshpatel/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/purnanshpatel/purnanshpatel/output/github-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/purnanshpatel/purnanshpatel/output/github-snake-dark.svg" />
</picture>

</div>

---

<!-- FOOTER -->
<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d0221,30:1a0533,60:0a0a2e,100:0d0221&height=120&section=footer&animation=fadeIn"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=13&duration=5000&pause=1000&color=00F5FF&center=true&vCenter=true&width=500&lines=Thanks+for+visiting+my+profile!+%E2%AD%90;If+you+like+my+work%2C+leave+a+star!+%F0%9F%92%AB;Let's+connect+and+grow+together+%F0%9F%9A%80" />

<br/>

**⚡ Made with 💙 by Purnansh Patel | Updated Regularly ⚡**

</div>
