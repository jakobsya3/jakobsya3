<p align="center">
  <img src="assets/banner.svg" alt='HALLO WORLD! banner' />
</p>

<?xml version="1.0" encoding="UTF-8"?>
<svg width="1200" height="260" viewBox="0 0 1200 260" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0" x2="1" y1="0" y2="1">
      <stop offset="0" stop-color="#0b1220"/>
      <stop offset="1" stop-color="#0a0f1a"/>
    </linearGradient>

    <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="3" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

    <style>
      .title {
        font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;
        font-size: 64px;
        font-weight: 700;
        fill: #60a5fa;
        letter-spacing: 1px;
      }
      .cursor {
        font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;
        font-size: 64px;
        font-weight: 800;
        fill: #60a5fa;
      }
      .hint {
        font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;
        font-size: 18px;
        fill: #94a3b8;
      }
    </style>
  </defs>

  <!-- Background -->
  <rect x="0" y="0" width="1200" height="260" rx="18" fill="url(#bg)"/>

  <!-- Subtle grid -->
  <g opacity="0.10">
    <path d="M0 52 H1200 M0 104 H1200 M0 156 H1200 M0 208 H1200" stroke="#93c5fd" stroke-width="1"/>
    <path d="M120 0 V260 M240 0 V260 M360 0 V260 M480 0 V260 M600 0 V260 M720 0 V260 M840 0 V260 M960 0 V260 M1080 0 V260" stroke="#93c5fd" stroke-width="1"/>
  </g>

  <!-- Terminal prompt -->
  <text x="70" y="95" class="hint" opacity="0.9">$ echo "</text>

  <!-- Typing text revealed via animated clip width -->
  <clipPath id="reveal">
    <rect x="190" y="40" width="0" height="90">
      <animate attributeName="width" values="0; 620" dur="2.2s" fill="freeze" />
    </rect>
  </clipPath>

  <g clip-path="url(#reveal)" filter="url(#glow)">
    <text x="190" y="115" class="title">HALLO WORLD!</text>
  </g>

  <!-- Closing quote -->
  <text x="820" y="95" class="hint" opacity="0.9">"</text>

  <!-- Blinking cursor -->
  <text x="835" y="115" class="cursor">|
    <animate attributeName="opacity" values="1;0;1" dur="0.9s" repeatCount="indefinite"/>
  </text>

  <!-- Bottom hint -->
  <text x="70" y="205" class="hint">Welcome to my GitHub profile</text>
</svg>


## Hi, I'm Jakob 👋

Computer Science student based in Duisburg (NRW, Germany) with a focus on Java and Python, currently building solid fundamentals in software development and databases.

[![GitHub](https://img.shields.io/badge/-GitHub-000?style=flat&logo=github&logoColor=white)](https://github.com/<dein-username>)
[![Email](https://img.shields.io/badge/-Email-c14438?style=flat&logo=gmail&logoColor=white)](mailto:yaqoup.aldagher@gmail.com)

&nbsp;

### About me
- 🎓 Computer Science student.
- 💻 Main focus: Java, OOP, clean code, and databases (SQL).
- 🧰 Tools: IntelliJ IDEA, Git, PostgreSQL (optional: add what you actually use).
- 🌱 Currently learning: <z.B. OOP, SQL joins, JDBC, Testing mit JUnit>.
- 📫 How to reach me: [yaqoup.aldagher@gmail.com](mailto:yaqoup.aldagher@gmail.com)

### Languages & Tools
<p>
  <code><img width="10%" src="https://www.vectorlogo.zone/logos/java/java-ar21.svg"></code>
  <code><img width="10%" src="https://www.vectorlogo.zone/logos/python/python-ar21.svg"></code>
  <code><img width="10%" src="https://www.vectorlogo.zone/logos/postgresql/postgresql-ar21.svg"></code>
  <br />
  <code><img width="10%" src="https://www.vectorlogo.zone/logos/git-scm/git-scm-ar21.svg"></code>
  <code><img width="10%" src="https://www.vectorlogo.zone/logos/jetbrains/jetbrains-ar21.svg"></code>
</p>

### GitHub stats
<img alt="Jakob's GitHub stats" src="https://github-readme-stats.vercel.app/api?username=<dein-username>&show_icons=true&hide_border=true" />
<img alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=<dein-username>&layout=compact&hide_border=true" />

### Projects
- 🔹 **<Projekt 1 Name>** — <1 Satz Beschreibung> → https://github.com/<dein-username>/<repo1>
- 🔹 **<Projekt 2 Name>** — <1 Satz Beschreibung> → https://github.com/<dein-username>/<repo2>
