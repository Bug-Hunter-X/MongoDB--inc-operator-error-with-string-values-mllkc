# MongoDB $inc operator error with string values
This repository demonstrates an uncommon error related to the MongoDB $inc operator. The error occurs when attempting to increment a field using a string value instead of a number.
## Bug Description
The $inc operator in MongoDB is used to increment a numerical field in a document. However, passing a string value as the increment amount will result in an error. The correct usage is to provide a number.
## Solution
The solution is to ensure that the value passed to the $inc operator is a number. This can be achieved by explicitly converting the value to a number if necessary.