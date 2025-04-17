# Sudoku Solver

This is a Python script to solve a 9x9 Sudoku puzzle using a backtracking algorithm.

## Features
- Solves 9x9 Sudoku puzzles efficiently.
- Uses a backtracking algorithm to fill in missing numbers.
- Provides formatted input and output for clarity.

## Installation
Ensure you have Python installed. Then, clone this repository and navigate to the project folder:

```sh
git clone https://github.com/shreyash0019/Sudoku-Solver.git
cd Sudoku-Solver
```

## Usage

1. **Edit the `main.py` file** to input your Sudoku puzzle. Use `0` for empty cells.
2. **Run the script** with:

```sh
python3 main.py
```

## Example
### **Input Sudoku**
```
8 1 0 | 0 3 0 | 0 2 7
0 6 2 | 0 5 0 | 0 9 0
0 7 0 | 0 0 0 | 0 0 0
---------------------
0 9 0 | 6 0 0 | 1 0 0
1 0 0 | 0 2 0 | 0 0 4
0 0 8 | 0 0 5 | 0 7 0
---------------------
0 0 0 | 0 0 0 | 0 8 0
0 2 0 | 0 1 0 | 7 5 0
3 8 0 | 0 7 0 | 0 4 2
```

### **Output Sudoku**
```
8 1 9 | 4 3 6 | 5 2 7
4 6 2 | 7 5 1 | 3 9 8
5 7 3 | 2 9 8 | 4 1 6
---------------------
2 9 4 | 6 8 7 | 1 3 5
1 5 7 | 9 2 3 | 8 6 4
6 3 8 | 1 4 5 | 2 7 9
---------------------
7 4 5 | 3 6 2 | 9 8 1
9 2 6 | 8 1 4 | 7 5 3
3 8 1 | 5 7 9 | 6 4 2
```

## Project Structure
```
Sudoku-Solver/
│── .gitignore
│── README.md
│── requirements.txt
│── main.py
│── sudoku_samples/
│   ├── sample1.txt
│   ├── sample2.txt
│── tests/
│   ├── test_solver.py
```

---
### Contributions
Feel free to submit a pull request if you'd like to improve the solver!
