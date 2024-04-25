TicTacToe
This is a simple implementation of the classic game Tic-Tac-Toe using Java Swing library. The game is designed to be played on a 600x650 pixels window, with a 50 pixels high text panel on top displaying the current player's turn.

Screenshot

![image](https://github.com/Yash3440/Tic-Toc-Toe-Game/assets/95624581/a51d2914-5e3c-454c-b683-b01f23cf71bc)


How to Play-
The game starts with player X.
Click on an empty tile to place your mark.
The game will automatically switch to the other player after each turn.
The first player to get 3 of their marks in a row (horizontally, vertically, or diagonally) wins the game.
If all 9 tiles are filled and no player has won, the game ends in a tie.
Code Structure
The code is structured as follows:

TicTacToe class: This is the main class that sets up the game window, creates the text panel and the game board, and handles user input.
ActionListener: An anonymous inner class that listens for button clicks and updates the game state accordingly.
checkWinner method: This method checks if there is a winner or a tie after each turn.
setWinner method: This method sets the background and foreground colors of the winning tiles to indicate a win.
setTie method: This method sets the background and foreground colors of all tiles to indicate a tie.
Running the Code
To run the code, simply compile and run the TicTacToe.java file.

Building and Running with Maven
Alternatively, you can build and run the code using Maven. Here are the steps:

Clone this repository to your local machine.
Open a terminal and navigate to the cloned repository.
Run mvn clean compile to compile the code.
Run mvn exec:java to run the game.
Note: You will need to have Maven installed on your machine to run the above commands.

License
This project is licensed under the MIT License - see the LICENSE file for details.
