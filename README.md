<div align="center">

<!-- Animated Space Invaders header -->
<img src="https://readme-typing-svg.demolab.com?font=Share+Tech+Mono&size=28&duration=3000&pause=1000&color=00FF41&center=true&vCenter=true&width=600&lines=KlossKarl;Building+things+that+shouldn't+exist+yet." alt="Typing SVG" />

<!-- Space invader divider -->
```
▀▄▀▄▀▄  ▄▀▄▀▄▀  ▀▄▀▄▀▄  ▄▀▄▀▄▀  ▀▄▀▄▀▄  ▄▀▄▀▄▀
```

</div>

<div align="center">

<!-- Animated pixel invaders using pure CSS/SVG -->
<svg width="400" height="80" viewBox="0 0 400 80" xmlns="http://www.w3.org/2000/svg">
  <style>
    .invader { animation: march 0.8s steps(2) infinite; }
    .invader:nth-child(2) { animation-delay: 0.4s; }
    .invader:nth-child(3) { animation-delay: 0.2s; }
    .invader:nth-child(4) { animation-delay: 0.6s; }
    .invader:nth-child(5) { animation-delay: 0.1s; }
    @keyframes march {
      0% { transform: translateY(0px); }
      50% { transform: translateY(4px); }
      100% { transform: translateY(0px); }
    }
    .shot { animation: fire 1.2s linear infinite; opacity: 0; }
    @keyframes fire {
      0% { transform: translateY(60px); opacity: 1; }
      100% { transform: translateY(-10px); opacity: 0; }
    }
  </style>
  <!-- Invader 1 -->
  <g class="invader" transform="translate(20, 10)">
    <rect x="8" y="0" width="8" height="8" fill="#00FF41"/>
    <rect x="4" y="8" width="16" height="8" fill="#00FF41"/>
    <rect x="0" y="16" width="24" height="8" fill="#00FF41"/>
    <rect x="0" y="24" width="8" height="8" fill="#00FF41"/>
    <rect x="16" y="24" width="8" height="8" fill="#00FF41"/>
    <rect x="8" y="16" width="4" height="8" fill="#000"/>
    <rect x="12" y="16" width="4" height="8" fill="#000"/>
  </g>
  <!-- Invader 2 -->
  <g class="invader" transform="translate(80, 10)">
    <rect x="8" y="0" width="8" height="8" fill="#00FF41"/>
    <rect x="4" y="8" width="16" height="8" fill="#00FF41"/>
    <rect x="0" y="16" width="24" height="8" fill="#00FF41"/>
    <rect x="0" y="24" width="8" height="8" fill="#00FF41"/>
    <rect x="16" y="24" width="8" height="8" fill="#00FF41"/>
    <rect x="8" y="16" width="4" height="8" fill="#000"/>
    <rect x="12" y="16" width="4" height="8" fill="#000"/>
  </g>
  <!-- Invader 3 -->
  <g class="invader" transform="translate(160, 10)">
    <rect x="8" y="0" width="8" height="8" fill="#00FF41"/>
    <rect x="4" y="8" width="16" height="8" fill="#00FF41"/>
    <rect x="0" y="16" width="24" height="8" fill="#00FF41"/>
    <rect x="0" y="24" width="8" height="8" fill="#00FF41"/>
    <rect x="16" y="24" width="8" height="8" fill="#00FF41"/>
    <rect x="8" y="16" width="4" height="8" fill="#000"/>
    <rect x="12" y="16" width="4" height="8" fill="#000"/>
  </g>
  <!-- Invader 4 -->
  <g class="invader" transform="translate(240, 10)">
    <rect x="8" y="0" width="8" height="8" fill="#00FF41"/>
    <rect x="4" y="8" width="16" height="8" fill="#00FF41"/>
    <rect x="0" y="16" width="24" height="8" fill="#00FF41"/>
    <rect x="0" y="24" width="8" height="8" fill="#00FF41"/>
    <rect x="16" y="24" width="8" height="8" fill="#00FF41"/>
    <rect x="8" y="16" width="4" height="8" fill="#000"/>
    <rect x="12" y="16" width="4" height="8" fill="#000"/>
  </g>
  <!-- Invader 5 -->
  <g class="invader" transform="translate(320, 10)">
    <rect x="8" y="0" width="8" height="8" fill="#00FF41"/>
    <rect x="4" y="8" width="16" height="8" fill="#00FF41"/>
    <rect x="0" y="16" width="24" height="8" fill="#00FF41"/>
    <rect x="0" y="24" width="8" height="8" fill="#00FF41"/>
    <rect x="16" y="24" width="8" height="8" fill="#00FF41"/>
    <rect x="8" y="16" width="4" height="8" fill="#000"/>
    <rect x="12" y="16" width="4" height="8" fill="#000"/>
  </g>
  <!-- Laser shot -->
  <rect class="shot" x="192" y="0" width="4" height="12" fill="#FF0000"/>
