# unit4_discussion
Python Binary Search Tree application for CMSC 315. Includes recursive BST insertion, search operations, in-order traversal, performance analysis, and examples demonstrating BST organization and efficiency.

For this assignment, I created a Binary Search Tree (BST) application that stores and organizes data in a hierarchical structure. My real-world example was organizing employee records by employee ID numbers. Each new employee ID is inserted into the tree according to BST rules, where smaller values are placed on the left and larger values are placed on the right. I implemented recursive insertion, recursive searching, and in-order traversal. The in-order traversal demonstrates how the BST automatically organizes data because it displays the values in sorted order.

One of the most important concepts I learned was how recursion is used to navigate through a tree structure. Before this assignment, I understood recursion conceptually, but implementing recursive insert and search functions helped me better understand how trees are traversed. I also learned how BSTs improve search efficiency compared to searching through a standard list because each comparison eliminates half of the remaining possibilities.

Trees improve performance because they provide faster searching, insertion, and retrieval operations. In a balanced BST, these operations can be performed in approximately O(log n) time, making them much more efficient than a linear search through an unsorted list. However, BSTs can become inefficient when data is inserted in sorted order. For example, if employee IDs are added as 1001, 1002, 1003, and 1004, the tree becomes unbalanced and resembles a linked list. In that case, search performance degrades to O(n), eliminating many of the advantages of using a BST.

Overall, this assignment helped me better understand how tree structures organize data efficiently and why maintaining a balanced tree is important for performance.
