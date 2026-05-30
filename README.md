# Scrap Dive

3D Ocean Minesweeper Roguelike — built with Three.js, pure HTML/CSS/JS, no build step.

## Play

Open `index.html` in any modern browser. Works offline as a PWA.

## Install as App (iOS / Android)

1. Open in Safari / Chrome
2. Share → "Add to Home Screen"
3. Launches fullscreen with no browser chrome

## Files

| File | Purpose |
|------|---------|
| `index.html` | Entire game — single file |
| `manifest.json` | PWA manifest (name, icons, display mode) |
| `sw.js` | Service worker — offline caching |
| `icon-192.png` | App icon 192×192 |
| `icon-512.png` | App icon 512×512 |

## Deploy to GitHub Pages

1. Push all files to a repo
2. Settings → Pages → Branch: `main` / root
3. Done — playable at `https://yourusername.github.io/reponame/`
