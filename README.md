<!-- ====================== START OF README ====================== -->

<!-- 1️⃣ Animated gradient background (CSS) -->
<style>
  /* Apply a smooth gradient that shifts hue over time */
  body {
    background: linear-gradient(45deg, #0e0e0e, #1a1a2e, #0e0e0e);
    background-size: 600% 600%;
    animation: gradientShift 12s ease infinite;
  }
  @keyframes gradientShift {
    0%   { background-position: 0% 50%; }
    50%  { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
  }

  /* 2️⃣ Floating particles (tiny circles) */
  .particles {
    position: absolute;
    inset: 0;
    overflow: hidden;
    pointer-events: none;
    z-index: 0;
  }
  .particles circle {
    fill: #ff6b6b;
    opacity: 0.4;
    animation: drift 8s linear infinite;
  }
  @keyframes drift {
    0%   { transform: translateY(0) translateX(0); }
    50%  { transform: translateY(-30px) translateX(20px); }
    100% { transform: translateY(0) translateX(0); }
  }

  /* Keep the main content on top of the particles */
  .content { position: relative; z-index: 1; }
</style>

<!-- 3️⃣ Particles SVG (placed right after <body>) -->
<div class="particles">
<svg width="0" height="0" style="position:absolute">
  <!-- generate a handful of circles; you can add/remove as you like -->
  <circle cx="10%"  cy="20%" r="2"/>
  <circle cx="30%"  cy="80%" r="1.5"/>
  <circle cx="55%"  cy="40%" r="2.2"/>
  <circle cx="70%"  cy="65%" r="1.8"/>
  <circle cx="85%"  cy="25%" r="2.5"/>
  <circle cx="20%"  cy="55%" r="1.2"/>
  <circle cx="45%"  cy="10%" r="1.7"/>
  <circle cx="65%"  cy="85%" r="2"/>
  <circle cx="90%"  cy="70%" r="1.4"/>
</svg>
</div>

<!-- ====================== MAIN CONTENT ====================== -->
<div class="content">

<!-- 1️⃣ Rotating SVG square (SMIL animation) -->
<p align="center">
  <svg width="120" height="120" viewBox="0 0 100 100"
       xmlns="http://www.w3.org/2000/svg">
    <rect x="20" y="20" width="60" height="60"
          fill="none" stroke="#ff6b6b" stroke-width="4">
      <animateTransform attributeName="transform"
                        type="rotate"
                        from="0 50 50"
                        to="360 50 50"
                        dur="8s"
                        repeatCount="indefinite"/>
    </rect>
  </svg>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Firma+Code&size=32&pause=1000&center=true&vCenter=true&width=600&lines=Hi%2C+I'm+Prajwal+Jagtap+%F0%9F%91%8B;ML+Engineer+%7C+GenAI+Enthusiast;Python+%26+C%2B%2B+Developer;Problem+Solver+%F0%9F%9A%80" alt="Typing SVG" />
</p>

<h1 align="center">PRAJWAL JAGTAP</h1>
<h3 align="center">Problem Solver | ML Engineer | GenAI Enthusiast</h3>

<p align="center">
  <img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="500" alt="Coding"/>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/YOUR_LINKEDIN_USERNAME/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin"/>
  </a>
  <a href="https://github.com/prajwal18042006">
    <img src="https://img.shields.io/badge/GitHub-111?style=for-the-badge&logo=github"/>
  </a>
  <a href="https://leetcode.com/prajwaljagtap18-04-2006/">
    <img src="https://img.shields.io/badge/LeetCode-111?style=for-the-badge&logo=leetcode&logoColor=orange"/>
  </a>
  <a href="mailto:prajwaljagtap977@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=prajwal18042006&label=Profile%20Views&color=0e75b6&style=flat" />
</p>

---

## 🌟 Overview

🎓 **3rd Year ENTC Engineering Student**  
🤖 Interested in **Machine Learning, Data Science, GenAI & Agentic AI**  
💻 Practicing **DSA (LeetCode / Codeforces / CodeChef)** for placements  
🚀 Focused on building **end‑to‑end ML projects + deployment**

---

## 🧰 Tech Stack

### 👨‍💻 Languages
![Python](https://img.shields.io/badge/Python-111?style=for-the-badge&logo=python)
![C++](https://img.shields.io/badge/C++-111?style=for-the-badge&logo=c%2B%2B)
![SQL](https://img.shields.io/badge/SQL-111?style=for-the-badge&logo=mysql)

### 🤖 Machine Learning / AI
![scikit-learn](https://img.shields.io/badge/scikit--learn-111?style=for-the-badge&logo=scikitlearn)
![PyTorch](https://img.shields.io/badge/PyTorch-111?style=for-the-badge&logo=pytorch)
![TensorFlow](https://img.shields.io/badge/TensorFlow-111?style=for-the-badge&logo=tensorflow)

### 🛠 Tools & Technologies
![Git](https://img.shields.io/badge/Git-111?style=for-the-badge&logo=git)
![Docker](https://img.shields.io/badge/Docker-111?style=for-the-badge&logo=docker)
![Linux](https://img.shields.io/badge/Linux-111?style=for-the-badge&logo=linux)
![Flask](https://img.shields.io/badge/Flask-111?style=for-the-badge&logo=flask)

---

## 🚀 Featured Projects

| Project | Description | Links |
|--------|-------------|------|
| ❤️ **Heart Disease Detection System** | ML model + prediction web app | [Repo](https://github.com/prajwal18042006) |
| 🌿 **Crop Disease Detection** | CNN / Transfer Learning + scanning + alerts | [Repo](https://github.com/prajwal18042006) |
| 📅 **AI Powered Academic Schedule Assistant** | AI‑based schedule + productivity assistant | [Repo](https://github.com/prajwal18042006) |

---

## 🧠 LeetCode Stats

<p align="center">
  <img src="https://leetcard.jacoblin.cool/prajwaljagtap18-04-2006?theme=dark&font=Karma&ext=contest" />
</p>

---

## 📊 GitHub Stats

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=prajwal18042006&show_icons=true&theme=dark" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=prajwal18042006&layout=compact&theme=dark" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=prajwal18042006&theme=dark" />
</p>

---

## 🏆 GitHub Trophies

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=prajwal18042006&theme=darkhub&no-frame=true&row=1&column=6" />
</p>

---

## 📈 Contribution Graph

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=prajwal18042006&theme=github-compact" />
</p>

---

## 🤝 Connect With Me

<p align="center">
  <a href="https://www.linkedin.com/in/YOUR_LINKEDIN_USERNAME/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin"/>
  </a>
  <a href="https://leetcode.com/prajwaljagtap18-04-2006/">
    <img src="https://img.shields.io/badge/LeetCode-111?style=for-the-badge&logo=leetcode&logoColor=orange"/>
  </a>
  <a href="https://codeforces.com/profile/prajj1842006">
    <img src="https://img.shields.io/badge/Codeforces-111?style=for-the-badge&logo=codeforces"/>
  </a>
  <a href="mailto:prajwaljagtap977@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
</p>

<p align="center">
  <i>“Consistency beats talent when talent doesn’t work hard.”</i>
</p>

</div> <!-- end .content -->

<!-- ======================= END OF README ======================= -->
