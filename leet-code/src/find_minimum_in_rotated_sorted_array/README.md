Find Minimum in Rotated Sorted Array
===

Suppose a sorted array is rotated at some pivot unknown to you beforehand.

(i.e., 0 1 2 4 5 6 7 might become 4 5 6 7 0 1 2).

Find the minimum element.

You may assume no duplicate exists in the array.

Solution
===
Binary search, discuss the possibility of the segment under watch

Follow up
===
If duplicates are allowed, shift the windown of search by one, this will definitely harm the performance if a lot of duplicates are found. 
