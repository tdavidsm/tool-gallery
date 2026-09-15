# 🛠️ Classroom Tools — Gallery

One place to find every free, browser-based classroom tool, with thumbnail previews and links to the live version of each.

**▶ Open it:** https://tdavidsm.github.io/tool-gallery/

## What's inside
A responsive gallery of 12 tools, filterable by subject:

- **Motion & Kinematics** — Rocket Kinematics, Speed Lab, Better Video Analysis
- **Atomic Structure** — Particle Scattering-inator, Rutherford Scatter
- **Chemistry Lab** — Bunsen Burner Simulator, Element Lab, Lab Equipment Match
- **Classroom & Language** — Group-i-fier, Recitation Coach, Scripture Quest
- **For Teachers** — Classroom Tool Workshop

Each card links out to that tool's own GitHub Pages site. Thumbnails live in `img/`.

## Updating the gallery
When you ship a new tool, add a `<a class="card">…</a>` block to `index.html`, drop a screenshot in `img/`, and bump the counts. Everything is one self-contained `index.html` plus images — no build step.

## Tech
Plain HTML/CSS/JS, no dependencies. Light/dark aware, touch-friendly, lazy-loaded thumbnails. School colors (brown & orange). Deployed via GitHub Pages from `main`.
