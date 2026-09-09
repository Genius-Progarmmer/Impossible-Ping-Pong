# Ping Pong Game

A lightweight Ping Pong game developed in Python using the Pygame library. The project focuses on basic game development concepts such as movement, collision detection, scoring, sound effects, and game states.

## Description

This project is a simple Ping Pong game where the player controls a paddle and tries to keep the ball from reaching the bottom of the screen.

The game includes scoring, collision detection, sound effects, randomized background colors, and a game-over system.

## Technologies

* Python
* Pygame

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

## Challenges

One of the main challenges of this project was implementing collision detection between the ball and paddle while keeping the ball movement consistent.

Another challenge was creating the game-over and restart system and connecting the different game states together.

## What I Learned

Through this project, I learned how to:

* Create a game using Pygame
* Handle keyboard and mouse input
* Detect collisions between objects
* Create scoring systems
* Work with game states
* Add sound effects
* Use random values in games
* Manage game assets

## Status

Completed

## Future Improvements

* Add multiple difficulty levels
* Add an AI opponent
* Add more sound effects
* Add a start menu
* Add improved visual effects
* Add high-score saving

## Project Preview

The image below shows the game in action.

![Ping Pong Game Preview](pingpong.png)

## Installation

Clone the repository:

```bash
git clone https://github.com/Genius-Progarmmer/Impossible-Ping-Pong.git
```

Move into the project directory:

```bash
cd Impossible-Ping-Pong
```

Install Pygame:

```bash
pip install pygame
```

## How to Run

Run the game with:

```bash
python ping_pong.py
```

Make sure the `sounds_and_pic` folder is in the same directory as the Python file.

## Project Structure

```text
Impossible-Ping-Pong/
│
├── ping_pong.py
│
└── sounds_and_pic/
    ├── Ping-pongeffect.mp3
    ├── pingpong.png
    ├── tennis_ball.png
    └── border.jpg
```

## Author

**Genius-Progarmmer**

GitHub: https://github.com/Genius-Progarmmer
