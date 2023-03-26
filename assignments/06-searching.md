# Videos:
- [Linear Search](https://youtu.be/_HRA37X8N_Q)
- [Binary Search](https://youtu.be/f6UU7V3szVw)
- [Binary Search Questions](https://youtu.be/W9QJ8HaRvJQ)
- [Binary Search in 2D Arrays](https://youtu.be/enI_KyGLYPo)

# Binary Search in 2D Array Video Is Helpful but Question 2 is Confusing. [(https://youtu.be/enI_KyGLYPo)]
# (Detailed Explaination of the Same code Theoretically, But By taking different target and different matrix example)
- Let's say we have a sorted two-dimensional matrix like this:
  1  2  3  4
  5  6  7  8
  9  10 11 12
  13 14 15 16
  
 - We want to search for the number 11 in this matrix.

The "search" method first initializes the number of rows and columns in the matrix. In this case, there are 4 rows and 4 columns.

Since the matrix has more than one row, the algorithm uses a modified binary search to narrow down the search space to two rows that may contain the target value. It starts by finding the middle row of the matrix, which is row 2.

It then checks if the middle element of this row (element 7) is less than, greater than, or equal to the target value. In this case, 7 is less than 11, so the algorithm narrows the search space to the bottom half of the matrix (rows 3 and 4).

It then checks if the target value is in the middle column of these two rows (column 2). In this case, the target value 11 is in the middle column of the bottom two rows, so the algorithm performs a binary search on these two rows to locate the target value.

It divides the matrix into four sections and performs a binary search on each section to locate the target value. In this case, the algorithm will first search the top-left section (elements 9 and 10), but since the target value 11 is greater than 10, it will move on to search the top-right section (elements 11 and 12). Since 11 is found in this section, the algorithm returns the row and column indices of the target value, which are [2, 2].

So the intuition behind the code is to use a modified binary search algorithm to narrow down the search space in a sorted two-dimensional matrix, and then perform a binary search on the narrowed-down space to locate the target value.


# Problems:

## Easy
- [Square Root](https://leetcode.com/problems/sqrtx/)
- [Guess Number Higher or Lower](https://leetcode.com/problems/guess-number-higher-or-lower/)
- [First Bad Version](https://leetcode.com/problems/first-bad-version/)
- [Two Sum II - Input array is sorted](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/)
- [Valid Perfect Square](https://leetcode.com/problems/valid-perfect-square/)
- [Arranging Coins(Easy)](https://leetcode.com/problems/arranging-coins/)
- [Find Smallest Letter Greater Than Target](https://leetcode.com/problems/find-smallest-letter-greater-than-target/)
- [Kth Missing Positive Number](https://leetcode.com/problems/kth-missing-positive-number/)
- [Search Insert Position](https://leetcode.com/problems/search-insert-position/)
- [Peak Index in a Mountain Array](https://leetcode.com/problems/peak-index-in-a-mountain-array/)
- [Count Negative Numbers in a Sorted Matrix](https://leetcode.com/problems/count-negative-numbers-in-a-sorted-matrix/)
- [Intersection of Two Arrays](https://leetcode.com/problems/intersection-of-two-arrays/)
- [Intersection of Two Arrays II](https://leetcode.com/problems/intersection-of-two-arrays-ii/)
- [Fair Candy Swap](https://leetcode.com/problems/fair-candy-swap/)
- [Check If N and Its Double Exist](https://leetcode.com/problems/check-if-n-and-its-double-exist/)
- [Special Array With X Elements Greater Than or Equal X](https://leetcode.com/problems/special-array-with-x-elements-greater-than-or-equal-x/)
- [Binary Search](https://leetcode.com/problems/binary-search/)

## Medium
- [Find First and Last Position of Element in Sorted Array](https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/)
- [Single Element in a Sorted Array](https://leetcode.com/problems/single-element-in-a-sorted-array/)
- [Search in Rotated Sorted Array](https://leetcode.com/problems/search-in-rotated-sorted-array/)
- [Search in Rotated Sorted Array II](https://leetcode.com/problems/search-in-rotated-sorted-array-ii/)
- [Find Minimum in Rotated Sorted Array](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/)
- [Find Peak Element](https://leetcode.com/problems/find-peak-element/)
- [Find Right Interval](https://leetcode.com/problems/find-right-interval/)
- [Reach a Number](https://leetcode.com/problems/reach-a-number/)
- [Maximum Value at a Given Index in a Bounded Array](https://leetcode.com/problems/maximum-value-at-a-given-index-in-a-bounded-array/)
- [Koko Eating Bananas](https://leetcode.com/problems/koko-eating-bananas/)
- [Minimum Absolute Sum Difference](https://leetcode.com/problems/minimum-absolute-sum-difference/)
- [Search a 2D Matrix](https://leetcode.com/problems/search-a-2d-matrix/)
- [Find a Peak Element II](https://leetcode.com/problems/find-a-peak-element-ii/)
- [Frequency of the Most Frequent Element](https://leetcode.com/problems/frequency-of-the-most-frequent-element/)
- [Find the Duplicate Number](https://leetcode.com/problems/find-the-duplicate-number/)
- [Capacity To Ship Packages Within D Days](https://leetcode.com/problems/capacity-to-ship-packages-within-d-days/)
- [4 Sum](https://leetcode.com/problems/4sum/)

## Hard
- [Median of Two Sorted Arrays](https://leetcode.com/problems/median-of-two-sorted-arrays/)
- [Find Minimum in Rotated Sorted Array II](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array-ii/)
- [Aggressive cows](https://www.spoj.com/problems/AGGRCOW/)
- [Book allocation](https://www.geeksforgeeks.org/allocate-minimum-number-pages/)
- [Split Array Largest Sum](https://leetcode.com/problems/split-array-largest-sum/)
- [Find in Mountain Array](https://leetcode.com/problems/find-in-mountain-array/)
- [Count smaller number after Self](https://leetcode.com/problems/count-of-smaller-numbers-after-self/)
- [Divide Chocolate Problem](https://curiouschild.github.io/leetcode/2019/06/21/divide-chocolate.html)
