# HW1 Shane DeSilva

This program defines a function that takes in a list of numpy arrays and returns a numpy array of all of them multiplied in their original order.

This program will raise a custom *DimensionMismatchError* exception whenever the inner dimension of two consecutive matrices do not match.

Consecutive matrices need to be of the form
$M_{mxn} * M_{nxm} $ in order to be multiplied sucessfully.

An example of when an exception will be raised would be $M_{2x3} * M_{4x3} $. This is invalid since 3 and 4 do not match.
