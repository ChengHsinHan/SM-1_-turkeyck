#Problem 0

1.Write a program (or modify the one given) to calculate and print out the histogram of the number of times each side occurs, the deviation of this number from one-sixth of the number of trials, the frequency with which each side occurs, and the deviation of this from one sixth. Hand in a copy of the code you used.

2.Show a typical print-out of your program.

3.Run the program for various numbers of random integers, starting with a small number, say 10, and increasing to a substantially larger number. The only upper limit is that the program should not take more than about one second to run. ([Your time is valuable.) THIS IS A COMPUTATIONAL PROBLEM. ANSWERS MUST BE ACCOMPANIED BY DATA. Please hand in hard copies for all data to which you refer in your answers.

4.As the number of trials increases, does the magnitude (absolute value) of the differences between the number of times a given side occurs and one-sixth of the number of trials increase or decrease? (Hint: This is not the same question as the next one.)

5.As you increase the number of trials, does the ratio of the number of times each side occurs to the total number of trials approach closer to 1/6?

Ans:
1.  problem 0(problem 0.py)
2.![123](https://imgur.com/Uy7lYDO)
One die with 6 sides

Number of trials =  1

[0, 0, 0, 0, 0, 0]

s, N_s, N_s-N/6, N_s/N, N_s/N-1/6

1 0 -0.16666666666666666 0.0 -0.16666666666666666
   2 0 -0.16666666666666666 0.0 -0.16666666666666666

3 0 -0.16666666666666666 0.0 -0.16666666666666666

4 1 0.8333333333333334 1.0 0.8333333333333334

5 0 -0.16666666666666666 0.0 -0.16666666666666666

6 0 -0.16666666666666666 0.0 -0.16666666666666666

Elapsed time = 0.0015051406890094336

3.
One die with 6 sides
Number of trials =  1
[0, 0, 0, 0, 0, 0]
s,  N_s,      N_s-N/6,          N_s/N,     N_s/N-1/6
1    0   -0.16666666666666666    0.0   -0.16666666666666666
2    0   -0.16666666666666666    0.0   -0.16666666666666666
3    0   -0.16666666666666666    0.0   -0.16666666666666666
4    1    0.8333333333333334     1.0    0.8333333333333334
5    0   -0.16666666666666666    0.0   -0.16666666666666666
6    0   -0.16666666666666666    0.0   -0.16666666666666666
Elapsed time = 0.0015051406890094336


One die with 6 sides
Number of trials =  10
[0, 0, 0, 0, 0, 0]
s, N_s, N_s-N/6, N_s/N, N_s/N-1/6
1 1 -0.6666666666666667 0.1 -0.06666666666666665
2 3 1.3333333333333333 0.3 0.13333333333333333
3 2 0.33333333333333326 0.2 0.033333333333333354
4 0 -1.6666666666666667 0.0 -0.16666666666666666
5 1 -0.6666666666666667 0.1 -0.06666666666666665
6 3 1.3333333333333333 0.3 0.13333333333333333
Elapsed time = 0.00041644988903880215


One die with 6 sides
Number of trials =  100
[0, 0, 0, 0, 0, 0]
s, N_s, N_s-N/6, N_s/N, N_s/N-1/6
1 29 12.333333333333332 0.29 0.12333333333333332
2 16 -0.6666666666666679 0.16 -0.006666666666666654
3 12 -4.666666666666668 0.12 -0.04666666666666666
4 14 -2.666666666666668 0.14 -0.026666666666666644
5 14 -2.666666666666668 0.14 -0.026666666666666644
6 15 -1.6666666666666679 0.15 -0.016666666666666663
Elapsed time = 0.00043855528599252066
====================
One die with 6 sides
Number of trials =  1000
[0, 0, 0, 0, 0, 0]
s, N_s, N_s-N/6, N_s/N, N_s/N-1/6
1 166 -0.6666666666666572 0.166 -0.0006666666666666488
2 166 -0.6666666666666572 0.166 -0.0006666666666666488
3 170 3.333333333333343 0.17 0.003333333333333355
4 170 3.333333333333343 0.17 0.003333333333333355
5 172 5.333333333333343 0.172 0.005333333333333329
6 156 -10.666666666666657 0.156 -0.010666666666666658
Elapsed time = 0.0020400123474431557
====================
One die with 6 sides
Number of trials =  10000
[0, 0, 0, 0, 0, 0]
s, N_s, N_s-N/6, N_s/N, N_s/N-1/6
1 1658 -8.666666666666742 0.1658 -0.0008666666666666545
2 1632 -34.66666666666674 0.1632 -0.0034666666666666457
3 1691 24.333333333333258 0.1691 0.002433333333333343
4 1679 12.333333333333258 0.1679 0.0012333333333333363
5 1723 56.33333333333326 0.1723 0.005633333333333351
6 1617 -49.66666666666674 0.1617 -0.004966666666666647
Elapsed time = 0.07104200893847515
====================
One die with 6 sides
Number of trials =  100000
[0, 0, 0, 0, 0, 0]
s, N_s, N_s-N/6, N_s/N, N_s/N-1/6
1 16630 -36.66666666666788 0.1663 -0.00036666666666665404
2 16711 44.33333333333212 0.16711 0.0004433333333333511
3 16584 -82.66666666666788 0.16584 -0.00082666666666667
4 16680 13.33333333333212 0.1668 0.0001333333333333464
5 16770 103.33333333333212 0.1677 0.0010333333333333306
6 16625 -41.66666666666788 0.16625 -0.00041666666666664853
Elapsed time = 0.07832573723472537
====================
One die with 6 sides
Number of trials =  600000
[0, 0, 0, 0, 0, 0]
s, N_s, N_s-N/6, N_s/N, N_s/N-1/6
1 99667 -333.0 0.16611166666666666 -0.0005549999999999999
2 99931 -69.0 0.16655166666666665 -0.00011500000000000399
3 100169 169.0 0.16694833333333334 0.00028166666666668005
4 100526 526.0 0.16754333333333332 0.0008766666666666645
5 99734 -266.0 0.16622333333333333 -0.00044333333333332337
6 99973 -27.0 0.16662166666666667 -4.499999999998949e-05
Elapsed time = 0.42588968301650243

4.
As the number of trials increase, differences between the number of times a given side occurs and one-sixth of the number of trials increase.

5.
Yes,as the number of trials increase, the ratio of the number of times each side occurs to the total number of trials approach closer to 1/6.
