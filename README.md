# Off-by-One Error in Java
This repository demonstrates a common off-by-one error in Java when iterating over an array. The error occurs in the loop condition, leading to an `ArrayIndexOutOfBoundsException`. The solution shows how to correct the condition to properly iterate over the array.

## Bug
The `Bug.java` file contains the buggy code.  The for loop attempts to access an array element outside of its bounds, resulting in a runtime exception.

## Solution
The `BugSolution.java` file provides a corrected version of the code that avoids the off-by-one error. The loop condition is modified to iterate only up to `arr.length - 1`, preventing the index from going out of bounds.