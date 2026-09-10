# SUBJECT 07 — Three.js Lab Escape 🧬

You wake as **test subject 07**, infected with an unknown virus. Find the cure, consume it — and escape.

A single-file [Three.js](https://threejs.org/) escape-room game. No build step: just open `index.html` (internet required for the Three.js CDN).

## The 3 steps

1. **Identify the virus** — take your height + weight at the measuring station, match the trial clipboard roster (8 subjects, 8 unique strains), log your diagnosis.
2. **Find and consume the cure** — split your strain into elements, look up atomic numbers on the full 118-element periodic table, join them into the 4-digit fridge code (e.g. `NaCO → 11·6·8 → 1168`), unlock the cure fridge, drink **your** vial.
3. **Find the access card and escape** — solve the riddle on each of the 8 scientist lockers (math, jokes, science — including Chinese homophone puns 谐音梗). One hides the access card. Swipe out at the airlock — cured subjects only.

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
