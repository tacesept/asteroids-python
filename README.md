# Asteroids

A simple Python implementation of the classic Asteroids arcade game built with `pygame`.

## Overview

- Move a player ship around the screen.
- Avoid colliding with asteroids.
- Destroy asteroids with shots to split them into smaller pieces.
- The game ends when the player collides with an asteroid.

## Requirements

- Python 3.13+
- `pygame==2.6.1`

## Installation

1. Clone the repository:

```bash
git clone <repo-url>
cd asteroids
```

2. Create a virtual environment:

```bash
python -m venv .venv
source .venv/bin/activate
```

3. Install dependencies:

```bash
python -m pip install -r requirements.txt
```

If you do not have a `requirements.txt`, install directly:

```bash
python -m pip install pygame==2.6.1
```

## Run the game

From the repository root:

```bash
python main.py
```

```bash
python main.py
```

## Project structure

- `main.py` — game loop and object collision logic
- `asteroid.py` — asteroid behavior and collision handling
- `asteroidfield.py` — asteroid spawning and field management
- `player.py` — player ship movement and controls
- `shot.py` — shot firing and update logic
- `constants.py` — game settings and screen size constants
- `logger.py` — logging game state and events
- `circleshape.py` — collision shape utilities

## Notes

- The game currently uses `pygame` for rendering and input.
- When an asteroid is shot, it splits into smaller asteroids.
- The player loses when colliding with any asteroid.

## License

This project is provided as-is with no specific license.
