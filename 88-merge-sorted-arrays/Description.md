# 88. Merge Sorted Arrays

https://leetcode.com/problems/merge-sorted-array/

## Solution Notes

Trick here is to traverse arrays from the end and not from the beginning. Since the maximum number of both arrays will be the last, you can put it to the last element.

## Characteristics

- Time O(m + n)
- Space O(1)