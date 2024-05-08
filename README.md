# SnakeGame

## Description
This Python application is a recreation of the classic Snake game using the tkinter library for graphics and user interface. The player controls a snake that moves around a grid, eating food (obstacles) to grow longer. The game ends if the snake collides with itself. The player can control the snake's direction using arrow keys or buttons provided in the UI.

## Features
- Snake movement controlled by arrow keys or buttons.
- Score tracking to keep track of the number of obstacles eaten.
- High score tracking to keep track of the maximum score achieved.
- Start, stop, and quit buttons for user convenience.

## Requirements
- tkinter library (usually comes pre-installed with Python)

## Usage
1. Run the Python script (`snake_game.py`).
2. Use the arrow keys or the start, stop, and quit buttons to control the snake.
3. Eat the obstacles to grow longer and increase the score.
4. Avoid colliding with the boundaries of the grid or the snake's own body.
5. The game ends when the snake collides, and the score is updated.
6. Close the application by clicking the quit button or closing the window.

## Important Notes
- Ensure that you have a working Python environment with the tkinter library installed.
- The game grid is defined by constants `GRADUATION`, `PIXEL`, `STEP`, `WD`, and `HT`. You can adjust these constants to change the size of the game grid.
- The snake's speed and obstacle spawn rate are controlled by the `REFRESH_TIME` constant.
- The game tracks the current score and the highest score achieved during gameplay.
- The snake's color, background color, and obstacle color can be adjusted by modifying the respective color constants (`BG_COLOR`, `OB_COLOR`, `SN_COLOR`).

## Files
- `snake_game.py`: The main Python script.
- `README.md`: This file providing information about the game.

## Credits
- Inspired by various tutorials and resources on building Snake games in Python using different graphics libraries.
- Original code from [Ganesh Kavhar's GitHub](https://github.com/ganeshkavhar/snake-game-in-python-by-ganesh-kavhar).
