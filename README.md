# Unhandled Division by Zero in JavaScript

This repository demonstrates a common error in JavaScript: unhandled division by zero. The `foo` function attempts to divide `a` by `b`, but doesn't properly handle the case where `b` is zero. This results in an error. The solution demonstrates how to correctly handle this situation using a simple `if` statement.

## Bug

The `bug.js` file contains the erroneous code. The function `foo` does not check if `b` is zero before performing the division, resulting in an error if `b` is zero.

## Solution

The `bugSolution.js` file provides the solution. The function `foo` now includes a check for `b` being zero. If `b` is zero, the function returns zero. Otherwise, it performs the division as expected.