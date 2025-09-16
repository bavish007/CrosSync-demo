# The Secret Number (Codeforces 2132-B)

**Platform:** Codeforces
**ID:** 2132-B
**Solved at:** 2025-08-21T15:00:32.000Z
**Difficulty:** 900
**Tags:** math
**Source:** https://codeforces.com/problemset/problem/2132/B

## Problem statement
B. The Secret Numbertime limit per test2 secondsmemory limit per test256 megabytesinputstandard inputoutputstandard outputVadim has thought of a number xxx. To ensure that no one can guess it, he appended a positive number of zeros to the right of it, thus obtaining a new number yyy. However, as a precaution, Vadim decided to spread the number n=x+yn=x+yn = x + y. Find all suitable xxx that Vadim could have thought of for the given nnn.InputEach test consists of several test cases. The first line contains a single integer ttt (1≤t≤104)(1≤t≤104)(1 \le t \le 10^4) — the number of test cases. The following lines describe the test cases.In a single line of each test case, there is an integer nnn — the number spread by Vadim (11≤n≤1018)(11≤n≤1018)(11 \le n \le 10^{18}).OutputFor each number nnn, output 000 if there are no suitable xxx. Otherwise, output the number of suitable xxx, followed by all suitable xxx in ascending order.ExampleInputCopy5111112559999999999999999991000000000000000000OutputCopy2
11 101
0
1
5
3
999999999 999000999000999 90909090909090909
0
NoteIn the first sample, to 111111 one can append two zeros to the right, then 11+1100=111111+1100=111111 + 1100 = 1111, and to 101101101 one can append one zero to the right, then 101+1010=1111101+1010=1111101 + 1010 = 1111.In the second sample, it is impossible to obtain 121212 through the described actions.

## Sample Input
```
5111112559999999999999999991000000000000000000
```

## Sample Output
```
2
11 101
0
1
5
3
999999999 999000999000999 90909090909090909
0
```

## Solution code
```cpp
Solution code could not be scraped.
```