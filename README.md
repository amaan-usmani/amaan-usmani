<!--
  GitHub Profile README for Amaan Usmani
  Replace <YOUR_GITHUB_USERNAME> below with your GitHub username
-->




<h1 align="center" style="margin-bottom:0">Amaan Usmani</h1>
<p align="center" style="margin-top:4px">
  <strong>Data Engineer 🚀 | Turning raw data into real insights</strong>
</p>

<!-- Typing animation -->
<p align="center" style="margin-top: 10px">
  <img src="https://readme-typing-svg.herokuapp.com/?font=Fira+Code&size=24&duration=3000&pause=800&color=DDDDDD&width=650&height=50&lines=Data+Engineer;Data+Analysis+Pipelines;+Website+Dev;+Python+Revision" alt="typing svg"/>
</p>

---

<!-- Social / quick badges -->
<p align="center">
  <!-- Replace YOUR_GITHUB_USERNAME with your username -->
  <a href="https://github.com/<amaan-usmani>">
    <img alt="Profile views" src="https://komarev.com/ghpvc/?username=<amaan-usmani>&style=flat-square&color=2bbc8a"/>
  </a>
  <a href="https://github.com/<amaan-usmani>">
    <img alt="Top Langs" src="https://github-readme-stats.vercel.app/api/top-langs/?username=<YOUR_GITHUB_USERNAME>&layout=compact&theme=radical&hide_border=true"/>
  </a>
</p>

---

## 🎯 About Me
I'm **Amaan Usmani**, a **Data Engineer** focused on building reliable data pipelines and transforming messy data into clear, actionable insights.  
I enjoy designing end-to-end data workflows, exploring data visually, and writing pragmatic Python.

**Current focus:** _Leveling up my Data Engineering skills through hands-on projects and cloud fundamentals (AWS)._  

---

## 📊 Tech Stack
<p>
  <!-- Shields: adjust or remove any you don't use -->
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="python"/>
  <img src="https://img.shields.io/badge/SQL-003B57?style=for-the-badge&logo=postgresql&logoColor=white" alt="sql"/>
  <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white" alt="java"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="pandas"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="numpy"/>
  <img src="https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black" alt="powerbi"/>
  <img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" alt="excel"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="git"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="github"/>
  <img src="https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apache-airflow&logoColor=white" alt="airflow"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="mysql"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="mongodb"/>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" alt="aws"/>
</p>

---

## 🚀 Featured Projects

### 📈 Data Analysis Projects
**What:** EDA, dashboards, model-agnostic insights, automated report generation.  
**Highlights:**
- Exploratory Data Analysis pipelines using Pandas & NumPy.
- Visualizations & dashboards (Power BI / Matplotlib / Plotly).
- Actionable insights presented to stakeholders.

**Links:**  
[🔗 Repo: data-analysis-projects](https://github.com/<YOUR_GITHUB_USERNAME>/data-analysis-projects) • [🌐 Demo (if any)](#)

---

### 🌐 Website Project
**What:** Full website (frontend + backend) showcasing projects and dashboards.  
**Tech:** HTML/CSS/JS (or React), Flask/Django backend, deployed on Netlify / Vercel / Heroku.  
**Highlights:**
- Interactive dashboards embedded
- Clean, dark-themed UI

**Links:**  
[🔗 Repo: personal-website](https://github.com/<YOUR_GITHUB_USERNAME>/personal-website) • [🌐 Live demo (if any)](#)

---

### 🧠 Python Revision Projects
**What:** Small scripts, algorithm revision notebooks, helpers for interviews.  
**Highlights:**
- Algorithm practice snippets
- Utility libraries for data cleaning & feature engineering

**Links:**  
[🔗 Repo: python-revision](https://github.com/<YOUR_GITHUB_USERNAME>/python-revision)

---

## 📈 GitHub Stats & Activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=<amaan-usmani>&show_icons=true&theme=dark&count_private=true&hide_border=true" alt="github stats" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=<Yamaan-usmani>&theme=dark" alt="streak" />
</p>

---

## 📩 Connect with Me
<p align="center">
  <a href="https://www.linkedin.com/in/amaaanusmani" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="linkedin"/>
  </a>
  <a href="mailto:your.email@example.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="email"/>
  </a>
  <a href="https://your-portfolio.example.com" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-111111?style=for-the-badge&logo=google-chrome&logoColor=white" alt="portfolio"/>
  </a>
</p>

---

## 🔧 How to Use / Customize
1. Replace **`<YOUR_GITHUB_USERNAME>`** with your GitHub username everywhere in this file.
2. Replace the repo/demo links with your real repo URLs and live demo URLs.
3. Update LinkedIn / Email / Portfolio links.
4. Optionally swap shields, themes or GIFs to match your aesthetic

![Snake animation](https://raw.githubusercontent.com/amaaanusmani/amaaanusmani/output/github-contribution-grid-snake-dark.svg)



name: Generate Snake Animation

on:
  schedule: 
    - cron: "0 */12 * * *"
  push:
    branches:
      - main
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest

    steps:
      - uses: actions/checkout@v4

      - name: Generate Snake
        uses: Platane/snk@v3
        with:
          github_user_name: amaaanusmani
          outputs: |
            dist/github-contribution-grid-snake-dark.svg

      - name: Push output
        uses: stefanzweifel/git-auto-commit-action@v4
        with:
          commit_message: "Generated snake animation"
          file_pattern: "dist/*"
![GitHub Skyline](./skyline/skyline.gif)


name: Generate GitHub Skyline

on:
  schedule:
    - cron: '0 0 * * *'
  workflow_dispatch:

jobs:
  skyline:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4

      - name: Generate 3D GitHub Skyline
        run: |
          npm install -g github-skyline-cli
          github-skyline-cli amaaanusmani --format gif --out ./skyline/skyline.gif

      - name: Commit and push
        uses: stefanzweifel/git-auto-commit-action@v4
        with:
          commit_message: "Update GitHub skyline"
          file_pattern: skyline/skyline.gif

         ![Metrics](./metrics.svg)

         name: Generate Metrics

on:
  schedule:
    - cron: "0 */6 * * *"
  workflow_dispatch:

jobs:
  metrics:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: lowlighter/metrics@latest
        with:
          token: ${{ secrets.GITHUB_TOKEN }}
          user: amaaanusmani
          template: classic
          base: header, activity, community, repositories
          config_animations: true
          config_timezone: Asia/Kolkata
          filename: metrics.svg

      - uses: stefanzweifel/git-auto-commit-action@v4
        with:
          commit_message: "Update metrics image"
          file_pattern: metrics.svg

          
![Trophies](https://github-profile-trophy.vercel.app/?username=amaaanusmani&theme=juicyfresh&no-bg=true&no-frame=true&column=8)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2b5876,100:4e4376&height=250&section=header&text=Amaan%20Usmani&fontSize=60&fontColor=ffffff"/>

![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white)


<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?size=30&duration=3000&color=34F6F1&center=true&vCenter=true&repeat=true&width=700&height=70&lines=Data+Engineer;Data+Analyst;ML+Learner;Turning+Raw+Data+Into+Insights">
</p>


![Amaan's Graph](https://github-readme-activity-graph.vercel.app/graph?username=amaaanusmani&theme=react-dark&hide_border=true)





---

_Last updated: <!--LAST_UPDATED-->_

