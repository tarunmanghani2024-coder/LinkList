# Singly Linked List - Twitter Tweet Manager

## Project Overview

This is a BCA data structures project implementing a **Singly Linked List** to manage Twitter tweets. It demonstrates core C++ programming with classes, pointers, and dynamic memory allocation.

***

## What It Does

- **Add tweets** at beginning, end, or specific position
- **Delete tweets** from any position
- **Search tweets** by username
- **Display all tweets** in the list
- **Count total tweets**

***

## Class Structure

```
NODE Class:
  - ID (string)       → Tweet ID
  - UNAME (string)    → Username  
  - TWEET (string)    → Tweet content
  - NEXT (NODE*)      → Pointer to next node

LinkList Class:
  - START (NODE*)     → Head pointer
  - END (NODE*)       → Tail pointer
  - countNode (int)   → Total nodes
```

***

## Key Operations

| Operation | Complexity |
|-----------|------------|
| Insert at Beginning | O(1) |
| Insert at End | O(1) |
| Insert at Position | O(n) |
| Delete from Beginning | O(1) |
| Delete from End | O(n) |
| Search by Username | O(n) |

***

## How to Run

```bash
g++ LinkList_Complete.cpp -o linklist
./linklist
```

***

## What I Learned

- Linked list implementation with pointers
- Dynamic memory allocation (`new`/`delete`)
- OOP concepts (classes, objects, encapsulation)
- Memory management (no memory leaks)
- Traversal and manipulation of linked data

***

## Limitations

- Windows-only (`conio.h`)
- No file persistence
- No update function
