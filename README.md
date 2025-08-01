# Python-Chess

Python-Chess is a simple chess engine and GUI built with Python. It allows users to play chess against another human or an AI, visualize the board, and explore chess moves. The project is designed for learning and experimenting with chess programming concepts.

## Features
- Play chess with a graphical interface
- Human vs Human and Human vs AI modes
- Basic chess engine logic
- Move validation and legal move generation
- Piece images for a realistic board display

## Project Structure
- `ChessEngine.py`: Core chess logic, board representation, and move validation
- `ChessMain.py`: Main entry point and GUI logic
- `SmartMoveFinder.py`: AI move selection logic
- `images/`: Chess piece images (PNG format)
- `__init__.py`: Package initialization

## Requirements
- Python 3.x
- `pygame` (for GUI)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/SpaciousFish/Python-Chess.git
   cd Python-Chess
   ```
2. Install dependencies:
   ```bash
   pip install pygame
   ```

## Usage
Run the main script to start the game:
```bash
python ChessMain.py
```

## Credits
- Piece images from Wikimedia Commons

## License
This project is licensed under the MIT License.
