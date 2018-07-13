## Resources
* Competitive Programming Chapter 1
* Competitive Programmer's Handbook page 3 to 21

## Questions
#### part one:
1. [Insomnia cure](https://codeforces.com/problemset/problem/148/A)
2. [Anton and Letters](https://codeforces.com/problemset/problem/443/A)
3. [Taxi](https://codeforces.com/problemset/problem/158/B)
4. [Rank List](http://codeforces.com/problemset/problem/166/A)
5. [Rock, Scissors, Paper](https://uva.onlinejudge.org/index.php?option=com_onlinejudge&Itemid=8&category=24&page=show_problem&problem=1384)

#### part two:
1. [Lovely Palindromes](https://codeforces.com/problemset/problem/688/B)
2. [Guess the Permutation](https://codeforces.com/problemset/problem/618/B)
3. [New Year's Eve](https://codeforces.com/problemset/problem/912/B)
4. [Plate Game](http://codeforces.com/problemset/problem/197/A)
5. [Traffic Lights](https://uva.onlinejudge.org/index.php?option=com_onlinejudge&Itemid=8&category=24&page=show_problem&problem=97)

## Editorial
#### part one:
1. see part *148A - Insomnia cure* [in this editorial](https://codeforces.com/blog/entry/3819)
2. see part *443A - Anton and Letters* [in this editorial](https://codeforces.com/blog/entry/12739)
3. see part *B 158B - Taxi* [in this editorial](https://codeforces.com/blog/entry/4089)
4. see part *166A - Rank List* [in this editorial](http://codeforces.com/blog/entry/4173)
5. see part *Rock, Scissors, Paper* [this editorial](http://www.algorithmist.com/index.php/UVa_10443). also see [code](https://github.com/maryam97/ACM/blob/master/UVa%20problems/10443%20Rock,%20Scissors,%20Paper.cpp)

#### part two:
1. see part *688B: Lovely Palindromes* [in this editorial](https://codeforces.com/blog/entry/45770)
2. see part *Guess the Permutation* [in this editorial](https://codeforces.com/blog/entry/23142)
3. see part *912B - New Year's Eve* [in this editorial](https://codeforces.com/blog/entry/56920)
4. see part *197A - Plate Game* [in this editorial](http://codeforces.com/blog/entry/4717)
5. see part *Traffic Lights* [in this section](#traffic-lights)

##### Traffic Lights
>You should search over all 5 hours (18000 seconds) to find a second which all of the traffic lights show green simultaneously.
For every input x, we know that its light cycle is 2x seconds and its green period is between start of the cycle and x-5 (after x- 5 seconds, the light turns orange)
Notice that you should start searching from one second after the first light turns red, due to assumption of the question.
For exmaple for the first test case, start searching from second 20 (19+1) which first light has turned red , you wil find that in second 40 both of the lights are green.

see [code](https://github.com/mehranagh20/ACM-ICPC/blob/master/uva/161-Traffic-Lights/161-Traffic-Lights.cpp)


##### For more questions in this topic see codeforces questions with [*constructive algorithms*](https://codeforces.com/problemset/tags/constructive%20algorithms) and [*implementation*](https://codeforces.com/problemset/tags/implementation) tags.
