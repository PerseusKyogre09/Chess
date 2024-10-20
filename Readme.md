# Two-Player Chess Game

This is a two-player chess game implemented using Python's `pygame` library. The game follows standard chess rules and allows two players to take turns moving their pieces on a chessboard. The interface is designed with basic chess piece images, and moves are validated to ensure the correct behavior for each piece.

## Features

- **Two-player mode:** One player plays as white and the other as black, alternating turns.
- **Graphical Interface:** A clean, minimalistic chessboard design with easy-to-follow visuals for valid moves, captured pieces, and current game status.
- **Piece Movement:** Each piece follows its standard movement rules (pawns, rooks, knights, bishops, queens, and kings).
- **Move Validation:** The game checks for valid moves for each piece, ensuring no illegal moves are made.
- **Turn-based System:** The game alternates between white and black, prompting players to select and move their pieces.
- **Captured Pieces Display:** Captured pieces are displayed on the side of the board.

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/chess-game.git
```
2. Install the required dependencies.
```bash
pip install pygame
```
3. Run the game
```bash
python main.py
```
## Controls
- Mouse Click: Select and move pieces.
- Forfeit Button: A button is provided to forfeit the game.

## How to Play
1. The game starts with the white player's turn. The game status will indicate whether you need to select a piece or a destination for the move.
2. Once a piece is selected, its valid moves will be highlighted.
3. After white completes their move, it's black's turn to move.
4. Captured pieces are displayed on the right side of the board.
5. The game continues until a checkmate is achieved, or a player forfeits the game.

## Game Screenshots
![Chess-1](https://imgur.com/PVLL3dV.png)
![Chess-2](https://imgur.com/hcCZeit.png)

## Dependencies
- Python 3.6+
- pygame library

## Future Improvements
- Add functionality for detecting checkmate.
- Implement a time control for each player.
- Add an AI opponent to play against the computer.
- Improve piece movement animations.
