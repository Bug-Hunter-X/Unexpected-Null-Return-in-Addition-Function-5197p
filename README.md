# JavaScript Bug: Unexpected Null Return in Addition Function

This repository demonstrates a common JavaScript bug involving the unexpected return of null when performing an addition operation with potentially null values. The `foo` function adds two numbers, but it returns null if either of the inputs is null. This behavior can lead to unexpected results or program crashes.

## Bug Description
The `bug.js` file contains a function named `foo` that takes two numbers as input and returns their sum. However, if either of the inputs is null, the function returns null. This is problematic because it prevents further operations that may expect a numerical result.

## Solution
The `bugSolution.js` file provides a corrected version of the `foo` function. The solution handles null input values by assigning them a default value of 0 before performing the addition.

## How to Reproduce
1. Clone this repository.
2. Open `bug.js` and run the code in a JavaScript environment.
3. Observe the unexpected null returns.
4. Open `bugSolution.js` and run the code to see the corrected behavior.
