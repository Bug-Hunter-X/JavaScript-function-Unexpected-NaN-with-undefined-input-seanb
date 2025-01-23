# JavaScript function Unexpected NaN with undefined input

This repository demonstrates a common JavaScript error related to unexpected NaN when a function expects null but receives undefined. The function `foo` handles null correctly but does not explicitly handle undefined, resulting in NaN when undefined is passed as an argument. The solution demonstrates how to handle this by explicitly checking for undefined.

## Bug

The `bug.js` file contains the buggy function. It returns 0 when null is passed in but NaN when undefined is passed in because there is no handling for undefined.

## Solution

The `bugSolution.js` file provides a solution that handles both null and undefined cases, preventing the NaN error.