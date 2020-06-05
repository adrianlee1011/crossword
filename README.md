# Crossword Puzzle Generator

Given a text file of words, and the structure of the crossword puzzle, the program will generate a solution for the crossword.

Algorithms used:
- AC-3 algorithm to enforce arc consistency.
- Least constraining values heuristic for determining the domain to assign to the particular variable.
- Minimum remaining value heuristic to determine the fewest number of remaining values in the particular domain of the variable.
- Largest degree heuristic to determine the most neighbours of the variable.
- Backtracking algorithm to solve the crossword.

Example crossword:
