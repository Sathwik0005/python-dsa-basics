# Python DSA Basics

This repository contains implementations of fundamental **Data Structures and Algorithms** in Python.  
Each concept is practiced and documented using Jupyter/Colab notebooks.

---

## ✅ Implemented So Far

### 1. Dynamic Array – `MyList`

File: `arrays/dynamic_array.ipynb`

A custom implementation of a **dynamic array** using `ctypes`, similar to how Python lists work internally.

**Supported operations:**

- `append(item)` – add element at the end
- `pop()` – remove and return the last element
- `clear()` – reset the list
- `find(item)` – return index of first occurrence
- `__len__()` – current number of elements
- `__str__()` – pretty-print the list
- `__getitem__(index)` – indexing (e.g. `arr[0]`)
- `__delitem__(index)` – delete by index
- `remove(item)` – delete by value
- `insert(pos, item)` – insert at a position
- `sort()` – simple in-place sort
- `min()` / `max()` – minimum and maximum values
- `sum()` – sum of all elements
- `extend(list)` – extend with a Python list
- `neg_index(pos)` – negative indexing (e.g. `-1` for last)
- `slice(start, stop, step)` – slicing similar to Python lists
- `merge(other)` – merge with another sequence

---

## 2. Singly Linked List – `MyLinkedList`

File: `linkedlist/linked_list.py`

This file contains a custom implementation of a **singly linked list** with node insertion, deletion, traversal, and indexing.

### Supported Operations

- `insert_head(value)` – Insert element at the head
- `append(value)` – Insert at the tail
- `insert_after(value, new_value)` – Insert after a given value
- `traverse()` – Print all elements
- `delete_head()` – Remove the first element
- `pop()` – Remove the last element
- `remove(value)` – Remove a specific value
- `search(value)` – Find index of a value
- `__getitem__(pos)` – Indexing support like a list
- `clear()` – Remove all elements
