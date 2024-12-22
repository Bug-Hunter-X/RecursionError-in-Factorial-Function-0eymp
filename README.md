# RecursionError in Factorial Function

This repository demonstrates a common error in recursive functions: the lack of a proper base case handling for negative input.  The factorial function is not defined for negative numbers, resulting in infinite recursion and a `RecursionError`.

The `bug.py` file contains the erroneous code.  The `bugSolution.py` file provides a corrected version that handles negative input gracefully.