# n_queen_visualizer
This project solves the classic N-Queens Puzzle, where the objective is to place N queens on an N x N chessboard such that no two queens threaten each other. A solution ensures that no two queens share the same row, column, or diagonal.

PROBLEM DESCRIPTION:

The N-Queens puzzle is a famous problem in which N queens must be placed on an N x N chessboard. The constraints are:

No two queens can be placed in the same row or column.
No two queens can be placed on the same diagonal.
The challenge grows as N increases, and the goal is to find all possible solutions for placing the queens on the board.

SOLUTION APPROACH:


This project uses a recursive backtracking algorithm to solve the N-Queens problem efficiently:

Recursion: The algorithm places queens row by row, recursively exploring valid placements.
Backtracking: If placing a queen results in a conflict later on, the algorithm backtracks and tries a different column placement.


ALGORITHM OVERVIEW:

Start from the first row and place a queen in a column where it does not threaten any previously placed queens.
Recursively repeat the process for the next row.
If a conflict is encountered, backtrack by removing the queen and trying the next possible placement.
The process continues until all queens are placed safely, or all possibilities are exhausted for a row.

TIME COMPLEXITY:

The time complexity of this algorithm is O(N!) since for each row, the algorithm has to try N possible columns for placing a queen.

FEATURES:

Solves the N-Queens puzzle for any board size N.
Displays all possible valid configurations for placing N queens.
Efficient use of recursion and backtracking to ensure optimal performance.
