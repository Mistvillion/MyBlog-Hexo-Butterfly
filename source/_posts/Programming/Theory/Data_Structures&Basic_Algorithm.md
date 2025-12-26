---
title: 数据结构与基础算法
categories:
  - Programming
  - Theory
comments: true
description: 常用数据结构与排序查找算法
series: 数据结构与基础算法
highlight_shrink: true
cover: /img/posts/DataStructures_and_Algorithm.jpg
abbrlink: f0be246
date: 2025-12-08 00:00:00
updated: 2025-12-08 00:00:00
toc:
  enable: true
  list_number: true
---

（尚未完工，持续更新中...）
本文囊括了一些最基础的数据结构与算法，此页为目录，详细介绍请看右侧边栏。
如果你有更好的想法或者我没有收录进来的数据结构或算法，请在评论区留言，方便我做出修改，谢谢！

---

## 1. 绪论（Introduction）

* **算法复杂度分析 (Complexity Analysis)**
* 时间复杂度 (Time Complexity) —— , , 
* 空间复杂度 (Space Complexity)

---

## 2. 线性结构（Linear Structures）

### 2.1 线性表 (Linear Lists)

* **顺序表 (Sequential List)**
* **单链表 (Singly Linked List)**
* **双向链表 (Doubly Linked List)**
* **循环链表 (Circular Linked List)**
* **静态链表 (Static Linked List)** 

### 2.2 栈、队列、数组 (Stacks, Queues and Arrays)

* **栈 (Stack)**：顺序栈、链栈、共享栈
* **队列 (Queue)**：循环队列 (Circular Queue)、链式队列
* **双端队列 (Deque)**：输入/输出受限的双端队列
* **数组与特殊矩阵 (Arrays and Special Matrices)**
* 数组的存储 (Row/Column Major Order)
* 对称矩阵的压缩存储 (Symmetric Matrix Compression)
* 三角矩阵/对角矩阵 (Triangular/Diagonal Matrix)
* 稀疏矩阵 (Sparse Matrix)：三元组、十字链表

### 2.3 串 (Strings)

* **字符串基本操作 (Basic String Operations)**
* **模式匹配 (Pattern Matching)**
* 朴素模式匹配算法 (Brute-Force)
* **KMP算法 (Knuth-Morris-Pratt)**
* KMP算法优化 (Modified KMP / nextval)

---

## 3. 树结构（Trees）

### 3.1 树与二叉树 (Trees and Binary Trees)

* **二叉树 (Binary Tree)**：完全二叉树 (Complete BT)、满二叉树 (Full BT)
* **遍历 (Traversal)**：先序、中序、后序、层序 (Level Order)
* **线索二叉树 (Threaded Binary Tree)**
* **树、森林与二叉树的转换 (Conversion between Trees, Forests and Binary Trees)**
* **哈夫曼树 (Huffman Tree)** 与哈夫曼编码 (Huffman Coding)
* **并查集 (Disjoint Set Union - DSU)**：合并与路径压缩 (Path Compression)

### 3.2 图 (Graphs)

* **图的存储 (Graph Storage)**
* **图的遍历 (Graph Traversal)**：DFS (Depth First Search) 与 BFS (Breadth First Search)
* **最小生成树 (Minimum Spanning Tree - MST)**
* **最短路径 (Shortest Path)**
* **拓扑排序 (Topological Sort)** —— AOV网
* **关键路径 (Critical Path Method - CPM)** —— AOE网

---

## 4. 查找与排序（Searching & Sorting）

### 4.1 查找 (Searching)

* **线性查找 (Linear Search) 与 折半查找 (Binary Search)**
* **树形查找 (Tree-based Search)**
* **B树与B+树 (B-Tree and B+ Tree)** 
* **散列表 (Hash Table)**：散列函数、处理冲突的方法

### 4.2 排序 (Sorting)

* **插入排序 (Insertion Sort)**：直接插入、折半插入、希尔排序 (Shell Sort)
* **交换排序 (Swap Sort)**：冒泡排序 (Bubble Sort)、**快速排序 (Quick Sort)**
* **选择排序 (Selection Sort)**：简单选择排序、**堆排序 (Heap Sort)**
* **归并排序 (Merge Sort)**
* **分配类排序**：基数排序 (Radix Sort)、计数排序 (Counting Sort)
* **外部排序 (External Sorting)**：多路平衡归并、置换-选择排序、最佳归并树

---

## 5. C++ STL 标准模板库

### 5.1 迭代器 (Iterator)

### 5.2 序列式容器 (Sequence Containers)

* `vector` (Dynamic Array)
* `list` (Doubly Linked List)
* `deque` (Double-ended Queue)
* `array` (Fixed-size Array)
* `string` (String Class)

### 5.3 容器适配器 (Container Adapters)

* `stack` (Stack)
* `queue` (Queue)
* `priority_queue` (Priority Queue / Max Heap)

### 5.4 关联式/无序容器 (Associative & Unordered Containers)

* `set` / `multiset` (Red-Black Tree based)
* `map` / `multimap` (Key-Value pairs)
* `unordered_set` / `unordered_map` (Hash Table based)

---

## 6. 算法进阶与技巧（Advanced Techniques）

* **双指针 (Two Pointers)**
* **滑动窗口 (Sliding Window)**
* **区间合并 (Interval Merging)**
* **分治 (Divide & Conquer)**
* **贪心 (Greedy Algorithm)**
* **动态规划 (Dynamic Programming)** 
* **单调栈 / 单调队列 (Monotonic Stack / Queue)**
* **位运算 (Bit Manipulation)**

<!-- 自定义 CSS：只在当前文章生效 -->
<style>
  /* Butterfly 主题 TOC 类名为 .toc-content */
  /* 隐藏 3级 (H3) 及更深层级的所有目录项 */
  .toc-content .toc-level-3,
  .toc-content .toc-level-4,
  .toc-content .toc-level-5,
  .toc-content .toc-level-6 {
      display: none !important;
  }
</style>