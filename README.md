# Algorithms

- [Bit Manipulation](#bit-manipulation)
- [Array](#array)
- [String](#string)
- [Linked List](#linked-list)
- [Stack](#stack)
- [Queue](#queue)
- [Heap](#heap)
- [Tree](#tree)
- [Hash Table](#hash-table)
- [Math](#math)
- [Two Pointers](#two-pointers)
- [Sort](#sort)
- [Recursion](#recursion)
- [Binary Search](#binary-search)
- [Binary Search Tree](#binary-search-tree)
- [Breadth-First Search](#breadth-first-search)
- [Depth-First Search](#depth-first-search)
- [Backtracking](#backtracking)
- [Dynamic Programming](#dynamic-programming)
- [Greedy](#greedy)
- [Graph](#graph)
- [Geometry](#geometry)
- [Simulation](#simulation)
- [Design](#design)
- [Concurrency](#concurrency)


# Array

| #       | Title                                                                                                                         | Solution                                                                                                          | Time         | Space         | Difficulty | Note               | Video Explaination                       |
| ------- | ----------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------- | ------------ | ------------- | ---------- | ------------------ | ---------------------------------------- |
| 118     | [Pascal's Triangle](https://leetcode.com/problems/pascals-triangle/)                                                          | [Java](./Java/PascalsTriangle118.java)                                                                            | _O(N^2)_     | _O(N)_        | Easy       |                    |                                          |
| 56      | [Merge Intervals](https://leetcode.com/problems/merge-intervals)                                                              | [Python](./Python/56_MergeIntervals.py)                                                                           | _O(nlogn)_   | _O(n)_        | Medium     | Intervals          |                                          |
| 268     | [Missing Number](https://leetcode.com/problems/missing-number)                                                                | [Java](./Java/missing-number.java)                                                                                | _O(n)_       | _O(1)_        | Easy       | Array              | [Tutorial](https://youtu.be/VwvGEE_OGss) |
| 697     | [Degree of an Array](https://leetcode.com/problems/degree-of-an-array)                                                        | [Java](./Java/Degree-of-an-Array.java)                                                                            | _O(n)_       | _O(n)_        | Easy       | Array              |                                          |
| 1089    | [Duplicate Zeroes](https://leetcode.com/problems/duplicate-zeros/)                                                            | [JavaScript](./JavaScript/Duplicate-Zeroes.js)                                                                    | _O(n)_       | _O(n)_        | Easy       | Array              |                                          |
| 1502    | [Can Make Arithmetic Progression From Sequence](https://leetcode.com/problems/can-make-arithmetic-progression-from-sequence/) | [Java](./Java/can-make-arithmetic-progression-from-sequence.java)                                                 | _O(n)_       | _O(1)_        | Easy       | Array              |                                          |
| 122     | [Best Time to buy and sell Stock II](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-ii)                        | [Python](./Python/best-time-to-buy-and-sell-stock-ii.py) <br> [C++](./C++/Best-Time-to-Buy-and-Sell-Stock-II.cpp) | _O(N)_       | _O(1)_        | Medium     | Stocks             |                                          |
| 119     | [Pascal's Triangle II](https://leetcode.com/problems/pascals-triangle-ii)                                                     | [Python](./Python/pascals-triangle-ii.py)                                                                         | _O(N^2)_     | _O(K)_        | Easy       |                    |                                          |
| 1480    | [Running Sum of 1d Array](https://leetcode.com/problems/running-sum-of-1d-array/)                                             | [Java](./Java/running-sum-of-1d-array.java)                                                                       | _O(N)_       | _O(N)_        | Easy       | Simple sum         |                                          |
| 42      | [Trapping Rain Water](https://leetcode.com/problems/trapping-rain-water/)                                                     | [Python](./Python/trapping_rain.py)                                                                               | _O(N^2)_     | _O(N)_        | Hard       | Array              |                                          |
| 11      | [Container with Most Water](https://leetcode.com/problems/container-with-most-water/)                                         | [Python](./Python/container_with_most_water.py)                                                                   | _O(N)_       | _O(N)_        | Medium     | Array Two Pointers |                                          |
| 1134 🔒 | [Armstrong Number](https://leetcode.com/problems/armstrong-number/)                                                           | [Java](./Java/Armstrong-Number.java)                                                                              | _O(N)_       | _O(1)_        | Easy       |                    |                                          |
| 1534    | [Count Good Triplets](https://leetcode.com/problems/count-good-triplets/)                                                     | [Python](./Python/count-good-triplets.py)                                                                         | _O(N^3)_     | _O(1)_        | Easy       |                    |                                          |
| 1572    | [Matrix Diagonal Sum](https://leetcode.com/problems/matrix-diagonal-sum/)                                                     | [Java](./Java/matrix-diagonal-sum.java)                                                                           | _O(N)_       | _O(1)_        | Easy       |                    |                                          |
| 811     | [Subdomain Visit Count](https://leetcode.com/problems/subdomain-visit-count/)                                                 | [Javascript](./JavaScript/Subdomain-Visit-Count.js)                                                               | _O(N\*M)_    | _O(N\*M + N)_ | Easy       |                    |                                          |
| 53      | [Maximum Subarray](https://leetcode.com/problems/maximum-subarray/)                                                           | [C++](./C++/maximum-subarray.cpp)                                                                                 | _O(N)_       | _O(1)_        | Easy       | Array              |                                          |
| 495     | [Teemo Attacking](https://leetcode.com/problems/teemo-attacking)                                                              | [C++](./C++/teemo-attacking.cpp)                                                                                  | _O(n)_       | _O(1)_        | Medium     | Array              |                                          |
| 15      | [3 Sum](https://leetcode.com/problems/3sum/)                                                                                  | [Python](./Python/ThreeNumbersSum.py)                                                                             | O( nLog(n) ) | O(1)          | Medium     | Array              |
| 1200    | [Minimum Absolute Difference](https://leetcode.com/problems/minimum-absolute-difference/)                                     | [Python](./python/SmallestDifference.py)                                                                          | O(n)         | O(1)          | Easy       | Array              |
| 532     | [K-diff Pairs in an Array](https://leetcode.com/problems/k-diff-pairs-in-an-array/)                                           | [C++](./C++/k-diff-pairs-in-an-array.cpp)                                                                         | O(n)         | O(n)          | Medium     | Array              |
| 152     | [Maximum Product Subarray](https://leetcode.com/problems/maximum-product-subarray/)                                           | [Javascript](./JavaScript/152.Maximum-Product-Subarray.js)                                                        | O(n)         | O(n)          | Medium     | Array              |
| 073     | [Set-Matrix-Zeroes](https://leetcode.com/problems/set-matrix-zeroes/)                                                         | [Java](./Java/set-matrix-zeroes.java)                                                                             | O(MN)        | O(1)          | Medium     | Array              |
| 1288    | [Remove-Covered-Intervals](https://leetcode.com/problems/remove-covered-intervals)                                            | [C++](./C++/Remove-Covered-Intervals.cpp)                                                                         | O(N\*N)      | O(1)          | Medium     | Array              |
| 189     | [Rotate-Array](https://leetcode.com/problems/rotate-array/)                                                                   | [Python](./Python/rotate-array.py)                                                                                | O(N)         | O(1)          | Medium     | Array              |
| 496     | [next-greater-element-i](https://leetcode.com/problems/next-greater-element-i)                                                | [Python](./Python/496_nextgreaterelement.py)                                                                      | O(N)         | O(1)          | Medium     | Array              |
| 1470    | [Shuffle the Array](https://leetcode.com/problems/shuffle-the-array)                                                          | [Java](./Java/shuffle-the-array.java)                                                                             | O(N)         | O(1)          | Easy       | Array              |
| 124     | [Permutation by Recussion](https://leetcode.com/problems/permutations/)                                                       | [Java](./Java/shuffle-the-array.java)                                                                             | O(N)         | O(N)          | Easy       | Array              |
| 283     | [Move-Zeroes](https://leetcode.com/problems/move-zeroes/)                                                                     | [C++](./C++/Move-Zeroes.cpp)                                                                                      | O(N)         | O(1)          | Easy       | Array              |
| 27      | [Remove-Element](https://leetcode.com/problems/remove-element/)                                                               | [C++](./C++/remove-element.cpp)                                                                                   | O(N)         | O(1)          | Easy       | Array              |
| 36      | [Valid Sudoku](https://leetcode.com/problems/valid-sudoku/)                                                                   | [Java](./Java/valid-sudoku.java)                                                                                  | O(N^2)       | O(N)          | Medium     | Array, 2D Matrix   |
| 1512    | [Number of Good Pairs](https://leetcode.com/problems/number-of-good-pairs/)                                                   | [Java](./Java/Number-of-Good-Pairs.java)                                                                          | O(N^2)       | O(1)          | Easy       | Array              |
| 162     | [Find Peak element](https://leetcode.com/problems/find-peak-element/)                                                         | [javascript](https://github.com/codedecks-in/LeetCode-Solutions/blob/master/JavaScript/findPeakElement.js)                                                                     | o(Logn)      | O(1)          | Medium     | Array              |
| 54     | [Spiral Matrix](https://leetcode.com/problems/spiral-matrix/)                                                         | [C++](./C++/Spiral-matrix.cpp)                                                                     | O(M\*N)      | O(M\*N)         | Medium     | Array              |
| 238     | [Product of Array Except Self](https://leetcode.com/problems/product-of-array-except-self/)                                                         | [C++](./C++/238.Product_of_array_except_self)                                                                   | O(N)      | O(N)         | Medium     | Array              |


<br/>

<div align="right">
    <b><a href="#algorithms">⬆️ Back to Top</a></b>
</div>
<br/>
