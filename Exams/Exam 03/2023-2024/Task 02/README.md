# Царство (Medium) - [HackerRank](<https://www.hackerrank.com/contests/kontrolno-3/challenges/challenge-4346>)


### Statement:

Дадено е царство, в което има йерархия и е под формата на дърво, индексирано от $0$ до $N$. Всеки връх съответства на даден човек от царството. Царят е с индекс $0$ и е началник на всички останали. Ако връх с индекс $x$ е родител на друг връх с индекс $y$, това означава, че човекът, съответстващ на върха с индекс $x$, e пряк началник на човека, съответстващ на индекс $y$. Вашата задача е по дадена йерархичната структура на царството да намерите за всеки един от върховете колко поданика има(колко върха има под него).


### Input format

Въвежда се броя $N$ на хората в царството. 

На всеки от следващите редове се въвеждат по две числа $x$ и $y$, като това значи, че човекът, чийто връх в дървото е с индекс $x$, е родител на човека с индекс в дървото $y$ .    


### Constraints

$1 \le N \le 10^6$

### Output format

Извеждат се N числа разделени с празно място, като $i$-тото число отговаря на броят поданици, на $i$-тия връх от дървото


### Samples


#### Sample Input 0
```
9
0 1
0 2
1 3
1 4
1 5
1 6
4 7
7 8
```

#### Sample Output 0
```
8 6 0 0 2 0 0 1 0
```