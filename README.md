# Neon Rift Runner

**Neon Rift Runner** is a high-energy, one-file **HTML5 canvas action side-scroller** with procedural levels, tight movement tech, reactive combat, and a fully styled HUD — all implemented with **zero external assets or libraries**.

Just open the file and play.

---

⚠️ **LICENSE & USAGE NOTICE — READ FIRST**

This repository is **source-available for private technical evaluation and testing only**.

- ❌ No commercial use  
- ❌ No production use  
- ❌ No academic, institutional, or government use  
- ❌ No research, benchmarking, or publication  
- ❌ No redistribution, sublicensing, or derivative works  
- ❌ No independent development based on this code  

All rights remain exclusively with the author.  
Use of this software constitutes acceptance of the terms defined in **LICENSE.txt**.

---

## Highlights

- ⚡ Fast, responsive platformer movement
- 🧠 Advanced mechanics: dash cancels, wall jumps, charge shots
- 🧬 Procedurally generated levels with checkpoints
- 👾 Multiple enemy types + boss encounter
- 🔫 Ranged, melee, charge, and dash combat
- 💥 Screen shake, hit-stop, particles, and flash effects (“juice”)
- 🎛️ In-game settings (difficulty, visuals, audio)
- 💾 Best score & best time saved via `localStorage`
- 📱 Touch controls for mobile
- 🔊 Procedural audio & music (Web Audio API)
- 📦 **Single self-contained HTML file**

---

## Controls

### Keyboard
| Action | Keys |
|-----|-----|
| Move | ← → or A / D |
| Jump | ↑ or W / Z |
| Dash | Shift or X |
| Shoot | Space (hold to charge) |
| Melee | C |
| Pause | P |

### Touch (mobile)
On-screen buttons appear automatically on small screens.

---

## How to Run

No setup required.

1. Download or clone the repository
2. Open `Neon Rift Runner.html` in any modern browser
3. Play instantly — works offline

Recommended browsers:
- Chrome
- Edge
- Firefox

---

## Gameplay Overview

- **Goal:** Reach the rift gate at the end of the run
- **Checkpoints:** Save progress mid-run
- **Score:** Combos, kills, coins, speed
- **Difficulty:** Scales with distance & stage
- **Chill Mode:** Optional reduced damage & spawn rate

Powerups:
- 🔥 Fire (faster firing + damage)
- 💚 Heal
- 🛡️ Shield

---

## Technical Overview

- **Rendering:** HTML5 `<canvas>`
- **Game loop:** `requestAnimationFrame`
- **Physics:** Custom AABB collision + resolution
- **Level generation:** Seeded procedural chunks
- **Audio:** Web Audio API (synthesized SFX & music)
- **Persistence:** `localStorage` (best score/time + settings)
- **UI:** HTML/CSS overlay HUD + modals
- **Architecture:** Modular JS sections inside a single file

No images, no audio files, no frameworks.

---

## Settings

Accessible in-game:
- Chill Mode
- Auto-fire
- Screen shake
- Particles
- Scanlines
- HiDPI rendering
- Music & SFX toggles
- Reset best score/time

All settings apply instantly.

---

## Project Structure

Neon Rift Runner.html

yaml
Copy code

Everything — HTML, CSS, JavaScript, audio synthesis — lives in one file by design.

---

## Why this exists

Neon Rift Runner is a proof-of-concept showing how far you can push:
- **pure browser tech**
- **single-file portability**
- **game feel over assets**

---

## Ideas for Extension

- Sprite graphics or shaders
- Multiple biomes
- Enemy AI variants
- Speedrun leaderboard (server-side)
- Replay recording
- Controller support

---

## Contribution Policy

Feedback, bug reports, and suggestions are welcome.

You may submit:

- Issues
- Design feedback
- Pull requests for review

However:

- Contributions do not grant any license or ownership rights
- The author retains full discretion over acceptance and future use
- Contributors receive no rights to reuse, redistribute, or derive from this code

---

## License
This project is not open-source.

It is licensed under a private evaluation-only license.
See LICENSE.txt for full terms.
