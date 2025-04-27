# 🧩 Sudoku Solver – Java CLI Application

A simple and efficient Sudoku Solver built in Java using the **Backtracking Algorithm**.

This project takes a partially filled 9x9 Sudoku board and finds the solution following Sudoku rules:
- Each number (1-9) must appear exactly once in each row, column, and 3x3 subgrid.

---

## 💻 Features:
✅ Solve any valid 9x9 Sudoku board  
✅ Uses recursive Backtracking approach  
✅ CLI-based input and output  
✅ Neat board printing for visual clarity  
✅ Handles invalid boards gracefully

---

## 🚀 Technologies Used:
- Java
- Recursion and Backtracking
- 2D Arrays
- CLI (Command Line Interface)

---

## 🎯 How to Run:
1. Clone the repository
2. Open in any Java IDE (like IntelliJ IDEA, Eclipse) or terminal
3. Compile and run the `SudokuSolver.java` (or your Main file)
4. Provide the Sudoku board as a 2D array input inside the code

---

## 📜 Algorithm Brief:
The solver tries to fill empty cells one by one by:
1. Trying numbers 1 to 9 in each empty spot
2. Checking if placing the number violates Sudoku rules
3. If a conflict occurs, it **backtracks** and tries the next number
4. Repeats until the board is filled successfully or declared unsolvable

---

## 🌟 Future Scope (Optional Upgrades):
- Read Sudoku board from user input or a file
- Add GUI (Graphical User Interface) for easier interaction
- Support solving multiple puzzles in one run

---

Made with 💖 by [Parul Jain](https://www.linkedin.com/in/enggparul-jain216/)

