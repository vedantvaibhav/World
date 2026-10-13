# Afterfield

A night walk through endless grass. Light falls from the sky in rings, and where a ring passes, flowers grow and stay.

Built with three.js and WebGL. No build step. Open `index.html` through any static server.

## Controls

- `W` `A` `S` `D` walk
- `Shift` run
- `C` switch camera
- Mouse to look (click the field to lock the pointer, `Esc` to let go)
- Touch: left thumb walks, right thumb looks

## Run it locally

```
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Deploy

It is a static site. Point Vercel, Netlify or GitHub Pages at the repo root.

## What is in here

- `index.html` holds everything: grass, terrain, sky, planet, waves, flowers, sound and controls.
- `astronaut.glb` is the rigged character with idle, walk and run clips. It is X Bot from the three.js examples (originally from Mixamo), dressed up as an astronaut in code.

Grass, terrain, sky, the planet, the flowers and all sound are generated in code. No textures or audio files.
