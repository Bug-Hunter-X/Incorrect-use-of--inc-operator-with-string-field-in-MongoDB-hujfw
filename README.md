# Incorrect use of $inc operator with string field in MongoDB
This example demonstrates an incorrect usage of the `$inc` operator in MongoDB. The `$inc` operator is designed to increment numeric fields, but attempting to use it with a string field will lead to errors or unexpected behavior.

## Bug
The bug lies in the use of `$inc` with a string field.  The correct usage requires a numeric field.

## Solution
Ensure that the field you are using with the `$inc` operator is of numeric type (int, long, or double).