</svg>

</div>

---

<div align="center">

## 🧠 WHAT I SHIP

</div>

<table align="center">
<tr>
<td width="50%" valign="top">

### 🪡 [LOOM](https://github.com/KlossKarl/loom)
**Local-first second brain**

Your vault. Your machine. No cloud, no subscription, no vendor that gets acquired.

- ChromaDB vector index + Neo4j knowledge graph
- Automated intake: audio, PDFs, web, academic papers
- Local LLM via Ollama — nothing leaves your machine
- The only PKM tool that proactively tells you what you forgot you knew

![Stars](https://img.shields.io/github/stars/KlossKarl/loom?style=flat-square&color=00FF41&labelColor=000)

</td>
<td width="50%" valign="top">

### ⚡ [FLUX](https://github.com/KlossKarl/flux)
**Design → Code pipeline**

Drop a handoff folder. Run `flux deploy`. Done.

- One command from Claude Design to deployed code
- Handles the spec, the implementation, the commit, the push
- `npx claude-flux deploy`
- The bridge Anthropic said they'd build

![npm](https://img.shields.io/npm/v/claude-flux?style=flat-square&color=00d4ff&labelColor=000)
![Stars](https://img.shields.io/github/stars/KlossKarl/flux?style=flat-square&color=00d4ff&labelColor=000)

</td>
</tr>
</table>

---

<div align="center">

## 🔬 ON THE BENCH

*Vertical industry tools. Document-heavy workflows. Structural extraction.*

`SolarExtract` &nbsp;·&nbsp; `Alford` &nbsp;·&nbsp; `OTIS`

---

## STACK

![Python](https://img.shields.io/badge/Python-000?style=flat-square&logo=python&logoColor=00FF41)
![JavaScript](https://img.shields.io/badge/JavaScript-000?style=flat-square&logo=javascript&logoColor=00FF41)
![Node.js](https://img.shields.io/badge/Node.js-000?style=flat-square&logo=node.js&logoColor=00FF41)
![Neo4j](https://img.shields.io/badge/Neo4j-000?style=flat-square&logo=neo4j&logoColor=00FF41)
![Claude](https://img.shields.io/badge/Claude-000?style=flat-square&logo=anthropic&logoColor=00FF41)

---

## STATS

<img src="https://github-readme-stats.vercel.app/api?username=KlossKarl&show_icons=true&theme=chartreuse-dark&bg_color=000000&hide_border=true&icon_color=00FF41&title_color=00FF41&text_color=ffffff" alt="GitHub Stats" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=KlossKarl&theme=matrix&background=000000&hide_border=true&stroke=00FF41&ring=00FF41&fire=ff6600&currStreakLabel=00FF41" alt="Streak" />

---

<!-- Snake game contribution graph -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/KlossKarl/KlossKarl/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/KlossKarl/KlossKarl/output/github-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/KlossKarl/KlossKarl/output/github-snake-dark.svg" />
</picture>

---

*Tampa, FL &nbsp;·&nbsp; [loom](https://github.com/KlossKarl/loom) &nbsp;·&nbsp; [flux](https://github.com/KlossKarl/flux)*

<!-- visitor counter -->
![](https://komarev.com/ghpvc/?username=KlossKarl&color=00FF41&style=flat-square&label=VISITORS)

</div>
