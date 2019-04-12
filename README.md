# 60_wrapBinarySearch

0: y=log2x represents a function in which x=2^y. This is the same as saying that the power to which
2 must be raised to return x is y.

1: The graph of y=log2x is a curve with a domain of (0, infinity), and a range of (-infinity, infinity). Its rate of change decreases as x increases.


RECURSIVE SOLUTION:
Problem: The recursive solution must return the index at which a specific element lies in an ordered list.

Recursive Abstraction: When I am asked to find an element in an orderedList with upper bound hi and lower bound lo starting at the element findMe, the recursive abstraction can find an element in an orderedList with either upper bound hi and lower bound findMe or with upper bound findMe and lower bound lo, starting at the element directly between the two bounds.
