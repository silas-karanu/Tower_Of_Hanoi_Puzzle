# Tower_Of_Hanoi_Puzzle
 Loop-based approach to solving the tower of Hanoi mathematical puzzle. Then implementation of a recursive solution.

# 🧠 Tower of Hanoi – Recursive and Iterative Implementations in Python

This repository contains two Python implementations of the classic **Tower of Hanoi** problem:

- `iterative.py`: An **iterative** solution using rules and cycles.
- `recursive.py`: A **recursive** solution using a divide-and-conquer approach.

---

## 📂 Files

### `iterative.py` – Iterative Tower of Hanoi

- Uses a dictionary to represent rods (`'A'`, `'B'`, `'C'`).
- Moves disks iteratively using modular arithmetic.
- Handles moves through the `make_allowed_move` function.
- Dynamically decides which two rods to move between at each step based on the current move number and parity of disk count.

### `recursive.py` – Recursive Tower of Hanoi

- Uses three separate lists: `A`, `B`, and `C`.
- Solves the problem through classic recursion.
- After every disk move, it prints the state of the rods.

---

## 🛠️ How to Run

Make sure Python 3 is installed.

Run either file from the terminal:

```bash
python iterative.py
```
---

## 🚀 Concepts Demonstrated
- Recursion and base cases

- Iterative control using modular arithmetic

- Data structures: lists and dictionaries

- Condition-based movement logic

- Print debugging and state visualization

---

## 🔧 Area for Improvement

 - Refactor `make_allowed_move()` to improve readability and reduce repetition.

 - Add error handling for invalid states (e.g., popping from empty rods).

- Turn print statements into optional verbose logs using `logging` module.

 - Add a GUI version using `tkinter` or `pygame`.

 - Convert to OOP: Create a `Rod` class and `TowerOfHanoi` class for cleaner structure.

 - Write unit tests using `unittest` or `pytest`.

 - Let the user input the number of disks and choose iterative or recursive mode.

 - Track and print the total number of moves made.

---

