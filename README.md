# Unexpected Output in Conditional Statement

This repository demonstrates a subtle bug in a JavaScript function that leads to unexpected output when a specific input (0) is provided.

## Bug Description

The function `foo` aims to return 0 if the input is null, -1 if the input is negative, and 1 otherwise.  However, due to an oversight in the conditional logic, it returns 1 when the input is 0, which is incorrect.  The corrected version ensures that 0 is handled properly, returning 0 in that specific case.

## How to Reproduce

1. Clone this repository.
2. Open `bug.js`.
3. Run the code.
4. Observe the unexpected output when the input is 0.
5. Open `bugSolution.js` and compare the corrected logic. 