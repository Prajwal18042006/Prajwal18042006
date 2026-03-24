<!-- ═══════════════════════════════════════════════════════════════════════════
  🐍 HOW THE SNAKE WORKS — READ THIS ONCE
  ─────────────────────────────────────────
  1. Create a file in your repo at:
       .github/workflows/snake.yml
  2. Paste the content between the dashes below into that file.
  3. Go to Actions tab → "Generate Snake" → Run workflow (first time manual).
  4. After it runs, it pushes the SVG to your "output" branch automatically.
  5. The snake images in this README will start animating immediately. ✅
  ─────────────────────────────────────────
  snake.yml content:
  ──────────────────────────────────────────────────────────────────────────
  name: Generate Snake
  on:
    schedule:
      - cron: "0 */12 * * *"
    workflow_dispatch:
  jobs:
    generate:
      runs-on: ubuntu-latest
      steps:
        - uses: Platane/snk/svg-only@v3
          with:
            github_user_name: prajwal18042006
            outputs: |
              dist/github-contribution-grid-snake.svg
              dist/github-contribution-grid-snake-dark.svg?palette=github-dark
        - uses: crazy-max/ghaction-github-pages@v3
          with:
            target_branch: output
            build_dir: dist
          env:
            GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
  ──────────────────────────────────────────────────────────────────────────
════════════════════════════════════════════════════════════════════════════ -->

<!-- TOP SNAKE ANIMATION -->
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)"
      srcset="https://raw.githubusercontent.com/prajwal18042006/prajwal18042006/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)"
      srcset="https://raw.githubusercontent.com/prajwal18042006/prajwal18042006/output/github-contribution-grid-snake.svg" />
    <img alt="GitHub Snake Animation"
      src="https://raw.githubusercontent.com/prajwal18042006/prajwal18042006/output/github-contribution-grid-snake-dark.svg" />
  </picture>
</div>

---

<!-- TYPING HEADER -->
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=32&pause=1000&center=true&vCenter=true&width=620&lines=Hi%2C+I'm+Prajwal+Jagtap+%F0%9F%91%8B;ML+Engineer+%7C+GenAI+Enthusiast;Python+%26+C%2B%2B+Developer;Problem+Solver+%F0%9F%9A%80" alt="Typing SVG" />
</p>

<h1 align="center">PRAJWAL JAGTAP</h1>
<h3 align="center">Problem Solver | ML Engineer | GenAI Enthusiast</h3>

<p align="center">
  <img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="500" alt="Coding GIF"/>
</p>

<!-- SOCIAL BADGES -->
<p align="center">
  <a href="https://www.linkedin.com/in/YOUR_LINKEDIN_USERNAME/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="https://github.com/prajwal18042006">
    <img src="https://img.shields.io/badge/GitHub-111?style=for-the-badge&logo=github&logoColor=white"/>
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
🚀 Focused on building **end-to-end ML projects + deployment**

---

## 🧰 Tech Stack

### 👨‍💻 Languages
![Python](https://img.shields.io/badge/Python-111?style=for-the-badge&logo=python&logoColor=3776AB)
![C++](https://img.shields.io/badge/C++-111?style=for-the-badge&logo=c%2B%2B&logoColor=00599C)
![SQL](https://img.shields.io/badge/SQL-111?style=for-the-badge&logo=mysql&logoColor=4479A1)

### 🤖 Machine Learning / AI
![scikit-learn](https://img.shields.io/badge/scikit--learn-111?style=for-the-badge&logo=scikitlearn&logoColor=F7931E)
![PyTorch](https://img.shields.io/badge/PyTorch-111?style=for-the-badge&logo=pytorch&logoColor=EE4C2C)
![TensorFlow](https://img.shields.io/badge/TensorFlow-111?style=for-the-badge&logo=tensorflow&logoColor=FF6F00)

### 🛠 Tools & Technologies
![Git](https://img.shields.io/badge/Git-111?style=for-the-badge&logo=git&logoColor=F05032)
![Docker](https://img.shields.io/badge/Docker-111?style=for-the-badge&logo=docker&logoColor=2496ED)
![Linux](https://img.shields.io/badge/Linux-111?style=for-the-badge&logo=linux&logoColor=FCC624)
![Flask](https://img.shields.io/badge/Flask-111?style=for-the-badge&logo=flask&logoColor=white)

---

## 🚀 Featured Projects

| Project | Description | Links |
|--------|-------------|-------|
| ❤️ **Heart Disease Detection System** | ML model + prediction web app | [Repo](https://github.com/prajwal18042006) |
| 🌿 **Crop Disease Detection** | CNN / Transfer Learning + scanning + alerts | [Repo](https://github.com/prajwal18042006) |
| 📅 **AI Powered Academic Schedule Assistant** | AI-based schedule + productivity assistant | [Repo](https://github.com/prajwal18042006) |

---

## 🧠 LeetCode Stats

<p align="center">
  <img src="https://leetcard.jacoblin.cool/prajwaljagtap18-04-2006?theme=dark&font=Karma&ext=contest" alt="LeetCode Stats"/>
</p>

---

## 📊 GitHub Stats

<p align="center">
  <img height="170"
    src="https://github-readme-stats.vercel.app/api?username=prajwal18042006&show_icons=true&theme=dark&hide_border=true"
    alt="GitHub Stats"/>
  <img height="170"
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=prajwal18042006&layout=compact&theme=dark&hide_border=true"
    alt="Top Languages"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=prajwal18042006&theme=dark&hide_border=true"
    alt="GitHub Streak"/>
</p>

---

## 🏆 GitHub Trophies

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=prajwal18042006&theme=darkhub&no-frame=true&row=1&column=6"
    alt="GitHub Trophies"/>
</p>

---

## 📈 Contribution Graph

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=prajwal18042006&theme=github-compact&hide_border=true"
    alt="Contribution Graph"/>
</p>

---

## 🤝 Connect With Me

<p align="center">
  <a href="https://www.linkedin.com/in/YOUR_LINKEDIN_USERNAME/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="https://leetcode.com/prajwaljagtap18-04-2006/">
    <img src="https://img.shields.io/badge/LeetCode-111?style=for-the-badge&logo=leetcode&logoColor=orange"/>
  </a>
  <a href="https://codeforces.com/profile/prajj1842006">
    <img src="https://img.shields.io/badge/Codeforces-111?style=for-the-badge&logo=codeforces&logoColor=1F8ACB"/>
  </a>
  <a href="mailto:prajwaljagtap977@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
</p>

<p align="center">
  <i>"Consistency beats talent when talent doesn't work hard."</i>
</p>

<!-- BOTTOM SNAKE ANIMATION -->
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)"
      srcset="https://raw.githubusercontent.com/prajwal18042006/prajwal18042006/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)"
      srcset="https://raw.githubusercontent.com/prajwal18042006/prajwal18042006/output/github-contribution-grid-snake.svg" />
    <img alt="GitHub Snake Footer"
      src="https://raw.githubusercontent.com/prajwal18042006/prajwal18042006/output/github-contribution-grid-snake-dark.svg" />
  </picture>
</div>
