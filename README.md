# MongoDB $inc Operator Error: Using String Increment Value
This repository demonstrates an uncommon error related to the MongoDB $inc operator. The error occurs when a string value is used for incrementing a numeric field, which leads to unexpected results.  The solution shows the correct usage of $inc with numeric values.

## Bug
The `$inc` operator is used incorrectly by providing a string value instead of a numeric value. This causes the update operation to fail silently or produce incorrect results. This is a subtle error that might be difficult to debug.

## Solution
The solution demonstrates the correct usage of the `$inc` operator with a numeric value.