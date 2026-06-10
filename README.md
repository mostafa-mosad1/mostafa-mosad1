## 🏆 GitHub trophies

<div align="center">

[![Trophies](https://github-profile-trophy.vercel.app/?username=YOUR_GITHUB_USERNAME&theme=tokyonight&no-frame=true&no-bg=true&margin-w=4&row=1)](https://github.com/ryo-ma/github-profile-trophy)

</div>

---

## 📊 GitHub stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=YOUR_GITHUB_USERNAME&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true"/>
<img height="170" src="https://github-readme-streak-stats.herokuapp.com/?user=YOUR_GITHUB_USERNAME&theme=tokyonight&hide_border=true"/>

</div>

<div align="center">

<img width="42%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_GITHUB_USERNAME&layout=compact&theme=tokyonight&hide_border=true&langs_count=8"/>

</div>

---

## 📈 Contribution graph

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=YOUR_GITHUB_USERNAME&theme=tokyo-night&hide_border=true&area=true&custom_title=Mostafa%27s%20Contribution%20Graph"/>

</div>

---

## 🐍 Contribution snake

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/YOUR_GITHUB_USERNAME/YOUR_GITHUB_USERNAME/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/YOUR_GITHUB_USERNAME/YOUR_GITHUB_USERNAME/output/github-contribution-grid-snake.svg"/>
  <img alt="contribution snake" src="https://raw.githubusercontent.com/YOUR_GITHUB_USERNAME/YOUR_GITHUB_USERNAME/output/github-contribution-grid-snake.svg"/>
</picture>

</div>


name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
