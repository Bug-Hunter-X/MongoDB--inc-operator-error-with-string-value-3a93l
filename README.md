# MongoDB $inc Operator Error

This repository demonstrates a common error when using the `$inc` operator in MongoDB updates.  The `$inc` operator is designed to increment a numeric field, but passing a string value will lead to an error.

## Bug
The `bug.js` file shows the incorrect usage of the `$inc` operator, where a string '1' is passed. This will result in a MongoDB error indicating that the increment value must be a number.

## Solution
The `bugSolution.js` file demonstrates the corrected approach.  The increment value is now a number, resulting in a successful update operation.