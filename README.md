# TypeScript Type Error Bug
This repository demonstrates a common type error in TypeScript, where a string is passed to a function expecting a number.  The error message is clear, but this example highlights the importance of type checking in TypeScript.

## Bug
The `bug.ts` file contains a function `add` that takes two numbers as arguments and returns their sum. However, the code attempts to call the function with a string and a number, resulting in a type error.

## Solution
The `bugSolution.ts` file shows the corrected code.  The solution ensures that only numbers are passed to the `add` function, avoiding the type error.