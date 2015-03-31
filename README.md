# iterextensions
Collection of itertool helpers

The python documentation highlights a few recipes that can be implemented using itertools.
(https://docs.python.org/2.7/library/itertools.html)

This repo contains these recipies as well as some others.

Python2/3 compatible 

### Example
    >>> import iterextensions
    >>> iterextensions.take(2, [1,2,3,4])
    [1, 2]
    >>> list(iterextensions.chunk([1,2,3,4], 2))
    [(1, 2), (3, 4)]
    >>> list(iterextensions.flatten([[1,2,3,4,5], [6,7,8,9,0]]))
    [1, 2, 3, 4, 5, 6, 7, 8, 9, 0]
