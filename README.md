# Voxel Sandbox

A creative-mode voxel building game in a single HTML file. No build step, no install — open `index.html` or visit the GitHub Pages site.

## Play

- **W A S D** — move
- **Space** — jump / fly up · **Shift** — fly down
- **F / double-Space** — toggle fly
- **Mouse** — look
- **Left click / E** — place block · **Right click / Q** — break block
- **1–9 / scroll wheel** — pick block
- **Esc** — release mouse

Your world auto-saves to the browser (`localStorage`). Use *reset world* on the start screen to wipe it.

## Tech

- Vanilla JavaScript + [three.js](https://threejs.org/) 0.160 (loaded from CDN)
- Procedurally generated terrain, chunked meshing, pointer-lock first-person controls
- 100% static — hostable anywhere (GitHub Pages, Netlify, a USB stick)

## Run locally

Just open `index.html` in a browser. (An internet connection is needed once to fetch three.js from CDN.)
