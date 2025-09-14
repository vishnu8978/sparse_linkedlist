# sparse_linkedlist


Overview

The main goal of this project involves creating an efficient sparse matrix representation system for C++ linked lists which handles matrices containing many zero elements. The storage of sparse matrices through 2D arrays proves inefficient because these methods allocate excessive memory space to store unneeded zero values. My solution implements linked lists to store non-zero matrix elements together with their row and column positions which reduces memory usage.Each non-zero matrix element in a singly linked list  contains four essential parts: row index ,column index,non-zero value and a pointer to next node. 

Features

Here singly linkedlist is used, where it store only non-zero values of a matrix

Another interesting thing is, here elements are inserted dynamically while it keeps sorted by row and column.

It displays both the matrix one is original other is sparse matrix.

Another advancement is a destructor is created where it works as a automatic memory cleaner.




https://github.com/vishnu8978/sparse_linkedlist/blob/main/Sparse_Using_LinkedList


