# Unhandled Exception: Division by Zero

This repository demonstrates a common error in JavaScript: unhandled exceptions. Specifically, this example focuses on the error that arises when attempting to divide by zero.

## Description

The `bug.js` file contains a simple calculator with functions for addition, subtraction, multiplication, and division.  The `divide` function includes a check for division by zero, but it throws an error if this condition is met. However, the error is not handled, leading to program termination.

The `bugSolution.js` file provides a solution that handles this potential exception using a `try...catch` block.

## How to reproduce the bug

1. Clone the repository.
2. Navigate to the directory.
3. Run `node bug.js` in your terminal.
4. Observe the unhandled exception error.

## How to fix the bug

Examine the `bugSolution.js` file to see how to use `try...catch` to handle potential exceptions gracefully.  This prevents the program from crashing and allows for more robust error handling.