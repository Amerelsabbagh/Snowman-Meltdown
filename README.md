# Snowman Meltdown

Snowman Meltdown is a Python terminal game where the player tries to guess a hidden word before the snowman completely melts. It is an enhanced, modular implementation of the classic hangman-style game, split into dedicated files for ASCII art, game logic, and the main entry point.[page:0]

## Overview

The game runs in the terminal and guides the player through repeated guesses, updating the snowman ASCII art and game state after each attempt. It is designed as a learning project to practice clean Python structuring, functions, and separation of responsibilities between modules.[page:0]

## Features

- Word-guessing gameplay in the command line.[page:0]
- Progressive snowman ASCII art showing the game state.[page:0]
- Separate `game_logic.py` for core logic.[page:0]
- `ascii_art.py` for visuals and text output.[page:0]
- `snowman.py` as the main script to start the game.[page:0]

## Project Structure

```text
Snowman-Meltdown/
├── ascii_art.py
├── game_logic.py
├── snowman.py
└── README.md
```

## Tech Stack

- Python 3.x[page:0]

## Getting Started

### Prerequisites

- Python 3.x installed on your machine.

### Run locally

```bash
git clone https://github.com/Amerelsabbagh/Snowman-Meltdown.git
cd Snowman-Meltdown
python snowman.py
```

Follow the prompts in your terminal to play the game.

## Learning Focus

This project is useful for practicing:

- Structuring a small Python project across multiple files.
- Implementing game state and input loops.
- Working with simple ASCII art and terminal output.
- Refactoring code to separate logic from presentation.[page:0]

## Possible Improvements

- Add a word list file and difficulty levels.
- Add tests for the game logic functions.
- Add input validation and error messages.
- Support replaying multiple rounds without restarting the script.

## Status

Learning project demonstrating Python fundamentals and simple game design in a console environment.
