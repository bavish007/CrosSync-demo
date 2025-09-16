# Beautiful Matrix (Codeforces 263-A)

**Platform:** Codeforces
**ID:** 263-A
**Solved at:** 2025-08-20T10:08:51.000Z
**Difficulty:** 800
**Tags:** implementation
**Source:** https://codeforces.com/problemset/problem/263/A

## Problem statement
A. Beautiful Matrixtime limit per test2 secondsmemory limit per test256 megabytesinputstdinoutputstdoutYou've got a 5 × 5 matrix, consisting of 24 zeroes and a single number one. Let's index the matrix rows by numbers from 1 to 5 from top to bottom, let's index the matrix columns by numbers from 1 to 5 from left to right. In one move, you are allowed to apply one of the two following transformations to the matrix:  Swap two neighboring matrix rows, that is, rows with indexes i and i + 1 for some integer i (1 ≤ i < 5).  Swap two neighboring matrix columns, that is, columns with indexes j and j + 1 for some integer j (1 ≤ j < 5). You think that a matrix looks beautiful, if the single number one of the matrix is located in its middle (in the cell that is on the intersection of the third row and the third column). Count the minimum number of moves needed to make the matrix beautiful.InputThe input consists of five lines, each line contains five integers: the j-th integer in the i-th line of the input represents the element of the matrix that is located on the intersection of the i-th row and the j-th column. It is guaranteed that the matrix consists of 24 zeroes and a single number one.OutputPrint a single integer — the minimum number of moves needed to make the matrix beautiful.ExamplesInputCopy0 0 0 0 00 0 0 0 10 0 0 0 00 0 0 0 00 0 0 0 0OutputCopy3InputCopy0 0 0 0 00 0 0 0 00 1 0 0 00 0 0 0 00 0 0 0 0OutputCopy1

## Sample Input
```
0 0 0 0 00 0 0 0 10 0 0 0 00 0 0 0 00 0 0 0 00 0 0 0 00 0 0 0 00 1 0 0 00 0 0 0 00 0 0 0 0
```

## Sample Output
```
31
```

## Solution code
```cpp
Solution code could not be scraped.
```