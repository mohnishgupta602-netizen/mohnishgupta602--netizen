<div align="center">
  <!-- Dynamic Gradient Wave Header with Neon Accents -->
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:00f2fe&height=220&section=header&text=Mohnish%20Narayan%20Gupta&fontSize=42&fontColor=ffffff&fontAlignY=38&desc=Software%20Engineer%20%7C%20Distributed%20Systems%20%7C%20Machine%20Intelligence&descSize=16&descAlignY=58&descColor=38bdf8&animation=fadeIn" width="100%" />

  <!-- Animated Terminal Typing SVG -->
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&pause=1000&color=00F2FE&center=true&vCenter=true&multiline=true&width=620&height=80&lines=%E2%96%B6+Architecting+Fault-Tolerant+Backend+Engines;%E2%96%B6+Streaming+High-Throughput+Real-Time+Pipelines;%E2%96%B6+Accelerating+ML+Inference+%26+Vector+Embeddings;%E2%96%B6+Rendering+Interactive+WebGL+%26+Spatial+Visuals" alt="Typing SVG" />
  </a>

  <!-- Social Badges with Cyberpunk Accents -->
  <p align="center">
    <a href="https://linkedin.com/in/YOUR_LINKEDIN"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
    <a href="https://YOUR_PORTFOLIO_SITE"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=00f2fe" /></a>
    <a href="mailto:YOUR_EMAIL@example.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
    <img src="https://komarev.com/ghpvc/?username=YOUR_GITHUB_USERNAME&style=for-the-badge&color=00f2fe" alt="Profile Views" />
  </p>
</div>

---

### ⚡ System Overview

```typescript
interface SoftwareEngineer {
  name: "Mohnish Narayan Gupta";
  focus: ["Scalable Microservices", "Real-Time Streaming", "Applied AI/CV", "3D Graphics"];
  architecturePatterns: ["Event-Driven", "Pub/Sub", "WAL Logging", "Vector Retrieval"];
  status: "Deploying high-throughput services & competing in hackathons";
}

name: Generate Snake Animation

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: Platane/snk@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
      - uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
