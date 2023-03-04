# AI-Based-Tik-Tac-Toe
## Introduction :
 Tic-Tac-Toe is an Artificial Intelligent program that can intelligently 
respond to the player’s moves. A player plays against a computer. The player makes a turn marking 
an X and the computer marks an O on the board. If either a player or the computer gets three of 
their marks on the board in a row, column or one of the two diagonals, they win. If the player has 
two of the spots filled up in a row, a column or in a diagonal and computer has its next turn, it will 
intelligently detect and fill up the spot by which the player can win. When the board fills up with 
neither player winning, the game ends in a draw. The search space of this board is not 3X3 but 
10X10.
## Architecture:
Dataset:
 The game will consist of a 10X10 dataset, with hundred squares that will have a clash 
between the human and the computer to determine who will claim a victory.
Features:
 Artificial Intelligent opponent.
 Simple Interface.
 Win: If the player or the computer has two in a row, they can place a third to get three in a 
row.
 Block: If the player has two ‘X’s’ in a row, the computer will make a move next to it, 
blocking the player. 
 Lose: The first from a player or a computer to place 3 markers in a row wins and the other 
one loses

## Tools and technique:
Pychram IDE:
 For this project we have used PYTHON as for language. Tools we used 
are PyCharm for the implementation of python. PyCharm is a dedicated Python Integrated 
Development Environment (IDE). It entertains us with all the features, tools, libraries of python language. There are also other compilers for PyCharm to work on like Visual Studio, but we 
chose PyCharm. We used PyCharm to call the dataset already fetched by Google Collab to the 
web.

##Minmax algorithm with alpha beta pruning :
 Minimax is a decision-making algorithm, typically used in a turn-based, two player games. The goal of the algorithm is to find the optimal 
next move. In the algorithm, one player is called the maximizer, and the other player is a 
minimizer. Alpha-beta pruning seeks to reduce the number of nodes that needs to be evaluated in 
the search tree by the minimax algorithm.