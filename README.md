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

2. Write a short Python function, is even(k), that takes an integer value and returns True if k is even, and False otherwise. However, your function cannot use the multiplication, modulo, or division operators.
```python 
def is_multiple(n,m):
  i=2
  if m*i == n:
    return True
  else:
    return False
```

3. Write a short Python function, minmax(data), that takes a sequence of one or more numbers, and returns the smallest and largest numbers, in the form of a tuple of length two. Do not use the built-in functions min or max in implementing your solution.
4.  Write a short Python function, minmax(data), that takes a sequence of one or more numbers, and returns the smallest and largest numbers, in the form of a tuple of length two. Do not use the built-in functions min or max in implementing your solution.
5.  Give a single command that computes the sum from Exercise R-1.4, rely- ing on Python’s comprehension syntax and the built-in sum function.
6.  Write a short Python function that takes a positive integer n and returns the sum of the squares of all the odd positive integers smaller than n.
7.  Give a single command that computes the sum from Exercise R-1.6, rely- ing on Python’s comprehension syntax and the built-in sum function.
8.  Python allows negative integers to be used as indices into a sequence, such as a string. If string s has length n, and expression s[k] is used for in- dex −n ≤ k < 0, what is the equivalent index j ≥ 0 such that s[j] references the same element?
9.  What parameters should be sent to the range constructor, to produce a range with values 50, 60, 70, 80?
10.  What parameters should be sent to the range constructor, to produce a range with values 8, 6, 4, 2, 0, −2, −4, −6, −8?
11.  Demonstrate how to use Python’s list comprehension syntax to produce the list [1, 2, 4, 8, 16, 32, 64, 128, 256].
12.  Python’s random module includes a function choice(data) that returns a random element from a non-empty sequence. The random module in- cludes a more basic function randrange, with parameterization similar to the built-in range function, that return a random choice from the given range. Using only the randrange function, implement your own version of the choice function.
13.  Write a pseudo-code description of a function that reverses a list of n integers, so that the numbers are listed in the opposite order than they were before, and compare this method to an equivalent Python function for doing the same thing.
14.  Write a short Python function that takes a sequence of integer values and determines if there is a distinct pair of numbers in the sequence whose product is odd.
15.  Write a Python function that takes a sequence of numbers and determines if all the numbers are different from each other (that is, they are distinct).
16.  In our implementation of thescalefunction(page25),thebodyoftheloop executes the command data[j]   = factor. We have discussed that numeric types are immutable, and that use of the   = operator in this context causes the creation of a new instance (not the mutation of an existing instance). How is it still possible, then, that our implementation of scale changes the actual parameter sent by the caller?
17.  Had we implemented the scale function (page 25) as follows, does it work properly?<p>
      def scale(data, factor): <p>
      for val in data:<p>
           val   = factor<p>
     Explain why or why not.
19.  Demonstrate how to use Python’s list comprehension syntax to produce the list [0, 2, 6, 12, 20, 30, 42, 56, 72, 90].
20.  Demonstrate how to use Python’s list comprehension syntax to produce thelist[ a , b , c ,..., z ],butwithouthavingtotypeall26such characters literally.
21.  Python’s random module includes a function shuffle(data) that accepts a list of elements and randomly reorders the elements so that each possi- ble order occurs with equal probability. The random module includes a more basic function randint(a, b) that returns a uniformly random integer from a to b (including both endpoints). Using only the randint function, implement your own version of the shuffle function.
22.  Write a Python program that repeatedly reads lines from standard input until an EOFError is raised, and then outputs those lines in reverse order (a user can indicate end of input by typing ctrl-D).
