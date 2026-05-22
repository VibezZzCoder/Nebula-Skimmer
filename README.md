# Nebula Skimmer

A small arcade browser game built with vanilla HTML, CSS, and JavaScript.

Dodge falling asteroids, collect gems, chain evasion combos, grab power-ups, and push for a new high score. The game was designed as a solid foundation for vibecoding practice and continual refinement. 

## Play

[https://VibezZzCoder.github.io/nebula-skimmer/](https://vibezzzcoder.github.io/Nebula-Skimmer/)

## Controls

- Move: `WASD` or arrow keys
- Pause: `Esc`
- Mobile: on-screen joystick and pause button

## Features

- Three difficulty levels: Easy, Medium, and Hard
- Asteroids with multiple sizes, movement styles, and behaviors
- Gems, score popups, combos, and power-ups
- Lives, invincibility frames, particles, screen shake, and synthesized sound effects
- Local high score saved in the browser
- Responsive canvas layout with mobile touch controls
- No build step, no dependencies, no external assets

## Run locally

Open `index.html` directly in a browser, or run a local server:

```bash
python3 -m http.server 8000 --bind 127.0.0.1
```

Then open:

```text
http://127.0.0.1:8000
```

## Project note

This started as a first local test game and is being kept as an experiment for comparing how different free/cheap LLM coding models improve the same small browser game over time.
