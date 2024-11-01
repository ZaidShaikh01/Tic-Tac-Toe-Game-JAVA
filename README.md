This Java program is a simple implementation of a Tic-Tac-Toe game where two players ('X' and 'O') take turns. Here’s a breakdown of how it works:

Key Components:
Board Initialization:

A 3x3 board (char[][] board) is initialized with empty spaces (' ').
Game Loop:

The game runs in a while loop until gameOver becomes true.
Each turn, the current player is prompted to enter a row and column to place their mark.
Input Validation and Move Placement:

If the chosen cell is empty, the player’s mark ('X' or 'O') is placed.
If the cell is already occupied, an "Invalid Move" message is displayed.
Win Check:

After each move, haveWon() checks if the player has won by:
Completing a row
Completing a column
Completing a diagonal
If a win is detected, the game announces the winner and ends.
Turn Switching:

If the game is not over, the turn switches to the other player.
Board Display:

printBoard() prints the board after every move, with each cell separated by " | ".
