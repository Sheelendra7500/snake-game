# Snake Game

A simple Python-based Snake game implementation with basic controls and scoring.

## Description

This is a classic Snake game built using Python and Pygame. Control the snake to eat food, grow longer, and achieve the highest score possible. The game features:

- Simple and intuitive arrow key controls
- Score tracking system
- Snake growth mechanics
- Game over detection on self-collision
- Wrapping borders (snake appears on opposite side)

## Requirements

- Python 3.x
- Pygame library

## Installation

1. Clone this repository:
```bash
git clone https://github.com/Sheelendra7500/snake-game.git
cd snake-game
```

2. Install the required dependencies:
```bash
pip install pygame
```

## How to Run

Run the game using Python:
```bash
python snake_game.py
```

## Controls

- **↑ (Up Arrow)**: Move Up
- **↓ (Down Arrow)**: Move Down
- **← (Left Arrow)**: Move Left
- **→ (Right Arrow)**: Move Right

## Gameplay

- The snake (green) starts in the center of the screen
- Food (red) appears randomly on the grid
- Eat food to grow longer and increase your score by 10 points
- Avoid colliding with your own body
- The game ends when the snake hits itself

## Game Features

- **Grid Size**: 600x400 pixels with 20x20 pixel cells
- **Starting Speed**: 10 FPS (can be adjusted in code)
- **Score Display**: Real-time score shown in the top-left corner

## License

This project is open source and available for educational purposes.
