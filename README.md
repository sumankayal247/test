# Flappy Bird 3D

A small Flappy Bird-inspired game built with [Three.js](https://threejs.org/). No build step or installation required.

## Play

**[Play Flappy Bird 3D](https://sumankayal247.github.io/test/)**

## Features

- Detailed 3D house sparrow with layered plumage, tail feathers, facial markings, legs and continuously animated wings
- Layered city skyline with rooftop details and illuminated windows
- Smooth day, sunset and night cycle with a sun, moon and stars
- Synthesized flap, point and crash sound effects (no external audio files)
- Rounded cylindrical 3D pipe obstacles with varied starting heights and spacing
- Score counter, pipe obstacles and responsive touch controls

## Controls

- **Space / Up Arrow** — flap
- **Mouse click / Touch** — flap
- Pass through the pipes to earn points and avoid collisions.

## Run locally

Open `index.html` through a local web server (ES modules require HTTP):

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Deployment

Every push to `main` automatically deploys the site to GitHub Pages using the workflow in `.github/workflows/deploy.yml`.
