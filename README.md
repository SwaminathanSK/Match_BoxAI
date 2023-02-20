# Match_BoxAI
Making an AI reinforced model to learn tic-tac-toe.
Using the code in this repository one can play tic-tac-toe with the computer as it learns over several gameplays.
The binary file stores the pickled data of probability distributions (reinforcements) for each move and for each board configuration. Initialize this whenever you want to restart the learning process
by executing the Bin_Init_File code.


To play the game, run the Main_code file and enter the inputs, for example, as ->


1 0 0


2 0 1


0 2 0

This denotes the current state of the board after you have made your move. Here, 1 corresponds to X, 2 to O and 0 to an empty space. As the player, you can only play as O
for the current version of this project. The computer plays as X and it displays its moves in the same manner.
