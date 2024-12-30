# Julia Function Bug

This repository demonstrates a simple bug in a Julia function related to handling negative numbers. The function `myfunction` is intended to return the square of its input, but it produces incorrect results when the input is negative. The solution shows how to fix the bug.

## Bug

The bug is caused by the incorrect handling of negative numbers in the conditional statement.  The function should always return the square of the input, regardless of its sign.

## Solution

The solution involves modifying the return statement to always calculate the square of the absolute value of the input, ensuring a positive result regardless of the input's sign. 
