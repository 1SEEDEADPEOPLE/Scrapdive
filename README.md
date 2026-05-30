# Scrap Dive

**3D Ocean Minesweeper Roguelike** — dive into the deep, sweep mines, collect scrap, unlock modules.

Built with Three.js. Single HTML file, no build step, works offline as a PWA.

---

## Play

Open `index.html` in any modern browser, or visit the GitHub Pages URL.

## Install as App (iOS / Android)

**iOS Safari:** Share → "Add to Home Screen"  
**Android Chrome:** Menu → "Add to Home Screen" or "Install App"

Launches fullscreen with no browser chrome.

---

## Files

| File | Purpose |
|------|---------|
| `index.html` | Entire game — single file |
| `manifest.json` | PWA manifest |
| `sw.js` | Service worker — offline caching |
| `icon-192.png` | App icon 192×192 |
| `icon-512.png` | App icon 512×512 |

## Deploy to GitHub Pages

1. Push all 5 files to a repo root
2. **Settings → Pages → Branch: `main` / root → Save**
3. Live at `https://yourusername.github.io/reponame/`

---

## Controls

| Action | Mobile | Desktop |
|--------|--------|---------|
| Reveal tile | Tap | Left click |
| Flag tile | Long press / Flag mode | Right click |
| Collect scrap | Tap near scrap | Left click near scrap |
| Use module | Tap module button | Click module button |
| Abort dive | SURFACE button | SURFACE button |
