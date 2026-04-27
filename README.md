# Asteroids

A small arcade-style Asteroids clone built with Python and Pygame.

## Requirements

- Homebrew
- `uv`

## Setup

### Option 1: With virtual environment activation

```bash
brew install uv
uv sync
source .venv/bin/activate
uv run main.py
```

### Option 2: Without virtual environment activation

```bash
brew install uv
uv sync
uv run main.py
```

## Controls

- `W`: move forward
- `S`: move backward
- `A`: rotate left
- `D`: rotate right
- `Space`: shoot

## Gameplay

- Avoid colliding with asteroids.
- Shoot asteroids to split larger ones into smaller pieces.
- The game ends when your ship is hit.
