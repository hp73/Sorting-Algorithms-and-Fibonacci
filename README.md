Project 2 - Sorting Algorithms and Fibonacci
CSCI 102 Winter 2019
By Harry Pinkerton, Laurie Jones, and James Lawson
Required to run: python 3.7


=======================
counter.py
=======================
Counter class that when run tests all of the methods within the class. When run, it tests all of the methods within the class.

=======================
fibs.py
=======================
Two versions of the function to compute the nth Fibonacci number. The first function is the standard recursive version, 
and the second is the memoizing cache version. When run, it tests both of the fibonacci functions as well as their respective counter versions.

=======================
profile.py
=======================
profileSort displays counts of comparisons and swaps and running times for the given sort algorithm on several data sizes. The data size starts at 1
and doubles on each iteration.  An initial run shows results for a sorted list of 256 numbers.
Arguments: the sort function and the number of data sets

profileFib displays counts of calls and running times of the given fib function on several values of n.
Arguments: the fib function and the upper bound on n. n increases by 1 on each iteration.

When run, profileSort displays the selectionSort algorithm and the quickSort algorithm, and profileFib runs fib1 and fib2.
=======================
sorts.py
=======================
Defines selection sort, quick sort, insertion sort, all of which iterate through
a list and organize a list. Descriptions of each kind of sort are available in the analysis.txt file.


=======================
tools.py
=======================
A Counter object allows the programmer to create, increment (by 1),
and reset (to 0) a counter.  When a Counter object is printed, its
current value (an integer) is displayed.

The getRandomList function returns a list of random numbers
between 1 and n.
