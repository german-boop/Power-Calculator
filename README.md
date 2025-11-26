# Power Calculator

A simple Python program to calculate the power of a number using `math.pow()`.

## Features

- Input any base and exponent (floating-point numbers allowed).
- Calculates `x^y` using Python's math module.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/power-calculator.git


Here’s a minimal and beginner-friendly version using math.pow(x, y):

# Calculate x raised to the power y

import math

x = float(input("Base (x): "))
y = float(input("Exponent (y): "))

print("Result:", math.pow(x, y))

Here’s a minimal, clear, and beginner-friendly version using three variables with math.pow(x, y):

# Calculate powers of three numbers

import math

# Input three base-exponent pairs
x1 = float(input("Enter first base: "))
y1 = float(input("Enter first exponent: "))

x2 = float(input("Enter second base: "))
y2 = float(input("Enter second exponent: "))

x3 = float(input("Enter third base: "))
y3 = float(input("Enter third exponent: "))

# Calculate and display powers
print("Result 1:", math.pow(x1, y1))
print("Result 2:", math.pow(x2, y2))
print("Result 3:", math.pow(x3, y3))


Here’s a minimal and clear version using a loop to handle three sets of base-exponent-multiplier inputs:

import math

# Loop for 3 sets of numbers
for i in range(1, 4):
    x = float(input(f"Enter base x{i}: "))
    y = float(input(f"Enter exponent y{i}: "))
    z = float(input(f"Enter multiplier z{i}: "))
    
    # Calculate (x ** y) * z
    result = math.pow(x, y) * z
    print(f"Result {i}: {result}")

