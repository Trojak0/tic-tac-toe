# tic-tac-toe

This C++ program implements a simple Tic-Tac-Toe game where two players take turns marking spaces on a 3x3 grid. Here's how to use the program:

Running the Program:

Compile and run the program using a C++ compiler.
The program will initialize the game board and display it, prompting Player X to make the first move.
Gameplay:

Players take turns entering the square they want to mark with their symbol (X or O).
Enter the letter corresponding to the square you want to mark (a-i) when prompted.
The board will update after each move, displaying the new state.
Winning:

The program automatically checks for a winning condition after each move.
If a player has three of their symbols in a row (horizontal, vertical, or diagonal), the program will output "Congratulations you won!".
Quitting:

To quit the game at any time, enter 'q' when prompted for a move.
Board Display:

The displayBoard() function shows the current state of the game board.
The board consists of letters denoting each square (a-i), separated by vertical lines and dashes.
Move Validation:

The moveToSquare() function allows a player to mark a specific square with their symbol (X or O).
The function verifies the player's move and updates the board accordingly.
Notes:

The program utilizes functions to handle different aspects of the game, promoting modularity and readability.
Players alternate between X and O symbols for their moves.
The game continues until a player wins or the user quits by entering 'q'.
Enjoy playing Tic-Tac-Toe with your friends using this simple C++ program!
