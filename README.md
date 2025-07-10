# AVL-MAP
AVL-MAP in C++
This project implements a custom map-like data structure using a self-balancing AVL Tree in C++. It supports efficient insertion, update, and search operations with a time complexity of O(log n). The implementation includes manual memory management and overloads the [] operator for intuitive key-value access.

# Features:
- AVL Tree-based balanced binary search map
- Supports map[key] = value and value = map[key] syntax via operator overloading
- Automatically balances after every insertion
- Memory-efficient with a shared static root node
- Demonstrates fundamental concepts of tree rotations and balancing

# Technologies & Concepts Used
- C++ (Manual Memory Management with malloc/free)
- AVL Tree (Self-balancing BST)
- Operator Overloading
- Tree Rotations (Left and Right)
