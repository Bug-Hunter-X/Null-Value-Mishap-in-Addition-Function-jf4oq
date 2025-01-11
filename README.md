# JavaScript Bug: Null Value Handling in Addition Function

This repository demonstrates a common error in JavaScript: improper handling of null values.

The `foo` function, designed to add two numbers, incorrectly returns 0 when either input is null.  A more robust solution would either treat null as 0, or raise an error indicating invalid input.

The `bug.js` file contains the buggy code. `bugSolution.js` shows the corrected version.

## How to reproduce

1. Clone this repository.
2. Open the `bug.js` file.
3. Run the script using Node.js or a similar environment.
4. Observe the unexpected output when null values are provided as arguments.