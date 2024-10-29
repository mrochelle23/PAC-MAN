# Pac-Man Game Project

Welcome to the Pac-Man Game Project! This multi-level browser-based game is inspired by the classic arcade game Pac-Man, where the player navigates a maze, collects points, and avoids ghosts.

## Table of Contents
- [Features](#features)
- [Setup Instructions](#setup-instructions)
- [Game Instructions](#game-instructions)
- [File Structure](#file-structure)
- [Customizations](#customizations)
- [Credits](#credits)

## Features
- **Four Levels:** The game includes `game.html` (Level 1), `game2.html` (Level 2), `game3.html` (Level 3), and `ultimate.html` (Level 4), each with unique mazes and challenges.
- **Score Tracking:** Points are awarded for collecting dots and power-pellets, with a score displayed at the top.
- **Ghosts with AI:** Ghosts move around the maze, and if Pac-Man encounters a ghost, the game is over. When a power-pellet is eaten, ghosts become "scared" for a few seconds, allowing Pac-Man to eat them.
- **Sound Effects:** Game sounds for movement, eating dots, power-ups, ghost capture, and game win/loss.
- **Responsive Gameplay:** Customizable controls for an enhanced gameplay experience.

## Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/mrochelle23/Sprint.git
   cd Sprint
   ```

2. **File Requirements**:
   - Ensure all files are in the correct structure, especially the JavaScript files (`game.js`, `game2.js`, `game3.js`, `ultimate.js`) and HTML files (`game.html`, `game2.html`, `game3.html`, `ultimate.html`).
   - Add sound files in a folder named `sounds` (e.g., `game_start.wav`, `sounds_waka.wav`, `pill.wav`, `sounds_eat_ghost.wav`, `sounds_gameOver.wav`, `sounds_gameWin.wav`).

3. **Run the Game**:
   - Open any of the HTML files (`game.html`, `game2.html`, `game3.html`, or `ultimate.html`) in a browser to play different levels.

## Game Instructions

1. **Objective**:
   - Navigate Pac-Man through the maze to eat all pac-dots and power-pellets while avoiding ghosts.
   - Eating a power-pellet allows Pac-Man to eat ghosts for a limited time, adding bonus points.

2. **Controls**:
   - Use the arrow keys to move Pac-Man around the maze:
     - **Up Arrow**: Move Up
     - **Down Arrow**: Move Down
     - **Left Arrow**: Move Left
     - **Right Arrow**: Move Right

3. **Scoring**:
   - **Pac-dot**: +10 points
   - **Power-pellet**: +50 points and temporarily “scares” ghosts.
   - **Scared Ghosts**: +100 points per ghost eaten.

4. **Game Over**:
   - The game ends if Pac-Man encounters a non-scared ghost.
   - A win is achieved upon eating all pac-dots and power-pellets in the maze.

## File Structure

```
.
├── sounds/                     # Sound effects for gameplay
│   ├── game_start.wav
│   ├── sounds_waka.wav
│   ├── pill.wav
│   ├── sounds_eat_ghost.wav
│   ├── sounds_gameOver.wav
│   └── sounds_gameWin.wav
├── game.html                   # Level 1 HTML
├── game2.html                  # Level 2 HTML
├── game3.html                  # Level 3 HTML
├── ultimate.html               # Ultimate level HTML
├── game.js                     # Level 1 JavaScript
├── game2.js                    # Level 2 JavaScript
├── game3.js                    # Level 3 JavaScript
├── ultimate.js                 # Ultimate level JavaScript
├── game.css                    # Styling for all game levels
└── README.md                   # Project documentation
```

## Customizations

- **Levels**: Modify `layout` arrays in the `game.js`, `game2.js`, `game3.js`, and `ultimate.js` files to change the maze layout.
- **Sounds**: Update sound effects by replacing files in the `sounds/` folder.
- **Ghost Speed**: Adjust ghost speed by modifying the `speed` attribute in each level's `Ghost` constructor.

## Credits
This project is based on the classic Pac-Man game and developed by Mikhai Rochelle as part of a multi-level game series in JavaScript. Special thanks to the original creators and inspiration sources for gameplay and design elements.
