# Short Sort (Codeforces 1873-A)

**Platform:** Codeforces
**ID:** 1873-A
**Solved at:** 2025-08-20T10:35:31.000Z
**Difficulty:** 800
**Tags:** brute force, implementation
**Source:** https://codeforces.com/problemset/problem/1873/A

## Problem statement
A. Short Sorttime limit per test1 secondmemory limit per test256 megabytesinputstandard inputoutputstandard outputThere are three cards with letters aa\texttt{a}, bb\texttt{b}, cc\texttt{c} placed in a row in some order. You can do the following operation at most once:   Pick two cards, and swap them.  Is it possible that the row becomes abcabc\texttt{abc} after the operation? Output "YES" if it is possible, and "NO" otherwise.InputThe first line contains a single integer ttt (1≤t≤61≤t≤61 \leq t \leq 6) — the number of test cases.The only line of each test case contains a single string consisting of each of the three characters aa\texttt{a}, bb\texttt{b}, and cc\texttt{c} exactly once, representing the cards.OutputFor each test case, output "YES" if you can make the row abcabc\texttt{abc} with at most one operation, or "NO" otherwise.You can output the answer in any case (for example, the strings "yEs", "yes", "Yes" and "YES" will be recognized as a positive answer).ExampleInputCopy6abcacbbacbcacabcbaOutputCopyYES
YES
YES
NO
NO
YES
NoteIn the first test case, we don't need to do any operations, since the row is already abcabc\texttt{abc}.In the second test case, we can swap cc\texttt{c} and bb\texttt{b}: acb→abcacb→abc\texttt{acb} \to \texttt{abc}.In the third test case, we can swap bb\texttt{b} and aa\texttt{a}: bac→abcbac→abc\texttt{bac} \to \texttt{abc}.In the fourth test case, it is impossible to make abcabc\texttt{abc} using at most one operation.

## Sample Input
```
6abcacbbacbcacabcba
```

## Sample Output
```
YES
YES
YES
NO
NO
YES
```

## Solution code
```cpp
Solution code could not be scraped.
```