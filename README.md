# MongoDB $inc Operator Error
This example demonstrates an incorrect usage of the `$inc` operator in MongoDB, which results in an error when attempting to increment a numerical field with a string value. The solution shows the correct implementation, where the increment value is a number.

## Bug
The bug lies in the incorrect usage of the `$inc` operator in a MongoDB update query.  The `counter` field should be incremented by a numerical value (e.g., 1), but instead, a string value ('1') is provided which leads to an error. 

## Solution
The solution shows the corrected code where the value provided for increment is a valid number.