# Snake Game

## Overview
This is a Snake Game implemented using the Turtle module in Python. The player controls a snake that moves around the screen eating food pellets to grow longer. The game ends if the snake collides with itself or the screen boundaries.

## Requirements
- Python 3.x
- Turtle module

## Usage
1. Run the script.
2. Use the arrow keys to control the direction of the snake: Up, Down, Left, Right.
3. The snake will move continuously, and the player's goal is to eat as much food as possible without colliding with itself or the screen boundaries.
4. Each time the snake eats food, it grows longer, and the player's score increases.
5. If the snake collides with itself or the screen boundaries, the game ends, and the score resets.

## Components
- `Snake`: Represents the snake object and its movements.
- `Food`: Represents the food pellet for the snake to eat.
- `Scoreboard`: Displays the player's score and manages game state.

## Features
- Smooth movement animation using Turtle's screen.update() and time.sleep().
- Collision detection with food, screen boundaries, and the snake's own body.
- Score tracking and display using the Scoreboard.

## Note
- Ensure that you have the necessary dependencies installed.
- Adjust the screen dimensions and sleep time in the code to modify the game's difficulty and appearance.

## Contributions
Contributions are welcome! If you find any issues or have suggestions for improvement, feel free to open an issue or create a pull request.
