# Sudoku Solver
Backtracking algo that solves sudoku puzzles.

Goes through each cell, checks if a number between 1 and 9 can be placed there. If yes, it goes on to the next cell and continues until board is full. If board is full, it implements the changes. If its made a bad choice, it essentially backtracks and changes the number in the board one level above.
