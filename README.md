# Flappy Bird

A browser-based Flappy Bird game built with HTML5 Canvas, CSS, and vanilla JavaScript. Play as a bird navigating through pipes, now with a special Phoenix mode!

🔗 **Live Demo:** [Play on GitHub Pages](https://wannjj.github.io/Flappy-Bird/)

## Features

- **Classic Flappy Bird gameplay** — dodge pipes and aim for the highest score
- **Multiple input methods** — play with keyboard, mouse, or touch
- **Phoenix Mode** — unlock a fiery phoenix skin by toggling a single constant
- **Pixel-perfect sprite rendering** using HTML5 Canvas
- **Sound effects** for jumps, scoring, and collisions
- **Responsive design** — works on desktop and mobile devices

## Controls

| Input                   | Action      |
| ----------------------- | ----------- |
| `Spacebar`              | Jump / Flap |
| `Mouse Click`           | Jump / Flap |
| `Touch` (Mobile/Tablet) | Jump / Flap |

## Phoenix Mode

Want to play as a legendary phoenix instead of the regular bird?

1. Open the main game file (e.g., `index.html` or your JS source)
2. Go to **line 46** and find:
   ```javascript
   const isPhoenix = false;
   ```
3. Change it to:
   ```javascript
   const isPhoenix = true;
   ```
4. Save and refresh the page — the phoenix sprite will replace the default bird!

## Tech Stack

- **HTML5** — Structure
- **CSS3** — Styling
- **JavaScript (ES6+)** — Game logic, physics, and rendering
- **HTML5 Canvas API** — 2D sprite rendering and animation

## Project Structure

```
Flappy-Bird/
├── index.html          # Main entry point
├── sprites/            # Game assets (PNG images)
│   ├── bird.png
│   ├── phoenix.png
│   ├── pipe.png
│   ├── background.png
│   └── ...
└── Sounds/             # Audio assets
    ├── FlappyBird_point.wav
    └── FlappyBird_hit.wav
```

## Getting Started

To run the game locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/wannjj/Flappy-Bird.git
   ```
2. Navigate to the project folder:
   ```bash
   cd Flappy-Bird
   ```
3. Open `index.html` in your browser:

   ```bash
   # On macOS
   open index.html

   # On Windows
   start index.html

   # Or simply double-click the file
   ```

> No build tools or dependencies required — it runs entirely in the browser!

## Recent Updates

- Refactored keyboard input handling for cleaner code
- Added mouse click support
- Applied consistent code formatting with Prettier
- Removed duplicate entry files
- Tweaked game constants (gravity, jump strength, pipe spawn rate) for smoother gameplay

## Credits

- **Sprites** — Bird, pipe, and background images sourced from the web
- **Sound Effects** — Audio files collected from online resources
- **Original Concept** — Flappy Bird by Dong Nguyen

## License

This project is for educational and personal use. All original game concepts and trademarks belong to their respective owners.
