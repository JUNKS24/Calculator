## Aim:

To develop a simple calculator program using the C language that performs basic arithmetic operations (+, -, *, /) based on user input, utilizing a switch statement for operation selection.

## Objective:
Learn how to use switch-case for control flow based on user input.

Perform basic arithmetic operations (addition, subtraction, multiplication, and division).

Get familiar with reading input using scanf and displaying output using printf.

Handle different data types (character for operator, double for operands)

Input/Parameters Used:

1. Operator (op):

A character input (+, -, *, /) used to select the desired arithmetic operation.



 Operands (first and second):

Two double-precision floating-point numbers entered by the user, which act as the numbers on which the operation is performed.

## Code Explanation using switch-case:

The switch statement evaluates the op character and matches it to a corresponding case:

Case '+': Adds the two operands.

Case '-': Subtracts the second operand from the first.

Case '*': Multiplies the two operands.

Case '/': Divides the first operand by the second.

Default Case: Displays an error message if the operator is invalid.
