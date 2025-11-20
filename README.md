# 🌳 Binary Tree Graph (C++ Implementation)

This project contains a complete and well-structured implementation of a **Binary Tree (non-BST)** using C++ Templates.  
The class includes various operations commonly used in **LeetCode problems** as well as **real-world applications** involving hierarchical data processing.

---

## 📘 Overview

This BinaryTree class supports:

- Node insertion  
- Node & subtree deletion  
- Tree traversal  
- Height, balance, and node count  
- Searching  
- Printing ancestors & descendants  
- Mirroring (reverse)  
- Parent lookup  

---

## 🧱 Features / Functionalities

### ✔ Tree Creation
- `setroot(val)` – Creates root node  
- `setleft(parent, value)` – Inserts left child under a parent  
- `setright(parent, value)` – Inserts right child under a parent  

---

## 🔎 Searching
- `search(r, val)` – Binary-search style recursive search  
- `FindNode(r, val)` – Full general search (checks entire tree)

---

## 🌳 Tree Traversals
- **Preorder** → `preorder(root)`  
  - Root → Left → Right  

- **Inorder** → `inorder(root)`  
  - Left → Root → Right  

- **Postorder** → `postorder(root)`  
  - Left → Right → Root  

- **Level Order** → `levelorder()`  
  - Breadth-first traversal using queue  

---

## 🗑 Node / Subtree Deletion

### `remove_specific(parent, child)`
Deletes a specific child from a parent and reconnects remaining subtree properly.

### `remove_all_nodes(parent, child)`
Deletes the entire subtree rooted at the child.

### `deleteSubtree(node)`
Internal recursive helper that deletes a complete subtree.

---

## 🔄 Tree Utilities

### `reverse(root)`
Mirrors (inverts) the entire tree by swapping left/right recursively.

### `height(root)`
Returns the height of the tree.

### `countnodes(root)`
Counts all nodes in the tree.

### `isBalanced(root)`
Checks whether the tree is height-balanced  
(left and right subtree height difference ≤ 1).

---

## 🧭 Node Type Check

### `InternalNode(value, root)`
Returns **true** if the node has at least one child.

### `ExternalNode(value, root)`
Returns **true** if the node has no children (leaf node).

---

## 👨‍👩‍👦 Parent & Descendant / Ancestor Operations

### `parentnode2(root, child)`
Returns the **value of the parent** of a node.

### `print(root, val)`
Prints **all descendants** of a given node.

### `printAnces(root)`
Prints ancestors of all nodes during traversal.

### `printAnces1(root, val)`
Prints ancestors of a specific node.

---

## 📂 Summary

This Binary Tree class is designed for:

- Learning tree fundamentals  
- Practicing common LeetCode-style problems  
- Using tree operations in educational or real-world projects  

It includes both **basic** and **advanced** tree functionalities, all implemented cleanly using C++ templates.

---

If you want, I can also write:

✅ A professional project description  
✅ UML / architecture diagram  
✅ Sample output section  
✅ Code snippets section  
Just tell me!
