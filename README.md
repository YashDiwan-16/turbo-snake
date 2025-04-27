# Turbo Snake Game

A classic Snake game implementation in C++ that runs in the Windows command prompt.

## Description

Turbo Snake is a console-based implementation of the classic Snake game where players control a snake that grows in length as it consumes food. The game ends when the snake collides with itself.

## Features

- Console-based gameplay with simple controls
- Score tracking
- Increasing difficulty as the snake grows longer
- Random food spawning

## Requirements

- Windows operating system
- C++ compiler with support for:
  - `<windows.h>` for console manipulation
  - `<conio.h>` for keyboard input handling

## How to Play

1. **Compile the game**: Compile the `SnakeGame.cpp` file using your preferred C++ compiler.
2. **Run the executable**: Execute the compiled file to start the game.
3. **Controls**:
   - `W` or `w`: Move snake UP
   - `A` or `a`: Move snake LEFT
   - `S` or `s`: Move snake DOWN
   - `D` or `d`: Move snake RIGHT

## Game Rules

- The snake constantly moves in the direction it is heading
- Direct the snake to eat the food (displayed as 'o')
- Each time the snake eats food, it grows longer and your score increases
- The game ends when the snake collides with itself
- Try to achieve the highest score possible!

## Code Structure

- `Point` struct: Manages coordinates in the 2D console space
- `Snake` class: Handles snake movement, growth, and collision detection
- `Board` class: Controls game rendering, food spawning, and input processing
- Main loop: Updates game state and renders at fixed intervals

## Future Improvements

- Add walls/boundaries
- Implement different difficulty levels
- Add high score tracking
- Include special power-ups
- Add colors and improved visuals

## Author

[Your Name]

## License

This project is open source and available under the [MIT License](LICENSE).