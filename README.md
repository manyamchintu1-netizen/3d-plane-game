# 🚀 SkyExplorer — 3D Plane Game

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Platform](https://img.shields.io/badge/Platform-Web%20Browser-brightgreen)]()
[![Made with Three.js](https://img.shields.io/badge/Made%20with-Three.js-blue?logo=javascript)]()

> SkyExplorer is a high-polish, browser-native 3D flying exploration game built with Three.js — no build step required. Fly through skies, explore floating islands, thread rings to score, avoid flocks of birds, and watch the dynamic day/night cycle.

---

## ▶ Play now
Open `index.html` in any modern browser (Chrome/Firefox/Edge/Safari — WebGL required).  
Quick launch (raw view):  
https://htmlpreview.github.io/?https://github.com/manyamchintu1-netizen/3d-plane-game/blob/main/index.html

---

## ✨ Highlights
- Lush, stylized 3D environment (clouds, floating islands, rings)
- Smooth flight model with pitch/roll/yaw, boost, and inertia
- Dynamic day–night cycle with lighting transitions
- Engine trail particles, propeller, glow, and polished shading
- Interactive HUD: Speed, Altitude, Rings/Score
- Procedural ring scoring and moving bird obstacles
- Single-file, no-dependencies gameplay (Three.js via CDN)

---

## 🎮 Controls
- WASD or Arrow Keys — Pitch & Roll (up/down/left/right)
- Mouse — subtle camera/mouse steering
- Space — Boost (short-term speed increase)
- P — Pause / Resume
- Click the page to enable audio (first interaction required on some browsers)

---

## 🧭 Objective & Scoring
- Fly through rings to earn points (+100 per ring).
- Avoid collisions with birds, islands, and the ground (crash triggers Game Over).
- Survive and explore. Beat your best score.

---

## 📦 Files
- `index.html` — Full game (HTML/CSS/JS + Three.js CDN)
- `LICENSE` — MIT
- `CONTRIBUTING.md` — Contribution & development guidelines

---

## 🛠 Technical Notes
- Engine: Three.js r128 (CDN)
- Single-file delivery: HTML contains all game logic and UI
- Performance: scene includes many procedural objects (clouds, islands). If slow, reduce counts in `index.html`.
- Audio: simple engine oscillator (Web Audio API) — requires user gesture to start.

---

## 🚀 How to run locally
Option A — open directly:
- Double-click `index.html` or open it in the browser.

Option B — local HTTP server (recommended if local file issues):
```bash
# Python 3
python -m http.server 8000
# then open http://localhost:8000
