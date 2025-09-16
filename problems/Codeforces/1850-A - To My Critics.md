# To My Critics (Codeforces 1850-A)

**Platform:** Codeforces
**ID:** 1850-A
**Solved at:** 2025-08-20T10:38:59.000Z
**Difficulty:** 800
**Tags:** implementation, sortings
**Source:** https://codeforces.com/problemset/problem/1850/A

## Problem statement
A. To My Criticstime limit per test1 secondmemory limit per test256 megabytesinputstandard inputoutputstandard outputSuneet has three digits aaa, bbb, and ccc. Since math isn't his strongest point, he asks you to determine if you can choose any two digits to make a sum greater or equal to 101010.Output "YES" if there is such a pair, and "NO" otherwise.InputThe first line contains a single integer ttt (1≤t≤10001≤t≤10001 \leq t \leq 1000) — the number of test cases.The only line of each test case contains three digits aaa, bbb, ccc (0≤a,b,c≤90≤a,b,c≤90 \leq a, b, c \leq 9).OutputFor each test case, output "YES" if such a pair exists, and "NO" otherwise.You can output the answer in any case (for example, the strings "yEs", "yes", "Yes" and "YES" will be recognized as a positive answer).ExampleInputCopy58 1 24 4 59 9 90 0 08 5 3OutputCopyYES
NO
YES
NO
YES
NoteFor the first test case, by choosing the digits 888 and 222 we can obtain a sum of 8+2=108+2=108 + 2 = 10 which satisfies the condition, thus the output should be "YES".For the second test case, any combination of chosen digits won't be at least 101010, thus the output should be "NO" (note that we can not choose the digit on the same position twice).For the third test case, any combination of chosen digits will have a sum equal to 181818, thus the output should be "YES".

## Sample Input
```
58 1 24 4 59 9 90 0 08 5 3
```

## Sample Output
```
YES
NO
YES
NO
YES
```

## Solution code
```cpp
Solution code could not be scraped.
```