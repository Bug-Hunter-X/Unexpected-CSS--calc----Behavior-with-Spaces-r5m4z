# Unexpected CSS `calc()` Behavior with Spaces

This repository demonstrates a subtle bug in how CSS handles spaces within the `calc()` function. Incorrect spacing between operators and operands can lead to unexpected or erroneous results.

## Bug Description
The `calc()` function is a powerful tool for performing calculations within CSS. However, it is sensitive to extra spaces around the operators. Adding spaces between an operator and its operands can lead to an invalid expression and unexpected behavior.

## Reproduction
The `bug.css` file shows the problematic code, and `bugSolution.css` demonstrates the fix.

## Solution
Ensure there are no spaces between the operators (+, -, *, /) and their operands in `calc()` expressions. 