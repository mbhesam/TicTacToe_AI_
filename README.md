 # Alpha-beta-pruning solution for tic tac toe Game
 ##AI vs Player:
This mode you can play with AI. you can not win AI because it behaves based on alphabeta prunning minimax and select the best move.
alpha beta prunning is based on minimax algorithem but there are differences between them:
Both algorithms should give the same answer. However, their main difference is that alpha-beta does not explore all paths, like minimax does, but prunes those that are guaranteed not to be an optimal state for the current player, that is max or min. So, alpha-beta is a better implementation of minimax.
 ##AI vs AI:
This mode functions as a test to demonstrate that the AI works by showing every game ends in a draw. It runs 10000 iterations of the game of the AI playing against itself. The count at the end displays the amount of times either of the AI's won a game, this count should be 0.
