# mergesort


## [16,21,11,8,12,22] -> Dizisinin

1. sort türüne göre aşamaları aşağıda yer almaktadır

[16,21,11,8,12,22] n eleman
[16, 21, 11] [8, 12, 22]
[16] [21, 11]  [8] [12, 22]
[16] [21] [11] [8] [12] [22]
[16] [11, 21]  [8] [12, 22]
[11, 16, 21] [8, 12, 22]
[8, 11, 12, 16, 21, 22]


2. Big-O gösterimi

2^x=n      , n eleman
x=log(n) 
n*log(n)
Average case: O(n*logn)
