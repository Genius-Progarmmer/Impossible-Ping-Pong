# Ping Pong Game

A lightweight Ping Pong game developed in Python using the Pygame library. The project focuses on basic game development concepts such as movement, collision detection, scoring, sound effects, and game states.

## Features

* Paddle controlled with the keyboard
* Automatic ball movement
* Horizontal wall bouncing
* Paddle collision detection
* Dynamic scoring system
* Randomized background colors
* Paddle-hit sound effects
* Game-over state
* Space-to-restart functionality
* Random ball spawn position on restart
* Paddle boundary restrictions

## Controls

* **Left Arrow** — Move the paddle left
* **Right Arrow** — Move the paddle right
* **Space** — Restart the game after losing
* **Mouse Click** — Randomize the background color

## Requirements

Make sure Python 3.x is installed.

Install Pygame using:

```bash
pip install pygame
```

## Running the Game

Run the Python file:

```bash
python ping_pong.py
```

Make sure the `sounds_and_pic` folder is located in the same directory as the Python file.

## Assets

The game uses the following assets:

```text
sounds_and_pic/
├── Ping-pongeffect.mp3
├── pingpong.png
├── tennis_ball.png
└── border.jpg
```

## Gameplay

The ball continuously moves around the game area and bounces off the boundaries.

The player controls the paddle using the Left and Right Arrow keys. Successfully hitting the ball increases the score and triggers a sound effect.

Each successful paddle collision also generates a new random RGB value for the game's background.

If the player misses the ball and it reaches the bottom of the game area, the game enters the game-over state. Pressing Space resets the score and launches the ball from a new random position at the top of the screen.

## Technologies Used

**Python**
Used for the game's logic, controls, scoring, and state management.

**Pygame**
Used for graphics, input handling, collision detection, audio, and the game loop.

## Project Structure

```text
Ping-Pong/
│
├── ping_pong.py
│
└── sounds_and_pic/
    ├── Ping-pongeffect.mp3
    ├── pingpong.png
    ├── tennis_ball.png
    └── border.jpg
```