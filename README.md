# Simple CLI Calculator

A command-line calculator built in Python that supports basic arithmetic 
along with power, modulus, floor division, square root, and logarithm operations.
__________________________________________________________________________________________________________________________________________
## Features
- Supports: `+`, `-`, `*`, `/`, `**` (power), `%` (modulus), `//` (floor division), `sqrt`, `pow`, `log`
- Handles invalid input gracefully (e.g., division by zero, invalid numbers, invalid operations)
- Lets you perform multiple calculations in one session without restarting the program
- Type `q`, `quit`, or `exit` at any number prompt to exit the program
__________________________________________________________________________________________________________________________________________
## How to Run
1. Make sure Python 3 is installed on your system.
2. Clone this repository: https://github.com/hitanshjain-prog/calculator-py
__________________________________________________________________________________________________________________________________________
## Example Usage
Simple Calculator
Supported operations: +, -, *, /, **, %, //, sqrt, pow, log
Enter first number: 16
Enter operation: sqrt
Result: 4.0
Would you like to perform another calculation? (y/n): y
Enter first number: 10
Enter operation: /
Enter second number: 0
Result: Error: Division by zero
Would you like to perform another calculation? (y/n): n
Goodbye!
__________________________________________________________________________________________________________________________________________
## Technologies Used
- Python 3
- Built-in `math` module

## What I Learned
- Structuring code into functions for better readability (separating input handling, 
  calculation logic, and program flow)
- Handling edge cases like division by zero and invalid logarithm inputs
- Using loops to allow repeated calculations without restarting the program
- Basic input validation and error handling in Python

## Future Improvements
- Add a graphical interface (GUI) using Tkinter
- Add support for more advanced operations (trigonometric functions, factorial, etc.)
- Add unit tests to verify calculation correctness
- Store calculation history in a file

## Author
[Hitansh Jain] — a first-year B.Tech CSE (AI & ML) student, building projects while learning Python.
