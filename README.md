# Subtle Bug in Euclidean Algorithm

This repository demonstrates a subtle bug in a JavaScript implementation of the Euclidean algorithm for finding the greatest common divisor (GCD) of two numbers. The bug is related to recursive calls and edge cases of inputs, causing incorrect results under specific conditions. 

The `bug.js` file contains the flawed implementation, while `bugSolution.js` provides a corrected version.

## Bug Description
The original code sometimes returns incorrect GCD values, particularly when the inputs have a specific relationship. The incorrect results primarily manifest when one number is significantly larger than the other or if the inputs share a specific ratio.

## Solution
The solution involves handling potential edge cases more carefully, thereby preventing the calculation of incorrect GCD values.

## How to Run
1. Clone this repository.
2. Navigate to the repository's directory in your terminal.
3. Run the JavaScript code using Node.js or a similar JavaScript runtime: `node bug.js` and `node bugSolution.js`.

Compare the outputs to understand how the fix addresses the bug.