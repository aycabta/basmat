
Bashicu Matric Calculator
=========================

[Web interface is available](http://gyafun.jp/ln/basmat.cgi).

Author: [Fish](http://googology.wikia.com/wiki/User:Kyodaisuu)

## Usage

```
basmat ini [max] [opt] [step]
```

* ini
    * Initial variable in the form of BM[n], where BM is a sequence expression of Bashicu matrix, and n is a natural number. n=2 if not given.
* max
    * Maximum length of sequence. Default is 20.
* opt
    * Calculation option. Default is 1.
    * opt = 1: n is constant.
    * opt = 2: n = n+1 for each loop.
    * opt = 3: n = n\*n for each loop.
    * opt = 4: Simulate Hardy. n=n+1 for successor, and copy n-1. It matches Hardy function for ordinals below epsilon\_0.
* step
    * Maximum step of calculation. Default is 0 (no limit).

## Example
```
basmat "(0,0)(1,1)[3]" 100000 2
basmat "(0,0)(1,1)[3]" 10000000 4
basmat "(0,0)(1,1)[3]" 13000 1 100000
```

