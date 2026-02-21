# 🦈 Sharky

Sharky is a fast-paced underwater browser game built with vanilla JavaScript and HTML5 Canvas. Collect coins, unlock poison bubbles, defeat sea enemies, and take down the final boss.

## Live Demo

[Play Sharky](https://iamhitya.github.io/sharky/)

## Gameplay

### Controls

- **Arrow Keys** or **WASD** — Move
- **Space** or **Arrow Up** — Swim up / Jump
- **X** — Shoot bubble
- **Y** — Fin slap

### Goal

- Explore the level
- Collect **20 coins**
- Collect all poison bottles to unlock poisonous bubbles
- Defeat enemies and the final boss

## Features

- Smooth character movement and physics
- Bubble and melee combat
- Multiple enemy types (regular/electric jellyfish, pufferfish, boss)
- Parallax scrolling background
- Sound and music toggles
- Win/lose screens and restart flow

## Tech Stack

- **JavaScript (ES6 modules)**
- **HTML5 Canvas**
- **CSS3**
- **GSAP** for animations

## Run Locally

1. Clone your repository and enter the project folder.
2. Start a local static server:

   ```bash
   python -m http.server 5500
   ```

3. Open:

   ```
   http://localhost:5500
   ```

## Project Structure

```text
.
├── index.html
├── script.js
├── style.css
├── assets/
└── game/
    ├── entities/
    └── utils/
```

## License

This project is licensed under the MIT License.