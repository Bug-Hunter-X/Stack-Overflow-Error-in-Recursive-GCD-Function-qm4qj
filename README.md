# Stack Overflow Error in Recursive GCD Function

This repository demonstrates a common error in recursive functions: stack overflow due to excessive recursion depth. The code implements the Euclidean algorithm for finding the greatest common divisor (GCD), but for large input numbers, the recursive calls can exceed the call stack limit.  The solution demonstrates how to improve this code with an iterative approach, avoiding stack overflow issues.

## Bug
The `bug.js` file contains the recursive GCD implementation that suffers from the stack overflow issue. 

## Solution
The `bugSolution.js` file offers an iterative version which eliminates the recursion and greatly improves performance for large inputs. This version uses a while loop to achieve the same functionality without exceeding the stack's capacity.