# Tic-Tac-Toe-game
I made a tic tac toe game using python programig language

Tic-Tac-Toe is a classic two-player game that is typically played on a 3x3 grid. The goal of the game is to be the first player to get three of their symbols (either "X" or "O") in a row, either horizontally, vertically, or diagonally. Here's a basic description of how you can create a simple Tic-Tac-Toe game in Python:

**Initializing the Game**

Create a 3x3 grid to represent the Tic-Tac-Toe board. You can use a list of lists or any other data structure that suits your preference.


**Player Input**

Prompt the players for their moves. Players can specify their moves by entering the row and column where they want to place their symbol.
Updating the Game Board

Update the game board with the player's symbol in the specified location if it's a valid move. Ensure that the location is not already occupied.


**Checking for a Win**

After each move, check if the current player has won the game by having three of their symbols in a row, either horizontally, vertically, or diagonally. If there's a win, declare the winner and end the game.


**Checking for a Draw**

If the game board is full, and no player has won, it's a draw. Announce the draw and end the game.


**Switching Players**

Alternate between the two players (usually "X" and "O") after each move.


**Repeating Steps 2-6**

Continue steps 2 to 6 until there is a winner or a draw.


**Game Loop**

Wrap steps 2 to 7 in a game loop that continues until the game reaches a conclusion.


**Displaying the Board**

Display the updated game board after each move so that the players can see the current state of the game.


**Game Over**

When the game is over, ask the players if they want to play again. If they do, reset the board and start a new game. If not, exit the program.
