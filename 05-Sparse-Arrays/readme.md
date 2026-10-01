# Sparse Arrays

## Problem
Count how many times each query string occurs in the given string list.

## Approach
Use an unordered map to store the frequency of every string in `stringList`. For each query, directly retrieve its frequency from the map.

## Complexity
- Time: O(N + Q) average
- Space: O(N)