# Sudoku Solver

A Python-based Sudoku solver that uses a backtracking algorithm to solve any given Sudoku puzzle.

## Project Overview

This project provides a simple implementation of a Sudoku solver in Python. The solver takes a partially filled 9x9 Sudoku board and attempts to fill the empty cells with numbers from 1 to 9, following the rules of Sudoku.

## Features

- Solves any valid 9x9 Sudoku puzzle using backtracking.
- Provides a simple interface to input the Sudoku board.
- Displays the solved Sudoku board.

## Getting Started

### Prerequisites

- Python 3.x

### Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/anshulkotwal/SUDUKO_SOLVER-PYTHON.git
    cd Sudoku-Solver
    ```

2. Run the solver:

    ```sh
    python sudoku_solver.py
    ```

## Usage

1. Define the Sudoku board in the `sudoku_solver.py` file. The board is represented as a 2D list where empty cells are denoted by 0.

    ```python
    board = [
        [7,8,0,4,0,0,1,2,0],
        [6,0,0,0,7,5,0,0,9],
        [0,0,0,6,0,1,0,7,8],
        [0,0,7,0,4,0,2,6,0],
        [0,0,1,0,5,0,9,3,0],
        [9,0,4,0,6,0,0,0,5],
        [0,7,0,3,0,0,0,1,2],
        [1,2,0,0,0,7,4,0,0],
        [0,4,9,2,0,6,0,0,7]
    ]
    ```

2. Run the script to solve the Sudoku and print the solved board.

    ```sh
    python sudoku_solver.py
    ```

## Example

Initial Sudoku Board:

7 8 0 | 4 0 0 | 1 2 0
6 0 0 | 0 7 5 | 0 0 9
0 0 0 | 6 0 1 | 0 7 8

0 0 7 | 0 4 0 | 2 6 0
0 0 1 | 0 5 0 | 9 3 0
9 0 4 | 0 6 0 | 0 0 5

0 7 0 | 3 0 0 | 0 1 2
1 2 0 | 0 0 7 | 4 0 0
0 4 9 | 2 0 6 | 0 0 7
