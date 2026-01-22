# Advanced Data Structures & Algorithms in Python

This repository contains implementations of advanced **sorting algorithms** and **tree-based data structures** using **Python**.  
These programs are designed for **DSA learning, exams, and practical understanding**.

---

## 📌 Contents

1. Optimized Quick Sort Algorithm  
2. Binary Search Tree (BST)  
3. AVL Tree (Self-Balancing Binary Search Tree)  

---

## 1️⃣ Optimized Quick Sort Algorithm

### Description
Optimized Quick Sort improves performance by using **in-place partitioning**, reducing extra memory usage.  
It selects a pivot element and rearranges the array so that elements smaller than the pivot come before it, and larger elements come after.

### Time Complexity
- Best Case: **O(n log n)**
- Average Case: **O(n log n)**
- Worst Case: **O(n²)**

### Space Complexity
- **O(log n)** (Recursive stack)

---

## 2️⃣ Binary Search Tree (BST)

### Description
A Binary Search Tree is a hierarchical data structure where:
- Left subtree contains values smaller than the root
- Right subtree contains values greater than the root

BST allows fast searching, insertion, and traversal.

### Operations Implemented
- Insertion  
- Search  
- Inorder Traversal  

### Time Complexity
- Average Case: **O(log n)**
- Worst Case: **O(n)**

### Space Complexity
- **O(n)**

---

## 3️⃣ AVL Tree

### Description
AVL Tree is a **self-balancing Binary Search Tree**.  
After each insertion, it checks the **balance factor** and performs rotations to maintain balance.

### Rotations Used
- Left Rotation  
- Right Rotation  
- Left-Right Rotation  
- Right-Left Rotation  

### Time Complexity
- Insert: **O(log n)**
- Search: **O(log n)**
- Delete: **O(log n)**

### Space Complexity
- **O(n)**

---


