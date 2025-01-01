# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over arrays.  The error occurs because the loop condition `i <= arr.length` is incorrect. Array indices are zero-based, so the valid indices range from 0 to `arr.length - 1`.

The `bug.java` file contains the code with the error. Running this code will result in an `ArrayIndexOutOfBoundsException`. The `bugSolution.java` file provides the corrected code.

This example highlights the importance of careful attention to loop boundaries when working with arrays in Java (and other programming languages).