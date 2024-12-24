# Off-by-one error in array iteration
This code demonstrates a common off-by-one error in Java when iterating over an array. The for loop condition `i <= arr.length` causes an `ArrayIndexOutOfBoundsException` because valid indices range from 0 to `arr.length -1`.