# Simple_Calculator
Beginner Python Project


Simple Calculator 🧮
A beginner-friendly Python calculator that performs basic arithmetic operations through an interactive command-line interface.
Features

➕ Addition
➖ Subtraction
✖️ Multiplication
➗ Division
🔢 Modulo (remainder)
Error handling for division by zero
Input validation for invalid operators

Requirements

Python 3.x
Jupyter Notebook or Google Colab (for .ipynb file)

Usage
Run the calculator function by executing the cells in order:
pythonprint(simple_calculator())
Example:
=== simple calculator ===
operation: +, -, *, /, %
enter first number: 156
enter operation: *
enter second number: 5
156.0 * 5.0 = 780.0
Supported Operations
OperationSymbolExampleAddition+5 + 3 = 8Subtraction-5 - 3 = 2Multiplication*5 * 3 = 15Division/6 / 3 = 2.0Modulo%5 % 3 = 2
Error Handling
The calculator includes built-in error handling for:

Division by zero: Returns "Error: Division by zero!"
Modulo by zero: Returns "Error: Modulo by zero!"
Invalid operators: Returns "Error: Invalid operator!"

Code Structure
pythondef simple_calculator():
    # 1. Display available operations
    # 2. Get user input for two numbers and operation
    # 3. Perform calculation based on operator
    # 4. Handle errors (division by zero, invalid operator)
    # 5. Return formatted result
Future Enhancements
Potential improvements for this project:

 Add more advanced operations (power, square root, etc.)
 Implement a GUI using Tkinter or PyQt
 Add calculation history
 Support for multiple operations in one expression
 Convert to a standalone Python script

Acknowledgments

Built as a beginner Python project
Perfect for learning basic programming concepts: functions, conditionals, user input, and error handling
