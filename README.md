# 301dannon

An Epitech project made in collaboration with Quentin "Tapir" Deregnaucourt.

## Aim

This programm will benchmark different sorting algorithms by comparing their execution speed, or rather the number of elementary operations performed by the algorithm (in order to be independent of the machine and its power). This is known as the time complexity of an algorithm.

## Algorythms

There are numerous elementary operations that can be relevant: variable declaration, variable assignment, variable access, function call, calculation, comparison, test, etc. To keep it simple, this programm will only count the number of comparisons between the given elements.

The following algorythms have been implemented:

- Selection sort
- Insertion sort
- Bubble sort
- Quicksort
- Merge sort

## Details

- Whenever the program goes through the list of elements (whether it's looking for, selecting or inserting an
element), always go from left to right.
- For quicksort, the program always pick the first element as pivot, and keep the relative order of the elements in
both partitions.
- Those algorythms are not optimized.
