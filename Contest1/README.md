## About
* Contest was held in 2018/8/2
* Was about *ad-hoc* and *data structures*
* Contest's length was 2.5 hour

## Questions
1. [Tanya and Stairways](http://codeforces.com/problemset/problem/1005/A)
2. [Cards with Numbers](http://codeforces.com/problemset/problem/254/A)
3. [Do Your Own Homework](https://uva.onlinejudge.org/index.php?option=com_onlinejudge&Itemid=8&page=show_problem&problem=3068)
4. [Heap Operations](http://codeforces.com/problemset/problem/681/C)
5. [Potentiometers](https://uva.onlinejudge.org/index.php?option=com_onlinejudge&Itemid=8&page=show_problem&problem=3238)
6. [Splitting the Uniqueness](http://codeforces.com/problemset/problem/297/C)

## Editorial
1. see part *1005A - Tanya and Stairways* [in this editorial](http://codeforces.com/blog/entry/60511).
2. see part *254A - Cards with Numbers* [in this editorial](http://codeforces.com/blog/entry/6085).
3. see part *Do Your Own Homework* [here](#do-your-own-homework-editorial), also see [code](https://github.com/maryam97/ACM/blob/master/UVa%20problems/11917%20.cpp).
4. see part *681C - Heap Operations* [in this editorial](http://codeforces.com/blog/entry/45425).
5. see part *Potentiometers* [here](#potentiometers-editorial), also see code with [Segment Tree](https://github.com/morris821028/UVa/blob/master/volume120/12086%20-%20Potentiometers.cpp) or [Fenwick Tree](https://github.com/ackoroa/UVa-Solutions/blob/master/UVa%2012086%20-%20Potentiometers/src/UVa%2012086%20-%20Potentiometers.cpp).
1. see part *297C - Splitting the Uniqueness* [in this editorial](http://codeforces.com/blog/entry/7437).

#### Do Your Own Homework Editorial
> For each test case map each subject string to the following integer (number of days), then check the map of the query string with D,
If it was smaller than or equal to D and not equal to zero (string exists in the map), output "Yesss" else if it was between D and smaller than or equal to D + 5, output "Late". Otherwise output " Do your own homework!".

#### Potentiometers Editorial
> The only important thing to note in this problem is that since *N* can be as large as 200000, then n ^ 2 solutions will not pass the time limit. (10 ^ 8 operations take about 1 seconds to finish).
so we need an appropriate data structure which supports *update and get* queries efficiently. both *Segment tree* and *Fenwick tree* can be used to solve this problem since both support *update and get* queries in O(log(n)).
