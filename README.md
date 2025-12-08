# Arithmetic Practice

Simple in-browser drills for addition, subtraction, multiplication, and division with two or three numbers.

## Features
- Toggle operations and pick two or three operands.
- Auto-generated solvable problems for each mode, including divisible division and non-negative subtraction.
- Instant correctness feedback with quick cycling to the next problem.

## How problems are generated
- Addition/Multiplication: random integers 1–20 (2 or 3 operands).
- Subtraction: all terms start 1–30; the first term is bumped to the sum of the rest plus 0–20 to avoid negatives.
- Division: picks factors (1–12 and 2–12; plus another 2–12 for 3-operands), multiplies them for the dividend so every division is exact.

## Usage
1. Open `index.html` in a modern browser (or serve the folder locally, e.g., `python3 -m http.server 8000`).
2. Choose the number count and an operation.
3. Enter your answer and press **Enter** or click **Enter** to check and continue.

## Notes
- Optimized layout for desktop and mobile; focus returns to the answer field after each problem.
