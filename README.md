# Chess Game with AI and Randomized Pieces

This is a chess game created using Python's `tkinter` and `python-chess` libraries. The game allows a player to play chess against a simple AI that makes random moves. The game also includes randomized piece placement at the start and checks for checkmate, displaying the winner when the game ends.

## Features:
- **Randomized Piece Setup**: Pieces are randomly placed at the start of each game.
- **Checkmate Detection**: The game automatically detects when a player is checkmated.
- **Winner Display**: When the game ends, the winner (either "White" or "Black") is displayed on the screen.
- **Player vs. AI**: The player plays as White, and the AI plays as Black with random moves.

## How to Play:

1. **Start the Game**:  
   Run the Python script to start the game:

2. **Move Pieces**:  
   Click on a piece to select it, then click on a valid square to move it.  
   The player controls White, and the AI controls Black.  
   The AI makes random moves in response to the player's moves.

3. **End Game**:  
   When a player is checkmated, the game will display a message on the screen showing who won (either "White" or "Black").

4. **Randomized Pieces**:  
   Each time the game starts, the pieces are randomly placed on the board, so no two games will start the same way.

### Planned Features:
- **Smarter AI**: The AI currently makes random moves, but it could be improved to use more advanced chess algorithms like minimax or alpha-beta pruning.
- **Undo Move**: Ability to undo the previous move.
- **Move Highlights**: Visual indication of legal moves for a selected piece.
- **Chess Notation**: Display the moves in standard chess notation.
