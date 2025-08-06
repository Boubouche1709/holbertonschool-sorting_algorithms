<p align="center">
  <img src="https://github.com/user-attachments/assets/7d564981-cb81-43e7-819a-25ffcfc5bd72" width="40%" height="40%" alt="Binary Tree Illustration"/>
</p>

# 🌲 C - Binary Trees & Sorting Algorithms

## 🧠 Project Overview

This project explores two fundamental pillars of computer science: **binary trees** and **sorting algorithms**, implemented in the C programming language. It aims to strengthen your understanding of non-linear data structures and algorithmic efficiency.

You will build and manipulate binary trees, explore their various forms, and implement multiple sorting algorithms while analyzing their time complexity using Big O notation.

---

## 🎯 Learning Objectives

### Binary Trees
- Define what a **binary tree** is and distinguish it from a **Binary Search Tree (BST)**
- Understand and implement traversal methods: **pre-order**, **in-order**, **post-order**, **level-order**
- Explain the concepts of **depth**, **height**, and **size** of a tree
- Identify and differentiate between **full**, **complete**, **perfect**, and **balanced** binary trees
- Compare the time complexity of tree operations vs. linked lists

### Sorting Algorithms
- Implement at least **four different sorting algorithms**
- Evaluate efficiency using **Big O notation**
- Choose the most appropriate sorting algorithm for a given dataset
- Understand what makes a sorting algorithm **stable**

---

## 🛠 Technical Requirements

- Allowed editors: `vi`, `vim`, `emacs`
- OS: Ubuntu 20.04 LTS
- Compiler: `gcc` with flags `-Wall -Werror -Wextra -pedantic -std=gnu89`
- Coding style: **Betty style** (`betty-style.pl`, `betty-doc.pl`)
- No global variables
- Maximum of 5 functions per file
- All files must end with a newline
- A `README.md` file is mandatory
- Header files must be protected with include guards

---

## 🌳 Data Structure: Binary Tree

```c
/**
 * struct binary_tree_s - Binary tree node
 *
 * @n: Integer stored in the node
 * @parent: Pointer to the parent node
 * @left: Pointer to the left child node
 * @right: Pointer to the right child node
 */
struct binary_tree_s
{
    int n;
    struct binary_tree_s *parent;
    struct binary_tree_s *left;
    struct binary_tree_s *right;
};

typedef struct binary_tree_s binary_tree_t;
typedef struct binary_tree_s bst_t;   /* Binary Search Tree */
typedef struct binary_tree_s avl_t;   /* AVL Tree */
typedef struct binary_tree_s heap_t;  /* Max Binary Heap */
```

 ## 👥 Authors
- [Boubouche1709](https://github.com/Boubouche1709)
