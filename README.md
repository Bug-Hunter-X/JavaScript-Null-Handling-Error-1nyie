# JavaScript Null Handling Bug

This repository demonstrates a common error in JavaScript when dealing with null values and its solution.

The `bug.js` file shows the erroneous code where the addition of numbers does not properly handle null values. The `bugSolution.js` shows the corrected code that accounts for null values and returns a default value of 0.

## Bug

The original code doesn't check for null values, leading to unexpected results or errors when null values are passed as parameters to the `foo` function.

## Solution

The solution explicitly checks for null values using strict equality (`===`) and returns 0 if either or both parameters are null. This ensures that the function behaves correctly even when null values are passed in.