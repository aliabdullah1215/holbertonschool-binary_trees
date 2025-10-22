# 🧱 C - Binary Trees

> A collaborative project at **Holberton School** focused on mastering binary tree data structures in C.

---

## 📚 Table of Contents
- [Overview](#overview)
- [Learning Objectives](#learning-objectives)
- [Data Structures](#data-structures)
- [Requirements](#requirements)
- [Compilation](#compilation)
- [File Descriptions](#file-descriptions)
- [Authors](#authors)

---

## 🧠 Overview
In this project, we implemented a variety of functions to create and manipulate **binary trees** using the C programming language.  
A binary tree is a hierarchical data structure in which each node has at most two children — referred to as the **left** and **right** child.  

This project lays the foundation for advanced data structures like **Binary Search Trees (BST)**, **AVL Trees**, and **Heaps**.

---

## 🎯 Learning Objectives
At the end of this project, you should be able to explain:

- What is a **binary tree**
- The difference between a **binary tree** and a **Binary Search Tree**
- The advantages of trees compared to linked lists (in terms of time complexity)
- Concepts such as **depth**, **height**, and **size** of a binary tree
- Different traversal methods: **preorder**, **inorder**, **postorder**
- The meaning of **complete**, **full**, **perfect**, and **balanced** binary trees

---

## 🧩 Data Structures

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
typedef struct binary_tree_s bst_t;
typedef struct binary_tree_s avl_t;
typedef struct binary_tree_s heap_t;
