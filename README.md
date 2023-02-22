# Chess Game

    This is a simple console-based implementation of the game of chess in Java. The game can be played by two players on a single computer, and follows the standard rules of chess.

## How to Play

    To run the game, simply run the Main class in your Java IDE of choice. The game will start with an empty chess board.

    To make a move, enter the starting and ending coordinates of the piece you want to move, separated by a space. For example, to move the pawn at position a2 to a4, enter a2 a4. If the move is valid, the game will update the board and prompt the other player to make their move.

    If a player's king is in check, they must make a move to get out of check on their next turn. If a player's king is in checkmate, the game is over and the other player wins.

## Implementation Details

    The game is implemented using object-oriented programming principles in Java. The game board is represented by a 2D array of Piece objects, with each subclass of Piece representing a different type of chess piece (e.g., King, Queen, Rook, etc.). The game logic enforces the rules of chess, including move validation, check and checkmate detection, and pawn promotion.

## Future Improvements

    Some potential improvements to the game include:

    - Adding support for multiplayer over a network
    - Implementing an AI player to play against
    - Adding a graphical user interface to make the game more user-friendly

## Credits

    This game was created by Joseph Oh. Feel free to use and modify the code as you see fit.