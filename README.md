# MongoDB $inc Operator with String Value

This repository demonstrates a common error when using the `$inc` operator in MongoDB: providing a string value instead of a number.  The `$inc` operator is used to increment a numeric field in a MongoDB document.  Passing a string value will result in an unexpected outcome, not an increment of the value.

## Bug
The bug is in the `bug.js` file. The `$inc` operator is incorrectly used with a string value.  This results in an update that does not increment the counter properly.

## Solution
The `bugSolution.js` file provides the corrected code.  The string value is changed to a number, enabling proper use of the `$inc` operator.