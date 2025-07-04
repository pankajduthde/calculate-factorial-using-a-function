# calculate-factorial-using-a-function

def factorial(n):
    if n == 0 or n == 1:
        return 1
    return n * factorial(n - 1)  # Recursive call

print(factorial(5))  # Output: 120



#using the math module for calculations

import math


num = float(input("Enter a number: "))


if num > 0:
    square_root = math.sqrt(num)
    natural_log = math.log(num)
else:
    square_root = "Undefined (must be >= 0)"
    natural_log = "Undefined (must be > 0)"

sine_value = math.sin(num)  # Works for all real numbers (radians)


print("\n--- Results ---")
print(f"Square root of {num}       : {square_root}")
print(f"Natural logarithm of {num} : {natural_log}")
print(f"Sine of {num} radians       : {sine_value}")

