Question is property of Uchicago, I dont own it. 

Suppose we have a board game played on a board with N × N squares, where (0, 0) is the top-left coordinate. 
The game has at most six players numbered from 1 to 6.

In each turn, a player can either place a piece on the board, or make a capture. 
We are not concerned with the rules that govern how pieces are placed on the board; 
instead, we will assume that pieces have already been placed on the board, and we will determine what captures can be made.

We will say that a piece from player X can be captured if it is enclosed by two pieces of another player Y in the same row or column. 
Consider the board below, where zeroes (0) represent empty squares, and numbers greater than zero represent pieces from a player. 
In this board, the piece from player 2 can be captured by player 1:
