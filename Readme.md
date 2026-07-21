# The Ultimate High-ROI LeetCode Patterns Guide

*41 patterns, 20 problems each, all free — no Premium garbage. Sorted top to bottom by how often each pattern actually shows up in interviews. Hash Map and Sliding Window first because they're everywhere. Segment Tree and Fenwick Tree last because almost nobody asks them. Inside each pattern: Easy to Hard, so you're not getting wrecked by a Hard problem before you've even nailed the basic version of the trick.*

**How to actually use this:**

Don't grind all 820. That's a waste of your time and most of this list won't come up. Drill the first 10-15 patterns until you don't have to think — you see the problem, your hands already know the code. Everything below that is bonus coverage for if your interviewer likes to go off-script. Speed matters more than breadth here: 45 minutes isn't a lot of time, and if you're still figuring out syntax halfway through, you're not getting to the part where you actually look good.

**Hard truths about the process:**

Most loops are decided on the first problem.

Speed and clean code beat a late correct answer.

Follow-ups exist to catch memorized solutions.

You're graded against other candidates that week, not a fixed bar.

<a id="top"></a>
## Patterns

[1. Hash Map / Hash Set](#1-hash-map--hash-set)  
[2. Sliding Window](#2-sliding-window)  
[3. Two Pointers](#3-two-pointers)  
[4. Binary Search](#4-binary-search)  
[5. Prefix Sum](#5-prefix-sum)  
[6. String Manipulation / Parsing](#6-string-manipulation--parsing)  
[7. String Matching / Pattern Search](#7-string-matching--pattern-search)  
[8. Stack](#8-stack)  
[9. Monotonic Stack / Queue (Specific Variants)](#9-monotonic-stack--queue-specific-variants)  
[10. Queue / Deque](#10-queue--deque)  
[11. Tree DFS (Preorder / Inorder / Postorder)](#11-tree-dfs-preorder--inorder--postorder)  
[12. Tree BFS (Level Order)](#12-tree-bfs-level-order)  
[13. Dynamic Programming - 1D](#13-dynamic-programming---1d)  
[14. Recursion / Divide and Conquer](#14-recursion--divide-and-conquer)  
[15. Backtracking / Subsets / Combinations / Permutations](#15-backtracking--subsets--combinations--permutations)  
[16. Graph DFS](#16-graph-dfs)  
[17. Graph BFS](#17-graph-bfs)  
[18. Matrix / Grid Traversal](#18-matrix--grid-traversal)  
[19. Heap / Priority Queue](#19-heap--priority-queue)  
[20. Intervals (Merge / Insert / Overlap)](#20-intervals-merge--insert--overlap)  
[21. Greedy](#21-greedy)  
[22. Dynamic Programming - 2D / Grid](#22-dynamic-programming---2d--grid)  
[23. Sorting](#23-sorting)  
[24. Fast & Slow Pointers (Linked List)](#24-fast--slow-pointers-linked-list)  
[25. Linked List Reversal / Manipulation](#25-linked-list-reversal--manipulation)  
[26. Binary Search Tree (BST)](#26-binary-search-tree-bst)  
[27. Bit Manipulation](#27-bit-manipulation)  
[28. Dynamic Programming - Knapsack Style](#28-dynamic-programming---knapsack-style)  
[29. Design Problems](#29-design-problems)  
[30. Topological Sort](#30-topological-sort)  
[31. Union-Find (Disjoint Set)](#31-union-find-disjoint-set)  
[32. Trie (Prefix Tree)](#32-trie-prefix-tree)  
[33. Cyclic Sort](#33-cyclic-sort)  
[34. Math / Number Theory](#34-math--number-theory)  
[35. Sliding Window Maximum / Minimum (Specific Variants)](#35-sliding-window-maximum--minimum-specific-variants)  
[36. Simulation / Array Rearrangement](#36-simulation--array-rearrangement)  
[37. Two Heaps](#37-two-heaps)  
[38. K-way Merge](#38-k-way-merge)  
[39. Game Theory / Minimax](#39-game-theory--minimax)  
[40. Segment Tree](#40-segment-tree)  
[41. Binary Indexed Tree (Fenwick Tree)](#41-binary-indexed-tree-fenwick-tree)  

---

# Arrays & Hashing

- Two Sum: https://leetcode.com/problems/two-sum/
- Contains Duplicate: https://leetcode.com/problems/contains-duplicate/
- Valid Anagram: https://leetcode.com/problems/valid-anagram/
- Group Anagrams: https://leetcode.com/problems/group-anagrams/
- Top K Frequent Elements: https://leetcode.com/problems/top-k-frequent-elements/
- Encode and Decode Strings (Premium): https://leetcode.com/problems/encode-and-decode-strings/
- Product of Array Except Self: https://leetcode.com/problems/product-of-array-except-self/
- Longest Consecutive Sequence: https://leetcode.com/problems/longest-consecutive-sequence/

# Two Pointers

- Valid Palindrome: https://leetcode.com/problems/valid-palindrome/
- Two Sum II - Input Array Is Sorted: https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/
- 3Sum: https://leetcode.com/problems/3sum/
- Container With Most Water: https://leetcode.com/problems/container-with-most-water/
- Trapping Rain Water: https://leetcode.com/problems/trapping-rain-water/
- Sort Colors: https://leetcode.com/problems/sort-colors/
- Boats to Save People: https://leetcode.com/problems/boats-to-save-people/

# Sliding Window

- Best Time to Buy and Sell Stock: https://leetcode.com/problems/best-time-to-buy-and-sell-stock/
- Longest Substring Without Repeating Characters: https://leetcode.com/problems/longest-substring-without-repeating-characters/
- Longest Repeating Character Replacement: https://leetcode.com/problems/longest-repeating-character-replacement/
- Permutation in String: https://leetcode.com/problems/permutation-in-string/
- Minimum Window Substring: https://leetcode.com/problems/minimum-window-substring/
- Fruit Into Baskets: https://leetcode.com/problems/fruit-into-baskets/
- Subarray Product Less Than K: https://leetcode.com/problems/subarray-product-less-than-k/
- Subarrays with K Different Integers: https://leetcode.com/problems/subarrays-with-k-different-integers/
- Max Consecutive Ones III: https://leetcode.com/problems/max-consecutive-ones-iii/

# Stack

- Valid Parentheses: https://leetcode.com/problems/valid-parentheses/
- Min Stack: https://leetcode.com/problems/min-stack/
- Evaluate Reverse Polish Notation: https://leetcode.com/problems/evaluate-reverse-polish-notation/
- Generate Parentheses: https://leetcode.com/problems/generate-parentheses/
- Daily Temperatures: https://leetcode.com/problems/daily-temperatures/
- Decode String: https://leetcode.com/problems/decode-string/
- Asteroid Collision: https://leetcode.com/problems/asteroid-collision/
- Car Fleet: https://leetcode.com/problems/car-fleet/
- Largest Rectangle in Histogram: https://leetcode.com/problems/largest-rectangle-in-histogram/
- Sum of Subarray Minimums: https://leetcode.com/problems/sum-of-subarray-minimums/

# Binary Search

- Binary Search: https://leetcode.com/problems/binary-search/
- Search in Rotated Sorted Array: https://leetcode.com/problems/search-in-rotated-sorted-array/
- Find Minimum in Rotated Sorted Array: https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/
- Search a 2D Matrix: https://leetcode.com/problems/search-a-2d-matrix/
- Time Based Key-Value Store: https://leetcode.com/problems/time-based-key-value-store/
- Koko Eating Bananas: https://leetcode.com/problems/koko-eating-bananas/
- Capacity To Ship Packages Within D Days: https://leetcode.com/problems/capacity-to-ship-packages-within-d-days/
- Median of Two Sorted Arrays: https://leetcode.com/problems/median-of-two-sorted-arrays/

# Linked Lists

- Reverse Linked List: https://leetcode.com/problems/reverse-linked-list/
- Merge Two Sorted Lists: https://leetcode.com/problems/merge-two-sorted-lists/
- Linked List Cycle: https://leetcode.com/problems/linked-list-cycle/
- Reorder List: https://leetcode.com/problems/reorder-list/
- Remove Nth Node From End of List: https://leetcode.com/problems/remove-nth-node-from-end-of-list/
- Copy List with Random Pointer: https://leetcode.com/problems/copy-list-with-random-pointer/
- Add Two Numbers: https://leetcode.com/problems/add-two-numbers/
- Reverse Nodes in k-Group: https://leetcode.com/problems/reverse-nodes-in-k-group/
- Merge k Sorted Lists: https://leetcode.com/problems/merge-k-sorted-lists/
- LRU Cache: https://leetcode.com/problems/lru-cache/

# Trees

- Maximum Depth of Binary Tree: https://leetcode.com/problems/maximum-depth-of-binary-tree/
- Same Tree: https://leetcode.com/problems/same-tree/
- Invert Binary Tree: https://leetcode.com/problems/invert-binary-tree/
- Balanced Binary Tree: https://leetcode.com/problems/balanced-binary-tree/
- Diameter of Binary Tree: https://leetcode.com/problems/diameter-of-binary-tree/
- Binary Tree Level Order Traversal: https://leetcode.com/problems/binary-tree-level-order-traversal/
- Binary Tree Zigzag Level Order Traversal: https://leetcode.com/problems/binary-tree-zigzag-level-order-traversal/
- Binary Tree Right Side View: https://leetcode.com/problems/binary-tree-right-side-view/
- Count Good Nodes in Binary Tree: https://leetcode.com/problems/count-good-nodes-in-binary-tree/
- Path Sum II: https://leetcode.com/problems/path-sum-ii/
- Lowest Common Ancestor of a Binary Tree: https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree/
- Construct Binary Tree from Preorder and Inorder Traversal: https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/
- Flatten Binary Tree to Linked List: https://leetcode.com/problems/flatten-binary-tree-to-linked-list/
- Binary Tree Maximum Path Sum: https://leetcode.com/problems/binary-tree-maximum-path-sum/
- Serialize and Deserialize Binary Tree: https://leetcode.com/problems/serialize-and-deserialize-binary-tree/

# Binary Search Trees

- Validate Binary Search Tree: https://leetcode.com/problems/validate-binary-search-tree/
- Kth Smallest Element in a BST: https://leetcode.com/problems/kth-smallest-element-in-a-bst/
- Insert into a Binary Search Tree: https://leetcode.com/problems/insert-into-a-binary-search-tree/
- Delete Node in a BST: https://leetcode.com/problems/delete-node-in-a-bst/
- Lowest Common Ancestor of a Binary Search Tree: https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-search-tree/

# Graphs

- Number of Islands: https://leetcode.com/problems/number-of-islands/
- Clone Graph: https://leetcode.com/problems/clone-graph/
- Number of Provinces: https://leetcode.com/problems/number-of-provinces/
- Course Schedule: https://leetcode.com/problems/course-schedule/
- Course Schedule II: https://leetcode.com/problems/course-schedule-ii/
- Redundant Connection: https://leetcode.com/problems/redundant-connection/
- Pacific Atlantic Water Flow: https://leetcode.com/problems/pacific-atlantic-water-flow/
- Rotting Oranges: https://leetcode.com/problems/rotting-oranges/
- 01 Matrix: https://leetcode.com/problems/01-matrix/
- Word Ladder: https://leetcode.com/problems/word-ladder/
- Network Delay Time: https://leetcode.com/problems/network-delay-time/
- Min Cost to Connect All Points: https://leetcode.com/problems/min-cost-to-connect-all-points/
- Reconstruct Itinerary: https://leetcode.com/problems/reconstruct-itinerary/
- Accounts Merge: https://leetcode.com/problems/accounts-merge/
- Alien Dictionary (Premium): https://leetcode.com/problems/alien-dictionary/
