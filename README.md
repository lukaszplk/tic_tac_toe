# Tic Tac Toe Game

A classic Tic Tac Toe game with a graphical user interface built using Python's Tkinter library.

## Features

- **Two Player Mode** - Play against a friend on the same computer
- **Graphical Interface** - Clean, colorful Tkinter-based GUI
- **Score Tracking** - Keeps track of wins for both players and ties
- **Play Again** - Quick restart after each game
- **3x3 Grid** - Classic Tic Tac Toe board
- **Visual Feedback** - Distinct colors for X (red) and O (blue)

## Installation

### From GitHub (Recommended)
```bash
pip install git+https://github.com/lukaszplk/tic_tac_toe.git
```

### From Release Wheel
```bash
pip install https://github.com/lukaszplk/tic_tac_toe/releases/download/v1.0.0/tic_tac_toe_game-1.0.0-py3-none-any.whl
```

### Local Development
```bash
git clone https://github.com/lukaszplk/tic_tac_toe.git
cd tic_tac_toe
pip install -e .
```

## Usage

After installation, simply run:

```bash
tic-tac-toe
```

Or run directly from source:

```bash
python tic_tac_toe_game/tictactoe.py
```

## How to Play

1. **Player 1 (X)** - Starts first with red X's
2. **Player 2 (O)** - Plays second with blue O's
3. **Click** on any empty square to place your mark
4. **Win** by getting three in a row (horizontal, vertical, or diagonal)
5. **Tie** when all squares are filled with no winner
6. **Play Again** by clicking anywhere after a game ends

## Requirements

- Python 3.7+
- NumPy 1.19.0+
- Tkinter (usually comes with Python)

## Development

To set up for development:

```bash
# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the game
python tic_tac_toe_game/tictactoe.py
```

## Building

To build the package:

```bash
python -m build
```

## License

MIT License - feel free to use and modify!

## Credits

Classic Tic Tac Toe game mechanics.
