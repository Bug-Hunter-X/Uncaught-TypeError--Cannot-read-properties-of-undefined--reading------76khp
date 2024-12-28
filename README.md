# Uncaught TypeError: Cannot read properties of undefined (reading '+')
This JavaScript code demonstrates a common error caused by implicit type coercion and missing function arguments. The `foo` function expects two arguments but is called with only one. This leads to an attempt to add a number to `undefined`, resulting in a `TypeError`.
The solution involves adding default parameter values to the function, ensuring that even when arguments are missing, it still executes without error.
This repository contains:
* `bug.js`: The original code containing the bug.
* `bugSolution.js`: The corrected code with the bug fixed.