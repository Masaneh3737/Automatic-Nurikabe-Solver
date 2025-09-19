# Automatic-Nurikabe-Solver 

NURIKABE SOLVER

This project implements an automatic solver for the Japanese logic puzzle Nurikabe, built in Python. The solver combines human-inspired logical deductions with a backtracking algorithm, aiming to process puzzles in a way similar to how a human player might reason through them before resorting to brute force.

PROJECT OVERVIEW:

Developed as part of a final-year dissertation in Economics & Mathematics at the University of Leeds.

Achieved a first-class grade (72%).

Showcases the ability to approach an open-ended problem with no predefined solution, combining creativity, persistence, and technical skill.

FEATURES:

Handles puzzles of varying sizes (tested up to 9x9).

Logical deduction rules (e.g., resolving 1-cell islands, preventing diagonal merges).

Backtracking with depth-first search for unresolved sections.

Validity checks for island connectivity and wall continuity.

Hybrid design balances reasoning efficiency with algorithmic completeness.

SKILLS DEMONSTRATED:

Problem Solving: Designed rules from first principles to tackle an unsolved challenge.

Python Development: Implemented recursive functions, backtracking search, and custom data structures.

Algorithm Design: Created efficient hybrid logic–brute force solver.

Analytical Thinking: Applied mathematical reasoning to computational puzzle solving. 

EXAMPLE USAGE  
PYTHON 

# Example 5x5 puzzle input
grid = [
    [3, 0, 0, 0, 1],
    [0, 0, 0, 0, 0],
    [0, 2, 0, 2, 0],
    [0, 0, 0, 0, 0],
    [0, 0, 3, 0, 0]
]

solve(grid) 
