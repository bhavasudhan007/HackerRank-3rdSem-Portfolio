# Dynamic Array

## Problem
Process queries on multiple dynamic sequences and return the required values based on the query operations.

## Approach
Maintain a vector of sequences. For each query, calculate the sequence index using XOR between `x` and `lastAnswer`. Type 1 queries append a value, while type 2 queries retrieve a value and update `lastAnswer`.

## Complexity
- Time: O(Q) average
- Space: O(N + Q)