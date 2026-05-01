# ORBITAL_DRIFT

**A high-speed orbital action game. Manage your energy and survive the lethal pursuit.**

🎮 **Play now → [sin1.studio/ORBITAL_DRIFT](https://sin1.studio/ORBITAL_DRIFT/)**

---

## Overview

ORBITAL_DRIFT is a browser-based action game where you navigate a glowing orb through 5 stages of increasingly dangerous planetary obstacles. Every tap costs energy — run out and the planets hunt you down.

---

## How to Play

1. **Tap / Click** anywhere on the screen to move your orb toward that point
2. Each tap costs **-10 ENERGY**
3. Reach the **yellow goal** to clear the stage
4. Avoid the **red planets** and their orbiting satellites
5. Clear all 5 stages to complete the mission

### Energy System

| Energy | Status |
|--------|--------|
| > 40   | Normal movement |
| 1–40   | DANGER — HUD flashes red |
| 0      | Enemies lock on and chase you — you cannot move |

---

## Stages

| Stage | Enemies | Notes |
|-------|---------|-------|
| 1 | 3 | Tutorial pace |
| 2 | 4 | Slightly faster rotation |
| 3 | 5 | Wall planets added |
| 4 | 7 | Tight corridors |
| 5 | **BOSS** | Multi-satellite boss chase |

---

## Controls

| Input | Action |
|-------|--------|
| Mouse click | Move player |
| Touch (tap) | Move player (mobile) |
| Touch (drag) | Continuous movement |

---

## Tech Stack

- **Vanilla HTML / CSS / JavaScript** — no frameworks, no build step
- **Canvas 2D API** — all rendering
- **Google Analytics (gtag.js)** — play tracking
- **Google Fonts** — Sawarabi Mincho (UI)

---

## Project Structure

```
ORBITAL_DRIFT/
├── index.html      # Game (single file — all logic, rendering, styles)
└── ogp.png         # OGP image for social sharing
```

---

## Development

Just open `index.html` in a browser — no install required.

```bash
git clone https://github.com/sin1n24/ORBITAL_DRIFT.git
cd ORBITAL_DRIFT
open index.html
```

---

## Known Limitations

- Audio is not implemented
- No save / high-score persistence
- Landscape orientation recommended on mobile

---

## License

© 2026 [sin1's studio](https://sin1.studio/)  
All rights reserved.

---
