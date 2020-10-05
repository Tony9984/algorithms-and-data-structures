# Algorithms and Data Structures

![](https://miro.medium.com/proxy/1*_gg1Te-7SJfk9E2D-mORfw.png)

![](https://img.shields.io/npm/v/dsa-ts)
[![Tests](https://github.com/jeffzh4ng/dsa-ts/workflows/Tests/badge.svg)](https://github.com/jeffzh4ng/algorithms-and-data-structures/actions?query=branch%3Amaster++)
![](https://img.shields.io/codecov/c/github/jeffzh4ng/dsa-ts)
![](https://img.shields.io/github/license/jeffzh4ng/algorithms-and-data-structures)

A collection of classical [data structures](https://github.com/jeffzh4ng/dsa-ts#data-structures) and [algorithms](https://github.com/jeffzh4ng/dsa-ts#algorithms) implemented in Typescript. Click the 📹 emoji for tutorials.

Data structure series: [View the entire series in order here](https://www.youtube.com/watch?v=CjVFSWchhEo&list=PLn4fTSbSpY5cL4_0MP83wq5khbmG3IKKd).

Algorithms/leetcode series: [View the entire series in order here](https://www.youtube.com/watch?v=GP1iUOVmAnY&list=PLn4fTSbSpY5fN2gxiU8VmOKo3255vlDkS)

The repository's primary goal is educational. Hence, all implementations include a prolific number of comments which guide the reader.

You can use this package in your projects if you so wish. Test coverage will be kept at 100%. To install the package, use npm or yarn:

```
npm install dsa-ts --save
```

```
yarn add dsa-ts
```

## Data Structures

- [x] Sequences
  - [x] [📹](https://www.youtube.com/watch?v=oXXLFvtG6-Q&list=PLn4fTSbSpY5cL4_0MP83wq5khbmG3IKKd&index=5) [Linked List](https://github.com/jeffzh4ng/dsa-ts/blob/master/src/data-structures/sequences/linked-list/linked-list.ts)
  - [x] [📹](https://www.youtube.com/watch?v=7l4YHzc3iXU&list=PLn4fTSbSpY5cL4_0MP83wq5khbmG3IKKd&index=7) [Stack](https://github.com/jeffzh4ng/dsa-ts/tree/master/src/data-structures/sequences/stack/stack.ts)
  - [x] [📹](https://www.youtube.com/watch?v=E1I8IcKv_cQ&list=PLn4fTSbSpY5cL4_0MP83wq5khbmG3IKKd&index=9) [Queue](https://github.com/jeffzh4ng/dsa-ts/blob/master/src/data-structures/sequences/queue/queue.ts)
  - [x] [Double-ended Queue](https://github.com/jeffzh4ng/dsa-ts/blob/master/src/data-structures/sequences/queue/deque.ts)
  - [x] [📹](https://www.youtube.com/watch?v=39HHWATPcwY&list=PLn4fTSbSpY5cL4_0MP83wq5khbmG3IKKd&index=11) [Circular Buffer](https://github.com/jeffzh4ng/dsa-ts/blob/master/src/data-structures/sequences/circular-buffer/circular-buffer.ts)
- [x] Priority Queues
  - [x] [📹](https://www.youtube.com/watch?v=xpSa8YOqeWQ&list=PLn4fTSbSpY5cL4_0MP83wq5khbmG3IKKd&index=13) [Binary Heap](https://github.com/jeffzh4ng/dsa-ts/blob/master/src/data-structures/priority-queues/min-binary-heap.ts)
  - [x] [D-Heap](https://github.com/jeffzh4ng/dsa-ts/blob/master/src/data-structures/priority-queues/min-d-heap.ts)
  - [x] [📹](https://www.youtube.com/watch?v=TlYPo28sw9E) [Indexed Binary Heap](https://github.com/jeffzh4ng/dsa-ts/blob/master/src/data-structures/priority-queues/min-indexed-d-heap.ts)
  - [x] Mergeable Heaps
    - [x] [📹](https://www.youtube.com/watch?v=m8rsw3KfDKs&list=PLn4fTSbSpY5cL4_0MP83wq5khbmG3IKKd&index=17) [Binomial Heap](https://github.com/jeffzh4ng/algorithms-and-data-structures/blob/master/src/data-structures/priority-queues/mergeable-heaps/min-binomial-heap.ts)
    - [x] [📹](https://www.youtube.com/watch?v=-IOse-LEJtw&list=PLn4fTSbSpY5cL4_0MP83wq5khbmG3IKKd&index=19) [Lazy Binomial Heap](https://github.com/jeffzh4ng/algorithms-and-data-structures/blob/master/src/data-structures/priority-queues/mergeable-heaps/lazy-min-binomial-heap.ts)
    - [x] [📹](https://www.youtube.com/watch?v=E_AgyAI8lsc&list=PLn4fTSbSpY5cL4_0MP83wq5khbmG3IKKd&index=23) [Fibonnaci Heap](https://github.com/jeffzh4ng/algorithms-and-data-structures/blob/master/src/data-structures/priority-queues/mergeable-heaps/min-fibonacci-heap.ts)
- [x] Search Trees
  - [x] [📹](https://www.youtube.com/watch?v=zEOWjb7wDik&list=PLn4fTSbSpY5cL4_0MP83wq5khbmG3IKKd&index=24) [Binary Search Tree](https://github.com/jeffzh4ng/algorithms-and-data-structures/blob/master/src/data-structures/trees/binary-search-tree/index.ts)
  - [x] [📹](https://www.youtube.com/watch?v=ietVegtgG_s&list=PLn4fTSbSpY5cL4_0MP83wq5khbmG3IKKd&index=25) [AVL Tree](https://github.com/jeffzh4ng/algorithms-and-data-structures/blob/master/src/data-structures/trees/avl-tree/index.ts)
  - [x] [Red-black Tree](https://github.com/jeffzh4ng/algorithms-and-data-structures/blob/master/src/data-structures/trees/red-black-tree/index.ts)
  - [x] [B-Tree](https://github.com/jeffzh4ng/algorithms-and-data-structures/blob/master/src/data-structures/trees/b-tree/b-tree.ts)
- [x] Hash Tables
  - [x] [📹](https://www.youtube.com/watch?v=_lJFWYFroYs&list=PLn4fTSbSpY5cL4_0MP83wq5khbmG3IKKd&index=26) [Hash Table (Separate Chaining)](https://github.com/jeffzh4ng/algorithms-and-data-structures/blob/master/src/data-structures/hash-tables/hash-table-separate-chaining.ts)
  - [x] [Hash Table (Open Addressing)](https://github.com/jeffzh4ng/algorithms-and-data-structures/blob/master/src/data-structures/hash-tables/hash-table-open-addressing-base.ts)
    - [x] [Hash Table (Linear Probing)](https://github.com/jeffzh4ng/algorithms-and-data-structures/blob/master/src/data-structures/hash-tables/hash-table-linear-probing.ts)
    - [x] [Hash Table (Quadratic Probing)](https://github.com/jeffzh4ng/algorithms-and-data-structures/blob/master/src/data-structures/hash-tables/hash-table-quadratic-probing.ts)
    - [x] [Hash Table (Double Hashing)](https://github.com/jeffzh4ng/algorithms-and-data-structures/blob/master/src/data-structures/hash-tables/hash-table-double-hashing.ts)

## Algorithms

Following algoritms/problems compiled from Grokking, EPI, and AlgoExpert

- [Array](https://github.com/jeffzh4ng/algorithms-and-data-structures#array)
- [Sliding Window](https://github.com/jeffzh4ng/algorithms-and-data-structures#sliding-window)
- [Two Pointers](https://github.com/jeffzh4ng/algorithms-and-data-structures#two-pointers)
- [Fast and Slow Pointers](https://github.com/jeffzh4ng/algorithms-and-data-structures#fast-and-slow-pointers)
- [Binary Search](https://github.com/jeffzh4ng/algorithms-and-data-structures#binary-search)
- [Merge Intervals](https://github.com/jeffzh4ng/algorithms-and-data-structures#merge-intervals)
- [Cyclic Sort](https://github.com/jeffzh4ng/algorithms-and-data-structures#cyclic-sort)
- [String](https://github.com/jeffzh4ng/algorithms-and-data-structures#string)
- [Linked List](https://github.com/jeffzh4ng/algorithms-and-data-structures#linked-list)
- [Linked List Reversal](https://github.com/jeffzh4ng/algorithms-and-data-structures#linked-list-reversal)
- [Tree](https://github.com/jeffzh4ng/algorithms-and-data-structures#tree)
- [Tree BFS](https://github.com/jeffzh4ng/algorithms-and-data-structures#tree-breadth-first-search)
- [Tree DFS](https://github.com/jeffzh4ng/algorithms-and-data-structures#tree-depth-first-search)
- [Stacks/Queues/Monotonic Queues](https://github.com/jeffzh4ng/algorithms-and-data-structures#stackqueuesmonotonic-queues)
- [Two Heaps](https://github.com/jeffzh4ng/algorithms-and-data-structures#two-heaps)
- [Top K Elements](https://github.com/jeffzh4ng/algorithms-and-data-structures#top-k-elements)
- [K-way Merge](https://github.com/jeffzh4ng/algorithms-and-data-structures#k-way-merge)
- [Design](https://github.com/jeffzh4ng/algorithms-and-data-structures#design)
- [Backtracking](https://github.com/jeffzh4ng/algorithms-and-data-structures#backtracking)
- [Greedy](https://github.com/jeffzh4ng/algorithms-and-data-structures#greedy)
- [Topological Sort](https://github.com/jeffzh4ng/algorithms-and-data-structures#topological-sort)
- [Union Find](https://github.com/jeffzh4ng/algorithms-and-data-structures#union-find)
- [Tries](https://github.com/jeffzh4ng/algorithms-and-data-structures#tries)
- [Bit Manipulation](https://github.com/jeffzh4ng/algorithms-and-data-structures#bit-manipulation)

### Array
  - [] 509. Fibonacci Number (Easy)
  - [] 896. Monotonic Array (Easy)
  - [] 238. Product of Array Except Self (Medium)
  - [] 48. Rotate Image (Medium)
  - [] 33. Search in Rotated Sorted Array (Medium)
  - [] 34. Find First and Last Position of Element in Sorted Array (Medium)
  - [] 189. Rotate Array (Easy)
  - [] 118. Pascal's Triangle (Easy)
  - [] 54. Spiral Matrix (Medium)
  - [] 280. Wiggle Sort (Medium)
  - [] 36. Valid Sodoku (Medium)
  - [] 48. Rotate Image (Medium)
  - [] 4. Median of Two Sorted Arrays (Hard)
  - [] 84. Largest Rectangle in Histogram (Hard)
  - [] 1200. Minimum Absolute Difference (Easy)

### Sliding Window
  - [] 209. Minim Size Subarray Sum (Medium)
  - [] 904. Fruit Into Baskets (Medium)
  - [] 3. Longest Substring Without Repeating Characters (Medium)
  - [] 1004. Max Consecutive Ones III (Medium)
  - [] 567. Permutation in String (Medium)
  - [] 438. Find All Anagrams in a String (Medium)
  - [] 46. Minimum Window Substring (Hard)
  - [] 76. Minimum Window Substring (Hard)
  - [] 239. Sliding Window Maximum (Hard)
  
### Two Pointers
  - [] 167. Two Sum II (Easy)
  - [] 283. Move Zeroes
  - [] 26. Remove Duplicates from Sorted Array (Easy)
  - [] 977. Squares of a Sorted Array (Easy)
  - [] 15. 3Sum (Medium)
  - [] 16. 3Sum Closest (Medium)
  - [] 713. Subarray Product Less than K (Medium)
  - [] 75. Sort Colors (Medium)
  - [] 18. 4Sum (Medium)
  - [] 845. Longest Mountain in Array (Medium)
  - [] 844. Backspace String Compare (Easy)
  - [] 581. Shortest Unsorted Continuous Subarray (Easy)
  
### Fast and Slow Pointers
  - [] 141. Linked List Cycle (Easy)
  - [] 142. Linked List Cycle II (Easy)
  - [] 876. Middle of the Linked List (Easy)
  - [] 234. Palindrome Linked List (Easy)
  - [] 143. Reorder List (Medium)
  - [] 457. Circular Array Loop (Medium)
  
 
### Binary Search
  - [x] 74. Search a 2D Matrix (Medium)
  - [x] 240. Search a 2D Matrix II (Medium)
  - [x] [📹 454. 4Sum II (Medium)](https://www.youtube.com/watch?v=i-tPlqTdLfo&list=PLn4fTSbSpY5fN2gxiU8VmOKo3255vlDkS&index=2)
  - [x] [📹 875. Koko Eating Bananas (Medium)](https://www.youtube.com/watch?v=i-eMqfWx5M4&list=PLn4fTSbSpY5fN2gxiU8VmOKo3255vlDkS&index=3)
  
### Merge Intervals
  - [x] [📹 56. Merge Intervals (Medium)](https://www.youtube.com/watch?v=LhBpbPM4Vy8&list=PLn4fTSbSpY5fN2gxiU8VmOKo3255vlDkS&index=4)
  - [x] [📹 57. Insert Interval (Hard)](https://www.youtube.com/watch?v=_OJ8rRuFv7Y&list=PLn4fTSbSpY5fN2gxiU8VmOKo3255vlDkS&index=5)
  - [x] 252 Meeting Rooms (Easy)
  - [x] [📹 253. Meeting Rooms II (Medium)](https://www.youtube.com/watch?v=UW8ocElp8nM&list=PLn4fTSbSpY5fN2gxiU8VmOKo3255vlDkS&index=6)
  - [x] [📹 452. Minimum Number of Arrows to Burst Balloons (Medium)](https://www.youtube.com/watch?v=lslPyeA3njw&list=PLn4fTSbSpY5fN2gxiU8VmOKo3255vlDkS&index=7)
  - [x] [📹 986. Interval List Intersection (Medium)](https://www.youtube.com/watch?v=_Ckxjssi4sg&list=PLn4fTSbSpY5fN2gxiU8VmOKo3255vlDkS&index=8)
  
### Cyclic Sort
  - [x] [📹 268. Missing Number (Easy)](https://www.youtube.com/watch?v=osFsID7ntNQ&list=PLn4fTSbSpY5fN2gxiU8VmOKo3255vlDkS&index=9)
  - [x] 448. Find All Numbers Disappeared in an Array (Easy)
  - [x] [📹 287. Find the Duplicate Number (Medium)](https://www.youtube.com/watch?v=qp0KJNVFIEE&list=PLn4fTSbSpY5fN2gxiU8VmOKo3255vlDkS&index=10)
  - [x] [📹 442. Find All Duplicates in an Array (Medium)](https://www.youtube.com/watch?v=1g9pY9JAeps&list=PLn4fTSbSpY5fN2gxiU8VmOKo3255vlDkS&index=11)
  - [x] 41. First Missing Positive (Hard)
  
### String
  - [x] [📹 20. Valid Parentheses (Easy)](https://www.youtube.com/watch?v=9Vt-gL8xtZY&list=PLn4fTSbSpY5fN2gxiU8VmOKo3255vlDkS&index=12)
  - [x] [📹 680. Valid Palindrome II (Easy)](https://www.youtube.com/watch?v=P-o3YmU-kmw&list=PLn4fTSbSpY5fN2gxiU8VmOKo3255vlDkS&index=13)
  - [x] [📹 557. Reverse Words in a String III (Easy)](https://www.youtube.com/watch?v=G7OgFehqJ5U&list=PLn4fTSbSpY5fN2gxiU8VmOKo3255vlDkS&index=15)
  - [x] [📹 929. Unique Email Addresses (Easy)](https://www.youtube.com/watch?v=vBSanEn25AE&list=PLn4fTSbSpY5fN2gxiU8VmOKo3255vlDkS&index=17&t=4s)
  - [x] 459. Repeated Substring Pattern (Easy)
  - [x] [📹 415. Add Strings (Easy)](https://www.youtube.com/watch?v=bhwvkq3ha-I&list=PLn4fTSbSpY5fN2gxiU8VmOKo3255vlDkS&index=17)
  - [x] 14. Longest Common Prefix (Easy)
  - [x] 583. Delete Operation for Two Strings (Medium)
  - [x] 767. Reorganize String (Medium)
  - [x] 856. Score of Parentheses (Medium)
  - [x] 1249. Minimum Remove to Make Valid Parentheses (Medium)
  - [x] 1268. Search Suggestions System (Medium)
  - [x] 791. Custom Sort String (Medium)
  - [x] 890. Find and Replace Pattern (Medium)
  - [x] 678. Valid Parenthesis String (Medium)
  - [x] 227. Basic Calculator II (Medium)
  - [x] 49. Group Anagrams (Medium)
  - [x] 214. Shortest Palindrome (Hard)
  - [x] 632. Smallest Range Covering Elements from K Lists (Hard)
  
### Linked List
  - [x] 21. Merge Two Sorted Lists (Easy)
  - [x] 160. Intersection of Two Linked Lists (Easy)
  - [x] 83. Remove Duplicates from Sorted List (Easy)
  - [x] 19. Remove Nth Node From End of List (Medium)
  - [x] 138. Copy List with Random Pointer (Medium)
  - [x] 19. Remove Nth Node from End of List (Medium)
  - [x] 2. Add Two Numbers (Medium)
  - [x] 138. Copy List with Random Pointer (Medium)
  - [x] 234. Palindrome Linked List (Easy)
  - [x] 86. Partition List (Medium)
  
### Linked List Reversal
  - [x] 206. Reverse Linked List (Easy)
  - [x] 92. Reverse Linked List II (Medium)
  - [x] 61. Rotate List (Medium)
  - [x] 24. Swap Nodes in Pairs (Medium)
  - [x] 328. Odd Even Linked List (Medium)
  - [x] 25. Reverse Nodes in k-Group (Hard)
  
### Tree
  - [x] 617. Merge Two Binary Trees (Easy)
  - [x] 226. Invert Binary Tree (Easy)
  - [x] 110. Balanced Binary Tree (Easy)
  - [x] 101. Symmetric Tree (Easy)
  - [x] 94. Binary Tree Inorder Traversal (Medium)
  - [x] 144. Binary Tree Preorder Traversal (Medium)
  - [x] 145. Binary Tree Postorder Traversal (Hard)
  - [x] 236. Lowest Common Ancestor of a Binary Tree (Medium)
  - [x] 297. Serialize and Deserialize Binary Tree (Hard)
  - [x] 145. Binary Tree Postorder Traversal Tree (Hard)
  
### Tree Breadth First Search
  - [x] 101. Symmetric Tree (Easy)
  - [x] 102. Binary Tree Level Order Traversal (Medium)
  - [x] 107. Binary Tree Level Order Traversal II (Easy)
  - [x] 103. Binary Tree Zigzag Level Order Traversal (Medium)
  - [x] 637. Average of Levels in Binary Tree (Easy)
  - [x] 111. Minimum Depth of Binary Tree (Easy)
  - [x] 104. Maximum Depth of Binary Tree (Easy)
  - [x] 116. Populating Next Right Pointers in Each Node (Medium)
  - [x] 199. Binary Tree Right Side View (Medium)
  
### Tree Depth First Search
  - [x] 112. Path Sum (Easy)
  - [x] 100. Same Tree (Easy)
  - [x] 113. Path Sum II (Medium)
  - [ ] 437. Path Sum III (Easy)
  - [ ] 105. Construct Binary Tree from Preorder and Inorder Traversal (Medium)
  - [ ] 114. Flatten Binary Tree to Linked List (Medium)
  - [ ] 129. Sum Root to Leaf Numbers (Medium)
  - [ ] 543. Diameter of a Binary Tree (Easy)
  - [ ] 124. Binary Tree Maximum Path Sum (Hard)
  - [ ] 98. Validate Binary Search Tree (Medium)
  - [ ] 1028. Recover a Tree From Preorder Traversal (Hard)
  
### Stack/Queues/Monotonic Queues
  - [x] 496. Next Greater Element I (Easy)	
  - [x] 503. Next Greater Element II (Medium)
  - [x] 901. Online Stock Span (Medium)
  - [x] 739. Daily Temperatures (Medium)
  - [ ] 907. Sum of Subarray Minimums (Medium)
  - [ ] 456. 132 Pattern (Medium)
  - [ ] 42. Trapping Rain Water (Hard)
  - [ ] 862. Shortest Subarray with Sum at Least K (Hard)
  - [ ] 84. Largest Rectangle in Histogram (Hard)
  - [ ] 239. Sliding Window Maximum (Hard)
  - [ ] 891. Sum of Subsequence Widths (Hard)	
  
### Two Heaps
  - [x] 295. Find Median from Data Stream (Hard)
  - [x] 502. IPO (Hard)
  
### Top K Elements
  - [x] 215. Kth Largest Element in an Array (Medium)
  - [x] 347. Top K Frequent Elements (Medium)
  - [x] 973. K Closest Points to Origin (Medium)
  - [x] 451. Sort Characters by Frequency (Medium)
  - [x] 767. Reorganize String (Medium)
  - [ ] 658. Find K Closest Elements (Medium)
  - [ ] 692. Top K Frequent Words (Medium)
  - [ ] 621. Task Scheduler (Medium)
  - [x] 895. Maximum Frequency Stack (Hard)
  - [ ] 1000. Minimum Cost to Merge Stones (Hard)
  
### K-way Merge
  - [ ] 23. Merge K Sorted Lists (Hard)
  - [ ] 378. Kth Smallest Element in a Sorted Matrix (Medium)
  - [ ] 373. Find K Pairs with Smallest Sums (Medium)
  
### Design
  - [ ] 146. LRU Cache (Medium)
  - [ ] 155. Min Stack (Easy)
  - [ ] 622. Design Circular Queue (Medium)
  - [ ] 232. Implement Queue using Stacks (Easy)
  - [ ] 211. Add and Search Word - Data structure design (Medium)
  - [ ] 705. Design HashSet (Easy)
  - [ ] 297. Serialize and Deserialize Binary Tree (Hard)
  
### Backtracking
  - [x] 78. Subsets (Easy)
  - [x] 90. Subsets II (Medium)
  - [x] 46. Permutations (Medium)
  - [x] 47. Permutations II (Medium)
  - [x] 60. Permutation Sequence (Hard)
  - [x] 22. Generate Parentheses (Hard)
  - [x] 39. Combination Sum (Medium)
  - [x] 40. Combinatin Sum II (Medium)
  - [x] 216. Combination Sum III (Medium)
  - [x] 77. Combinations (Medium)
  - [x] 526. Beautiful Arrangement (Medium)
  - [x] 784. Letter Case Permutation (Easy)
  - [x] 980. Unique Paths III (Hard)
  - [x] 131. Palindrome Partitioning (Medium)
  - [x] 17. Letter Combinations of a Phone Number (Medium)
  - [x] 51. N-Queens (Hard)
  - [x] 37. Sudoker Solver (Hard)
  - [x] 79. Word Search (Medium)
  - [x] 212. Word Search II (Hard)
 
### Greedy
  - [ ] 763. Partition Labels (Medium)
  - [ ] 407. Queue Reconstruction by Height (Medium)
  - [ ] 1046. Last Stone Weight (Easy)
  - [ ] 1029. Two City Scheduling (Easy)
  - [ ] 621. Task Scheduler (Medium)
  - [ ] 767. Reorganize String (Medium)
  - [ ] 435. Non-overlapping Intervals (Medium)
  - [ ] 134. Gas Station (Medium)
  - [ ] 55. Jump Game (Medium)
  - [ ] 45. Jump Game II (Hard)
  - [ ] 630. Course Schedule III (Hard)
  - [ ] 135. Candy (Hard)
  - [ ] 402. Remove K Digits (Medium)
  - [ ] 314. Remove Duplicate Letters (Hard)
  - [ ] 765. Couples Holding Hands (Hard)

### Topological Sort
  - [ ] 207. Course Schedule (Medium)
  - [ ] 210. Course Schedule II (Medium)
  - [ ] 269. Alien Dictionary (Hard)
  - [ ] 444. Sequence Reconstruction (Hard)
  - [ ] 310. Minimum Height Trees (Medium)

### Union Find
  - [ ] 128. Longest Consecutive Sequence (Hard)
  - [ ] 200. Number of Islands (Medium)
  - [ ] Graph Valid Tree
  - [ ] Number of Connected Components in an Undirected Graph
  
### Tries
  - [ ] 208. Implement Trie (Prefix Tree) (Medium)
  - [ ] 676. Implement Magic Dictionary (Medium)
  - [ ] 677. Map Sum Pairs (Medium)
  - [ ] 648. Replace Words (Medium)
  - [ ] 421. Maximum XOR of Two Numbers in an Array (Medium)
  - [ ] 692. Top K Frequent Words (Medium)
  - [ ] 1032. Stream of Characters (Hard)
  - [ ] 212. Word Search II (Hard)
  - [ ] 472. Concatenated Words (Hard)
  - [ ] 336. Palindrome Pairs (Hard)
  - [ ] Index Pairs of a String
  - [ ] Design Search Autocomplete System	
  - [ ] Word Squares
  
### Bit Manipulation
  - [ ] 231. Power of Two (Easy)
  - [ ] 201. Bitwise AND of Numbers Range (Easy)
  - [ ] 461. Hamming Distance (Easy)
  - [ ] 338. Counting Bits (Medium)
  - [ ] 136. Single Number (Easy)
  - [ ] 137. Single Number II (Medium)
  - [ ] 260. Single Number III (Medium)
  - [ ] 1109. Complement of Base 10 Integer (Easy)
  - [ ] 832. Flipping an Image (Easy)
  - [ ] 476. Number Complement (Easy)
  - [ ] 784. Letter Case Permutation (Easy)
  - [ ] 169. Majority Element (Easy)
  - [ ] 318. Maximum Product of Word Lengths (Medium)
  - [ ] 477. Total Hamming Distance (Medium)

## References

- [Fundamental Data Structures](https://en.wikipedia.org/wiki/Book:Fundamental_Data_Structures)
- [Introduction to Algorithms by Thomas H. Cormen, Charles E. Leiserson, Ronald L. Rivest, and Clifford Stein](https://en.wikipedia.org/wiki/Introduction_to_Algorithms)
- [Algorithm Design by Jon Kleinberg and Éva Tardos](https://www.amazon.ca/Algorithm-Design-Jon-Kleinberg/dp/0321295358)
- [Algorithms by William Fiset](https://github.com/williamfiset/Algorithms)
- [Algorithms by Jeff Erickson](http://jeffe.cs.illinois.edu/teaching/algorithms/)
- [Stanford CS 166](https://web.stanford.edu/class/cs166/)
- [Harvard CS 224](https://www.youtube.com/playlist?list=PL2SOU6wwxB0uP4rJgf5ayhHWgw7akUWSf)

## License

This repository is released under the MIT license. In short, this means you are free to use this software in any personal, open-source or commercial projects
