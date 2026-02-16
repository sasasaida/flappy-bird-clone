# Flappy Bird Clone

A simple browser-based Flappy Bird clone game built with Phaser 3 framework.

## Description

This is a lightweight implementation of the classic Flappy Bird game that runs directly in your web browser. The game features a bird that the player must navigate through columns (obstacles) without crashing into them or the ground. The objective is to reach the end of the level by skillfully controlling the bird's flight.

## Features

- Simple and intuitive gameplay
- Responsive controls using keyboard input
- Physics-based movement with gravity
- Collision detection with obstacles and ground
- Win/lose conditions
- Visual feedback with game state messages

## Technology Stack

- **Phaser 3.55.2** - A fast, free, and fun open source HTML5 game framework
- **HTML5** - Markup structure
- **JavaScript** - Game logic and interactivity

## How to Play

1. Open `index.html` in a web browser
2. Press the **Spacebar** to start the game
3. Press the **Up Arrow (↑)** key repeatedly to keep the bird airborne
4. Navigate through the columns without hitting them
5. Avoid crashing into the ground
6. Reach the end of the level to win!

## Installation & Setup

No installation required! Simply clone the repository and open the HTML file:

```bash
git clone https://github.com/sasasaida/flappy-bird-clone.git
cd flappy-bird-clone
```

Then open `index.html` in your favorite web browser.

Alternatively, you can use a local development server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js
npx http-server
```

Then navigate to `http://localhost:8000` in your browser.

## Project Structure

```
flappy-bird-clone/
├── index.html      # Main HTML file
├── app.js          # Game logic and Phaser configuration
├── assets/         # Game assets
│   ├── background.png
│   ├── bird.png
│   ├── column.png
│   └── road.png
└── README.md       # This file
```

## Game Controls

| Key | Action |
|-----|--------|
| Spacebar | Start the game |
| Up Arrow (↑) | Flap wings / Stay airborne |

## Game Mechanics

- The bird is affected by gravity and will fall if not controlled
- Press the up arrow key to make the bird fly upward
- The bird moves forward automatically once the game starts
- Collision with columns or ground results in game over
- Successfully reaching the right edge of the game area results in a win

## License

This is an educational project and a clone of the original Flappy Bird game.

## Credits

Built using the Phaser 3 game framework.
