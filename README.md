# Problem Statement

You are given two integer arrays nums1 and nums2, sorted in non-decreasing order, and two integers m and n, representing the number of elements in nums1 and nums2 respectively.</br>

Merge nums1 and nums2 into a single array sorted in non-decreasing order.</br>

The final sorted array should not be returned by the function, but instead be stored inside the array nums1. To accommodate this, nums1 has a length of m + n, where the first m elements denote the elements that should be merged, and the last n elements are set to 0 and should be ignored. nums2 has a length of n.</br>


## Example
```
Input: nums1 = [1,2,3,4,5,6], m = 3, nums2 = [2,5,6], n = 3
Output: [1,2,2,3,5,6]
Explanation: The arrays we are merging are [1,2,3] and [2,5,6].
The result of the merge is [1,2,2,3,5,6] with the underlined elements coming from nums1.
```

# Constraints
-5 * 10<sup>4</sup> <= data[i] <= 5 * 10<sup>4</sup>

## Sample Input - 1
```
1, 2, 3, 4, 5, 6
7, 8, 9
4
2

First line represents nums1
Second line represents nums2
Third line represents m
Fourth line represents n
```
## Sample Output - 1
```
[1, 2, 3, 4, 7, 8]
```
## Sample Input - 2
```
7, 8, 9, 10, 11, 12
1, 2, 3, 4
4
2
```
## Sample Output - 2
```
[1, 2, 7, 8, 9, 10]
```
