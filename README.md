## Hi, I'm Adil 👋

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=58A6FF&center=true&vCenter=true&width=600&lines=BS+AI+Student+%40+UET+Peshawar;Learning+Python+%E2%86%92+SQL+%E2%86%92+ML+%E2%86%92+Agentic+AI;Founder+%40+Adil+Gulf+Manpower+Solutions;Building+my+way+to+AI+Engineer" alt="Typing SVG" />

BS Artificial Intelligence student at UET Peshawar, rebuilding my skills from the ground up on the path to becoming an AI Engineer. I also run a manpower recruitment business connecting Pakistani workers with employers in Saudi Arabia and the Gulf.

- 🔭 **Currently learning:** Python basics (restarting my AI Engineer roadmap from scratch)
- 🗺️ **Full roadmap:** Excel → Python → Statistics → SQL → Pandas/NumPy → Data Visualization (Matplotlib/Seaborn + Power BI) → Machine Learning (scikit-learn) → AI/LLM basics → Agentic AI (LangChain/CrewAI) → Portfolio/Career
- 💼 **Running:** Adil Gulf Manpower Solutions — recruitment for KSA & Gulf employers
- 🎯 **Goals:** Land an AI Engineer role, targeting KSA near-term and USA/UK long-term, plus an international MS
- 🛠️ **Building along the way:** small real-world tools — CV/candidate formatters, a recruitment database, a video converter
- 🌱 **Also exploring:** Power BI, cloud computing
- 📫 **Reach me:** open to entry-level AI/data roles and remote work
- ⚡ **Fun fact:** I like AI-generated art, photography, and football

## 🛠️ Tech & Tools

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=plotly&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

## Featured projects

| Project | Description |
|---|---|
| **Adil Gulf Manpower Solutions — Website** | CEO-branded site redesign with LinkedIn/WhatsApp contact flow |
| **Recruitment Database** | MySQL database tracking candidates, employers, and placement status |
| **Candidate Message Formatter** | Python functions that auto-generate candidate status messages |
| **Video Converter** | Browser-based video converter tool |

## 📊 GitHub Stats

<img src="https://github-readme-stats.vercel.app/api?username=adilqayum&show_icons=true&theme=tokyonight&hide_border=true" alt="Adil's GitHub stats" height="165" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=adilqayum&theme=tokyonight&hide_border=true" alt="Adil's streak stats" height="165" />

## 🐍 Contribution Snake

<img src="https://raw.githubusercontent.com/adilqayum/adilqayum/output/github-contribution-grid-snake.svg" alt="Contribution snake animation" />

> The stats and snake animation need one-time setup — see below.

<details>
<summary>⚙️ Setup notes (one-time)</summary>

**Stats cards:** already work automatically once `adilqayum` is your real GitHub username — just swap it in the two image URLs above if your username is different.

**Contribution snake:** needs a small GitHub Action to generate it.
1. In your `adilqayum/adilqayum` repo, go to **Actions → New workflow → set up a workflow yourself**
2. Paste this and commit it as `.github/workflows/snake.yml`:

```yaml
name: Generate Snake
on:
  schedule:
    - cron: "0 */6 * * *"
  workflow_dispatch:
  push:
    branches: [ main ]
jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: dist/github-contribution-grid-snake.svg
      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```
3. Run it once manually (Actions tab → Run workflow) — it creates an `output` branch with the animated SVG, which the image link above already points to.

</details>
