# Data-Structures-and-Algorithms-in-Python-by-Goodrich

Worked solutions to the textbook "Data Structures and Algorithms in Python" by Michael T. Goodrich

Chapter 1: Python Primer
```python 
# R-1.1 Write a short Python function, is multiple(n, m), that takes two integer values and returns True if n is a multiple of m, that is, n = mi for some integer i, and False otherwise.

def is_multiple(n,m):
  i=2
  if m*i == n:
    return True
  else:
    return False
```
