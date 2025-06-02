# ASSIGNMENT-3-Module-4-Functions-Modules-in-Python-
## ✅ Task 1: Calculate Factorial Using a Function

### 📌 Problem Statement
Write a Python program that:
1. Defines a function named `factorial` that takes a number as an argument and calculates its factorial using a loop or recursion.
2. Returns the calculated factorial.
3. Calls the function with a sample number and prints the output.

### 🧠 Logic Used
This solution uses **recursion** to calculate the factorial. If the number is 0 or 1, it returns 1. Otherwise, it calls itself with `n - 1`.

### 🧾 Code 
```python
def factorial(n):
    if n == 0 or n == 1:
        return 1
    else:
        return n * factorial(n - 1)

# Sample call to the function
sample_number = int(input("Enter a number: "))
output = factorial(sample_number)

# Print the result
print(f"The factorial of {sample_number} is {output}")

****Output****
Enter a number: 5
The factorial of 5 is 120

****************************************************************************************************************************************************

**Task 2: Using the Math Module for Calculations**
📌 Problem Statement
Asks the user for a number as input.
Uses the math module to calculate the:
Square root of the number
Natural logarithm (log base e) of the number
Sine of the number (in radians)
Displays the calculated results.

### 🧠 Code
import math
# Ask the user for a number
number = float(input("Enter a number: "))
# Perform calculations using math module
square_root = math.sqrt(number)
natural_log = math.log(number)
sine_value = math.sin(number)  # Input is in radians
# Display the results
print(f"Square root of {number} is: {square_root}")
print(f"Natural logarithm (log base e) of {number} is: {natural_log}")
print(f"Sine of {number} radians is: {sine_value}")

****Output****

Enter a number: 25
Square root of 25.0 is: 5.0
Natural logarithm (log base e) of 25.0 is: 3.2188758248682006
Sine of 25.0 radians is: -0.13235175009777303
