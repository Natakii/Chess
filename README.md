# Chess
Python chess library
# Game Play

The first thing we need to do is import the chess library:

## Installation

```bash
pip install python-chess
```

## Usage

```python
import chess

board = chess.Board()
board.turn
board.turn == chess.WHITE
board
board.legal_moves
board.push_san("e4")
board
board.push_san("e5")
board
board.push_san("f4")
board

board.push_san("f4")
board
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
