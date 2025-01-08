# MongoDB $inc Operator Bug

This repository demonstrates a common error when using the `$inc` operator in MongoDB: attempting to increment a counter with a string value.

The `bug.js` file shows the incorrect code, while `bugSolution.js` provides the correct implementation. The issue arises from the use of '1' (a string) instead of 1 (a number).