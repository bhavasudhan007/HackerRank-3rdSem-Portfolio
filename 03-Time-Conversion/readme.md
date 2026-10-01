# Time Conversion

## Problem
Convert a 12-hour AM/PM time format into 24-hour time format.

## Approach
Extract the hour and determine whether the time is AM or PM. Convert 12 AM to 00, add 12 to PM hours except 12 PM, and preserve the minutes and seconds.

## Complexity
- Time: O(1)
- Space: O(1)