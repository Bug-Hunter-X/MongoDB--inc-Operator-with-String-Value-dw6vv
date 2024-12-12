# MongoDB $inc Operator with String Value

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations.  The `$inc` operator is used to increment a numerical field by a specified value. However, providing a string value instead of a number can lead to unexpected results and data corruption.

The `bug.js` file contains code that incorrectly uses the `$inc` operator with a string, while `bugSolution.js` provides the correct implementation.

## Bug Description
Incorrectly using a string with the `$inc` operator leads to incorrect data modifications and unexpected behavior.  The solution will show how to provide a numerical value for correct functioning.
