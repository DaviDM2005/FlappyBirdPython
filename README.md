# Flappy Bird Game using Pygame

This Python script implements a simple Flappy Bird game using the Pygame library. The game includes a flappy bird that the player can control by clicking the mouse or pressing a key to avoid hitting pipes. The objective is to navigate through the pipes and score as many points as possible.

## Game Features

- The player controls a flappy bird that can jump when the mouse is clicked or a key is pressed.
- Pipes appear on the screen, and the player must navigate the bird through the gap between them.
- The game keeps track of the player's score based on the number of pipes successfully passed.
- The game ends if the bird collides with the pipes or goes out of bounds.

## Game Components

- `FlappyBird` class: Manages the game loop, bird movement, pipe generation, collision detection, and scoring.
- Graphics: Utilizes images for the background, bird, and pipes to create a visual representation of the game.

## Controls

- Click the mouse or press any key to make the bird jump.
- The game automatically restarts after a collision or when the bird goes out of bounds.

## Dependencies

- Pygame: Ensure that you have the Pygame library installed (`pip install pygame`) before running the script.

## Usage

1. Run the script using a Python interpreter: `python flappy_bird.py`.
2. Control the bird by clicking the mouse or pressing a key to navigate through the pipes.
3. Try to score as many points as possible by passing through the gaps in the pipes.
4. The game ends if the bird collides with the pipes or goes out of bounds.
5. Close the game window to exit.

Feel free to modify and extend the game to add more features or customize the gameplay!
