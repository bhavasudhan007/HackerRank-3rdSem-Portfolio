# Diagonal Difference

## Problem
Calculate the absolute difference between the sums of the primary and secondary diagonals of a square matrix.

## Approach
Traverse the matrix once. For each row, add the element at `arr[i][i]` to the primary diagonal sum and `arr[i][n-1-i]` to the secondary diagonal sum. Return the absolute difference between the two sums.

## Complexity
- Time: O(N)
- Space: O(1)