# SUBJECT 07 — Three.js Lab Escape 🧬

You wake as **test subject 07**, infected with an unknown virus. Find the cure, consume it — and escape.

A single-file [Three.js](https://threejs.org/) escape-room game. No build step: just open `index.html` (internet required for the Three.js CDN).

## The 3 steps

1. **Identify the virus** — take your height + weight at the measuring station, match the trial clipboard roster (8 subjects, 8 unique strains), log your diagnosis.
2. **Find and consume the cure** — split your strain code into elements on the full 118-element periodic table (all strains are 2-element constructs, e.g. `2611 → Fe·Na`), examine those element capsules under the microscope, count the glowing cells to build the 4-digit fridge code, unlock the cure fridge, drink **your** cure.
3. **Find the access card and escape** — search the lab coat for the locker key. One of the 8 scientist lockers hides the access card. Swipe out at the airlock — cured subjects only.

## Features

- First-person controls (`WASD` + mouse, pointer lock, `E`/click to interact)
- English / 中文 language toggle on the start screen
- Randomized every run: your subject identity, virus strain, fridge code, card locker
- ACES tone mapping, image-based lighting, physical glass materials, soft shadows

## Run it

```bash
npx serve .
```

then open the printed URL, or simply double-click `index.html`.
