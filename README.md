# Snake-game-

This is a simple Snake Game built using the pygame library. The player controls a snake that moves across the screen, collecting apples to grow longer while avoiding collisions with its own body or the screen boundaries.

Features

Dynamic Gameplay: The snake grows longer each time it eats an apple.
Collision Handling: The game resets if the snake hits the wall or itself.
Random Apple Placement: Apples are randomly placed on the screen, avoiding the snake's current position.
Customizable Parameters: Modify game constants like speed, screen size, and block size.

How to Play

Run the Python script (snake_game.py) using Python 3.
Control the snake using the arrow keys:
Up Arrow: Move up
Down Arrow: Move down
Left Arrow: Move left
Right Arrow: Move right
The goal is to collect as many apples as possible without colliding with walls or yourself.
When the game resets, the snake starts anew with a score of zero.

Game Details

Constants:
Screen Size: 800 x 600 pixels (modifiable via WIDTH and HEIGHT constants).
Block Size: 20 pixels (modifiable via BLOCK_SIZE).
Frame Rate: 10 FPS (modifiable via FPS).
Colors:
Background: Black
Snake: Green
Apple: Red

Code Overview

Key Components:
Snake Initialization:
The snake is represented as a list of tuples where each tuple corresponds to a block in the snake's body.
Apple Placement:
Apples are generated randomly on the screen, ensuring they do not overlap with the snake's current position.
Movement & Controls:
Arrow keys are used to control the snake's direction, ensuring the snake cannot reverse into itself.
Collision Detection:
Checks for collisions with walls or the snake's own body.
Game Reset:
Resets the game when a collision is detected.

Customization

Game Speed: Adjust the FPS variable to change the snake's speed.
Screen Size: Modify the WIDTH and HEIGHT constants for a larger or smaller play area.
Snake and Apple Size: Change the BLOCK_SIZE constant to increase or decrease the size of the snake and apples.

License

This project is open-source and can be freely used or modified for educational or personal purposes.

Enjoy playing the classic Snake Game! 🐍






