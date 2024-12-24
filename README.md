# JavaScript Switch Statement Without Default Case

This repository demonstrates a common error in JavaScript: using a switch statement without a default case. The code includes a function `operate` that performs arithmetic operations based on the operator provided. However, if an invalid operator is passed, it throws an error. 

The `bug.js` file contains the buggy code that throws an error for unsupported operators.  The `bugSolution.js` file provides a corrected version that includes a default case to handle such situations more gracefully.

## How to Reproduce the Bug
1. Clone the repository.
2. Open `bug.js` and run it using a Node.js environment (or in a browser's developer console).
3. Notice the error thrown when an unsupported operator (like '%') is provided.