# ZeroDivisionError in Python
This repository demonstrates a common error in Python: the ZeroDivisionError, which occurs when performing division by zero.  The example function `calculate_average` calculates the average of a list of numbers.  The bug arises when an empty list is passed to the function.  The solution demonstrates a robust approach to handling this edge case.

## Bug
The original code fails when the input list is empty, raising a `ZeroDivisionError`.

## Solution
The solution adds a check for an empty list at the beginning of the function.  If the list is empty, the function returns 0, preventing the error.