# Snake Game

A simple Snake game implemented in Python using Pygame.

## Table of Contents
- [Description](#description)
- [Features](#features)
- [Installation](#installation)
- [How to Play](#how-to-play)
- [Code Structure](#code-structure)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)

## Description
This project is a classic Snake game where the player controls a snake that moves in four directions and grows in size when it eats food. The game ends when the snake collides with itself.

## Features
- Classic Snake gameplay
- Grid-based movement
- Food generation at random positions
- Score tracking
- Wall wrapping (snake reappears on the opposite side)

## Installation
### Prerequisites
Ensure you have Python installed on your system. You also need Pygame and Tkinter.

### Steps
1. Clone the repository:
   ```bash
   git clone
   ```
2. Navigate to the project directory:
   ```bash
   cd snake-game
   ```
3. Install dependencies:
   ```bash
   pip install pygame
   ```
4. Run the game:
   ```bash
   python snake.py
   ```

## How to Play
- Use the arrow keys to move the snake:
  - **Left Arrow**: Move left
  - **Right Arrow**: Move right
  - **Up Arrow**: Move up
  - **Down Arrow**: Move down
- Eat the green cubes (food) to grow the snake.
- Avoid colliding with the snake's body.
- If you collide, the game displays a message box and restarts.

## Code Structure
- `snake.py` - Main script containing the game logic.
- `cube` class - Handles individual cube elements, including the snake's body and food.
- `snake` class - Manages snake movement, growth, and collisions.
- `randomSnack()` - Generates food at a random location.
- `drawGrid()` - Draws the game grid.
- `message_box()` - Displays a game-over message.

