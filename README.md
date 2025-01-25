# MongoDB $inc operator error
This repository demonstrates an incorrect usage of the `$inc` operator in MongoDB update operations. The `$inc` operator is used to increment a numeric field by a specified value. However, if the value is not a number, the operation will fail.

## Bug
The `bug.js` file contains the incorrect code that causes the error. The value parameter in the `$inc` operator is a string, which is not a valid numeric value.

## Solution
The `bugSolution.js` file demonstrates the corrected code. The value parameter in the `$inc` operator is a number, which is a valid numeric value.