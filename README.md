# CasinoGame (We Need A Name)

2D top-down casino roguelike built in Python with Pygame.
Group project for a Python programming course

## Requirements

- Python 3.13
- Git

## Setup

1. Clone the repository
2. Create and activate a virtual environment
3. Run "pip install -r requirements.txt"
4. Check that Pygame works with "python -m pygame.examples.aliens"

## Workflow

Never commit directly to main
Create a branch for each task

## Project Structure

- `core/` — engine: scenes, run state, profile, saving, animations
- `games/` — casino games, all inheriting from `CasinoGame`
- `charms/` — charm base class and charms
- `scenes/` — menu, lobby, shop, game over
- `tests/` — pytest tests
- `assets/` — images, sounds, fonts
