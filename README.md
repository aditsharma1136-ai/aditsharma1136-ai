<h1 align="center">Hi 👋, I'm Aditya Sharma</h1>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?size=25&duration=4000&color=00F7FF&center=true&vCenter=true&width=600&lines=Aspiring+Full+Stack+Developer;AI+Enthusiast;React+Learner;Future+Tech+Builder" />
</p>

---

## 🧠 About Me
- 🚀 Learning **React, JavaScript, AI**
- 💡 Love building **real-world projects**
- 🎯 Goal: **Full Stack + AI Engineer**
- ⚡ Always curious about **future tech**

---

## 🛠️ Tech Stack
<p align="center">
  <img src="https://skillicons.dev/icons?i=html,css,js,react,nodejs,python,mysql,git,github,vscode" />
</p>

---

## 📊 GitHub Analytics
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=tokyonight&hide_border=true" height="150"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=YOUR_USERNAME&theme=tokyonight&hide_border=true" height="150"/>
</p>

---

## 📈 Top Languages
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&theme=tokyonight&hide_border=true"/>
</p>

---

## 🐍 Contribution Snake (Futuristic Animation)
<p align="center">
  <img src="https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_USERNAME/output/github-contribution-grid-snake.svg" />
</p>

---

## 🌐 Connect With Me
<p align="center">
  <a href="https://linkedin.com/in/YOUR_LINKEDIN">LinkedIn</a> •
  <a href="mailto:your-email@gmail.com">Email</a> •
  <a href="https://twitter.com/YOUR_TWITTER">Twitter</a>
</p>

---

## ⚡ System Status
```bash
> Initializing Aditya.exe...
> Loading Skills ██████████ 100%
> Status: Ready to Build 🚀



---

## 🚀 EXTRA (Important Setup for Snake Animation)

To make the 🐍 animation work:

1. Create folder: `.github/workflows`
2. Add file: `snake.yml`

```yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest

    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: YOUR_USERNAME
          outputs: |
            dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
