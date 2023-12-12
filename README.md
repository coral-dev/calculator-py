# Basic Calculator Program

## Introduction

This Python program is a simple yet effective calculator that performs basic arithmetic operations like addition, subtraction, multiplication, and division. The user interface is interactive, allowing the user to input numbers and choose operations to perform sequential calculations.

## Features

- **Basic Operations**: The calculator can perform addition (`+`), subtraction (`-`), multiplication (`*`), and division (`/`).
- **Continuous Calculations**: It allows for continuous calculations on the result of the previous operation.
- **User-Friendly Interface**: The program prompts the user for numbers and operations, making it easy to use.
- **Recursive Functionality**: If the user decides not to continue with the current calculation, the program restarts for a new calculation.

## Usage

1. **Start the Program**: Run the program. Upon startup, the calculator's logo is displayed.

2. **Input Numbers**: When prompted, enter the first number for the calculation.

3. **Select Operation**: Choose an operation (`+`, `-`, `*`, `/`) to perform on the entered number.

4. **Enter Second Number**: Enter the next number for the operation.

5. **View Result**: The program outputs the result of the operation.

6. **Continue or Restart**: 
   - To continue calculations with the result, type 'y' when prompted and repeat from step 3.
   - To start a new calculation, type 'n', and the program will restart.

## Example

```python
What's the first number?: 10
+
-
*
/
Pick an operation: +
What's the next number?: 5
10 + 5 = 15
Type 'y' to continue calculating with 15, or type 'n' to start a new calculation: y
Pick an operation: *
What's the next number?: 2
15 * 2 = 30
```

## Note

- The division operation does not handle division by zero. It will raise a `ZeroDivisionError` if the second number for a division operation is `0`.

## Conclusion

This basic calculator program is a great tool for simple arithmetic operations, demonstrating the basics of Python functions, loops, and dictionary usage in an interactive application.