# 🔫 Shooting Game

## Overview
The Shooting Game is an exciting, web-based arcade game created by Roshan Kumar Prajapati. Built with HTML, CSS, and JavaScript, it challenges players to control a shooter using mouse or touch input to fire bullets at red targets falling from the top of the screen. The game features three difficulty levels, score tracking, and a game over state when a target reaches the bottom. It includes a dark-themed canvas, responsive controls, and is optimized for both desktop and mobile devices, offering a thrilling gaming experience.

## Features
- **Gameplay** 🎮:
  - Players control a white shooter at the bottom of the screen, moving it with mouse or touch input.
  - Yellow bullets are fired by clicking or tapping to hit red targets that spawn at the top.
  - Targets have random sizes (20–60 pixels) and fall at speeds based on difficulty.
- **Difficulty Levels** 🎚️:
  - **Easy**: Target speed of 1.5 pixels/frame, spawn every 1.5 seconds.
  - **Medium**: Target speed of 3 pixels/frame, spawn every 1 second.
  - **Hard**: Target speed of 5 pixels/frame, spawn every 0.7 seconds.
- **Scoring** 📊:
  - Each hit on a target awards 10 points, displayed in the top-left corner.
- **Game Over** 🏁:
  - Game ends if a target reaches the bottom of the canvas, displaying "Game Over" in red.
  - A "Restart Game" button appears to reset the game.
- **Controls** 🖱️📱:
  - **Desktop**: Move shooter with mouse, shoot with left-click.
  - **Mobile**: Move shooter with touch drag, shoot with tap.
  - Start and restart buttons, plus a difficulty selector, for game control.
- **Visuals** 🎨:
  - Dark canvas background (`#1e1e1e`) with white shooter, yellow bullets, and red targets.
  - Simple, high-contrast design for clarity during fast gameplay.
- **Responsive Design** 📱:
  - Canvas resizes dynamically to fit the window size, ensuring compatibility across devices.

## Tech Stack
- **HTML5**: Structure of the game, including canvas and control elements.
- **CSS3**: Inline styles for canvas, buttons, and difficulty selector, with a dark theme and hover effects.
- **JavaScript**: Game logic, including shooter movement, bullet firing, target spawning, collision detection, and rendering (inline script in `index.html`).
- **Canvas API**: Used for rendering the shooter, bullets, targets, score, and game over text.

## Project Structure
```
shooting-game/
├── index.html         # Main HTML file
├── LICENSE.md        # MIT License
└── README.md         # This file
```

## Prerequisites
- A modern web browser (e.g., Chrome, Firefox, Edge) with Canvas and JavaScript support.
- A code editor (e.g., VS Code) for customization.

## Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/The-Roshan/shooting-game.git
cd shooting-game
```

### 2. Open the Website
- Open `index.html` in a web browser:
  ```bash
  open index.html  # macOS
  start index.html  # Windows
  ```
- Alternatively, use a local development server (e.g., VS Code Live Server) for better performance.

### 3. Customize (Optional)
- Edit inline CSS in `index.html` to modify colors, control styles, or add animations.
- Update inline JavaScript in `index.html` to enhance gameplay (e.g., add sound effects, new target types, or power-ups).
- Modify `index.html` to add UI elements like a pause button, high score display, or background effects.

## Usage
1. **Select Difficulty** 🎚️: Choose Easy, Medium, or Hard from the dropdown menu.
2. **Start Game** 🚀: Click the "Start Game" button to begin.
3. **Control Shooter** 🖱️📱: Move the shooter left/right using mouse or touch; click or tap to shoot bullets.
4. **Hit Targets** 🔫: Aim at red targets to score 10 points per hit.
5. **Score Points** 📊: Track your score in the top-left corner.
6. **Game Over** 🏁: If a target reaches the bottom, see "Game Over" and use the "Restart Game" button to play again.
7. **Responsive** 📱: Play on desktop or mobile for a consistent experience.

## Deployment
- **Static Hosting**:
  1. Upload `index.html` to a hosting service (e.g., GitHub Pages, Netlify, Vercel).
  2. Configure the service to serve `index.html` as the entry point.
- **GitHub Pages Example**:
  1. Push the repository to GitHub.
  2. Enable GitHub Pages in the repository settings, selecting the `main` branch.
  3. Access the site at `https://the-roshan.github.io/shooting-game`.
- **Netlify Example**:
  1. Drag the project folder into Netlify’s dashboard.
  2. Deploy and use the provided URL.
- **Local Server**:
  ```bash
  python -m http.server 8000
  ```
  Visit `http://localhost:8000`.

## Notes
- **JavaScript Logic**: The inline script in `index.html` handles:
  - Game initialization with shooter, bullets, targets, and score.
  - Difficulty settings for target speed and spawn rate.
  - Mouse and touch controls for shooter movement and shooting.
  - Collision detection between bullets and targets.
  - Target spawning at regular intervals based on difficulty.
  - Game loop using `requestAnimationFrame` for smooth animation.
  - Game over state with restart functionality.
- **Styling**: Inline CSS defines a dark theme, control positioning, and hover effects. Consider moving styles to a separate `styles.css` file for maintainability.
- **Enhancements**: Consider adding:
  - Sound effects for shooting, hits, or game over.
  - High score storage using `localStorage`.
  - Different target behaviors (e.g., side-to-side movement).
  - Power-ups or special bullets for varied gameplay.
  - A background animation (e.g., particles) to align with your other projects.
- **SEO**: Add meta tags in `<head>` (e.g., `description`, `keywords`) for better visibility, e.g., "Shooting game by Roshan Kumar Prajapati".
- **License**: Include the MIT License in `LICENSE.md` to clarify usage terms (as provided previously).
- **Performance**: The game is lightweight but could benefit from sprite-based graphics or optimized target spawning for high-end difficulty.

## License
This project is licensed under the MIT License. See `LICENSE.md` for details.

## Contributing
1. Fork the repository.
2. Create a feature branch: `git checkout -b feature/your-feature`.
3. Commit changes: `git commit -m "Add your feature"`.
4. Push to the branch: `git push origin feature/your-feature`.
5. Open a pull request.

## Acknowledgments
- Built with HTML, CSS, and JavaScript for a thrilling arcade shooting experience.
- Inspired by classic shooting gallery games with modern web interactivity.
- Created by Roshan Kumar Prajapati.

## Contact
For questions or feedback, contact Roshan Kumar Prajapati:
- 📧 Email: roshanjsr5555@gmail.com
- 📞 Phone: +91 7061126213
- 🌐 GitHub: [The-Roshan](https://github.com/The-Roshan)
