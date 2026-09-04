# CosmoBlitz

CosmoBlitz is a retro browser-based space shooter built with the HTML Canvas API. Pilot a starship through escalating enemy phases, survive boss encounters, and defend the galaxy while chasing a persistent high score.

## Features

- Full-screen canvas gameplay
- Multiple combat phases and boss encounters
- Mouse and touch movement controls
- Animated starfields, sprites, lasers, and visual effects
- Background music and sound effects with mute control
- High scores saved in browser local storage
- Responsive layout for desktop and mobile browsers
- Installable web-app manifest

## Built with

- HTML5
- CSS3
- Vanilla JavaScript
- Canvas API
- Web Audio and browser local storage

## Run locally

No package installation or build step is required.

```bash
git clone https://github.com/CoffeeDev-Err/CosmoBlitz.git
cd CosmoBlitz
python -m http.server 8000
```

Open `http://localhost:8000` in a browser. Windows users with Python installed can also run `start-local-server.bat`.

## Controls

- Move the ship with the mouse on desktop.
- Drag on the game area on a touch device.
- Use the sound button to mute or restore game audio.

## Project structure

```text
CosmoBlitz/
├── assets/          # Game images and audio
├── game.js          # Game state, rendering, input, and combat logic
├── index.html       # Screens, HUD, and canvas entry point
├── manifest.json    # Installable web-app metadata
└── style.css        # Retro interface and responsive styling
```

## Browser notes

Modern browsers block autoplay until the player interacts with the page. Start the game or touch the canvas to enable audio playback.

