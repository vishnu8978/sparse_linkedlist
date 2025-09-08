# sparse_linkedlist


Overview

This project demonstrates how to store and represent a Sparse Matrix using a Linked List in C++.
A sparse matrix is a matrix where most of the elements are zeros. Instead of storing all elements (including zeros), we only store the non-zero values with their positions (row, column). This saves memory and makes the structure more efficient.

Approach

Node Structure

Each non-zero element is stored as a node in a linked list.

Each node contains:

Row index

Column index

Value

Pointer to the next node.

Insertion

New nodes are inserted in sorted order (by row and column) so traversal is simple.




https://github.com/vishnu8978/sparse_linkedlist/blob/main/Sparse_Using_LinkedList


