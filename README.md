# Data-Structures-and-Algorithms-in-Python

## Worked solutions to the textbook ["Data Structures and Algorithms in Python"](https://www.wiley.com/en-us/Data+Structures+and+Algorithms+in+Python-p-9781118290279)

### Chapter 1: Python Primer

1. Write a short Python function, is multiple(n, m), that takes two integer values and returns True if n is a multiple of m, that is, n = mi for some integer i, and False otherwise.
```python 
def is_multiple(n,m):
  i=2
  if m*i == n:
    return True
  else:
    return False
```
