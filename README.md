# MongoDB $inc Operator Bug
This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations.  The incorrect usage of a string instead of a number with `$inc` results in unexpected results. The solution shows the correct usage.

## Bug
The provided `bug.js` file showcases an incorrect update operation using the `$inc` operator. Specifically, it attempts to increment the 'count' field by '1' which is a string. This leads to unexpected behavior and may not increment the count as intended.

## Solution
The `bugSolution.js` file demonstrates the correct way to use the `$inc` operator.  It uses a numeric value (1) to increment the 'count' field, ensuring the intended behavior is achieved.
