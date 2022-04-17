# Javascript-Game--Rock-Paper-Scissors
Created a web page that allows players to interact with the game. The various elements on the web page can be used to submit inputs or display outputs.

The following functions are implemented in the course of this project 



* startGame() - Starts the game and displays input prompts.
* endGame(event) - Triggered by user input. Computes and displays the end of the game.
* calcResult(move1,move2)- Called in endGame() to compute the result and return it as a string. The moves are a number between 0 - 2 corresponding to the index of the moveList. A victory is returned when move 1 wins over move 2.
* randomMove() - A function that returns a random number between 0 - 2 . Used to generate the computer move in calcResult().
