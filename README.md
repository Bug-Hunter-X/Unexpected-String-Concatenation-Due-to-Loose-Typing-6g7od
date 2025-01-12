# Unexpected String Concatenation in JavaScript

This repository demonstrates a common JavaScript bug caused by the language's loose typing system.  The `foo` function intends to add two numbers, but due to implicit type coercion, it performs string concatenation when one of the arguments is a string.

## Bug

The `bug.js` file contains the erroneous code.  Observe the unexpected output when a number and a string are passed as arguments.

## Solution

The `bugSolution.js` file provides a corrected version, explicitly converting the inputs to numbers before performing addition. This avoids implicit type coercion and ensures the expected numerical result.

This example highlights the importance of careful type handling in JavaScript to prevent unexpected behavior and ensure correct program execution.