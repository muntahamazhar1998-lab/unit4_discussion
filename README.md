## Unit 4 Discussion: Binary Search Trees
## Overview

This assignment introduced Binary Search Trees (BSTs) and recursive tree operations. A BST application was implemented in Python to demonstrate insertion, searching, and in-order traversal.

## Learning Objectives
Built a BST.
Inserted values recursively.
Searched recursively.
Performed in-order traversal.
Demonstrated BST organization and efficiency.
Requirements
## 1. Build a BST

An empty Binary Search Tree was created using a root node reference. Values were inserted according to BST rules, with smaller values placed in the left subtree and larger values placed in the right subtree.

## 2. Insert Multiple Values

Seven values were inserted into the BST: 50, 25, 75, 15, 35, 60, and 90. These values created both left and right subtrees.

## 3. Demonstrate In-Order Traversal

An in-order traversal was implemented and tested. The traversal returned values in sorted order because the algorithm visited the left subtree, current node, and right subtree.

## 4. Test Searching

Search operations were tested with values that existed in the tree and values that did not exist. The program correctly returned True when values were found and False when values were not found.

## 5. Demonstrate Edge Cases

Several edge cases were tested, including searching an empty tree, traversing an empty tree, and attempting to insert duplicate values.

## 6. Create a Real-World BST Example

Employee ID numbers were used as a real-world example to demonstrate how BSTs can organize records and improve search performance.

Discussion Board Reflection
## What concepts or skills did you learn while completing this assignment?

I learned how Binary Search Trees organize data using parent and child nodes. I also learned how recursion is used to perform insertion, searching, and traversal operations efficiently. The assignment improved my understanding of how hierarchical data structures differ from linear structures such as arrays and linked lists.

## What challenges did you encounter, and how did you overcome them?

The most challenging part was understanding the recursive insertion process and how nodes are linked together within the tree. I overcame this challenge by tracing the program step by step and drawing a tree diagram to visualize how values moved left or right during insertion.

## Explain BST behavior and compare how ordering works to create efficiency as compared to other data structures.

BSTs improve efficiency because each comparison eliminates part of the remaining search space. In a balanced BST, searching, insertion, and retrieval operations are much faster than a linear search through a list. However, BSTs can become inefficient when values are inserted in sorted order because the tree becomes unbalanced and resembles a linked list. When this occurs, search performance decreases significantly because more nodes must be visited
