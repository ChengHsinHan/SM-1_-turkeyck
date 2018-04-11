#Problem 0

1.Write a program (or modify the one given) to calculate and print out the histogram of the number of times each side occurs, the deviation of this number from one-sixth of the number of trials, the frequency with which each side occurs, and the deviation of this from one sixth. Hand in a copy of the code you used.

2.Show a typical print-out of your program.

3.Run the program for various numbers of random integers, starting with a small number, say 10, and increasing to a substantially larger number. The only upper limit is that the program should not take more than about one second to run. ([Your time is valuable.) THIS IS A COMPUTATIONAL PROBLEM. ANSWERS MUST BE ACCOMPANIED BY DATA. Please hand in hard copies for all data to which you refer in your answers.

4.As the number of trials increases, does the magnitude (absolute value) of the differences between the number of times a given side occurs and one-sixth of the number of trials increase or decrease? (Hint: This is not the same question as the next one.)

5.As you increase the number of trials, does the ratio of the number of times each side occurs to the total number of trials approach closer to 1/6?

Ans:
1.  problem 0(problem 0.py)

2.
<a href="https://imgur.com/Uy7lYDO"><img src="https://i.imgur.com/Uy7lYDO.png" title="source: imgur.com" /></a>


3.

	One die with 6 sides
	Number of trials = 1
	[0, 0, 0, 0, 0, 0] 
	s,   N_s,      N_s-N/6,           N_s/N,     N_s/N-1/6
	1    0   -0.16666666666666666    0.0   -0.16666666666666666
	2    0   -0.16666666666666666    0.0   -0.16666666666666666
	3    0   –0.16666666666666666    0.0   -0.16666666666666666
	4    1    0.8333333333333334     1.0    0.8333333333333334
	5    0   -0.16666666666666666    0.0   -0.16666666666666666
	6    0   -0.16666666666666666    0.0   -0.16666666666666666
	Elapsed time = 0.0015051406890094336

One die with 6 sides
Number of trials = 10
s,    N_s,     N_s-N/6,           N_s/N,   N_s/N-1/6
1     2    0.33333333333333326   0.2    0.033333333333333354
2     0    -1.6666666666666667   0.0    -0.16666666666666666
3     2    0.33333333333333326   0.2    0.033333333333333354
4     1    -0.6666666666666667   0.1    -0.06666666666666665
5     2    0.33333333333333326   0.2    0.033333333333333354
6     3    1.3333333333333333    0.3    0.13333333333333333
Elapsed time = 0.004119498618017951
====================
One die with 6 sides
Number of trials =  100
s,    N_s,     N_s-N/6,          N_s/N,     N_s/N-1/6
1     16   -0.6666666666666679  0.16     -0.006666666666666654
2     19   2.333333333333332    0.19     0.023333333333333345
3     22   5.333333333333332   0.22      0.053333333333333344
4     12   -4.666666666666668   0.12     -0.04666666666666666
5     16   -0.6666666666666679  0.16     -0.006666666666666654
6     15   -1.6666666666666679  0.15     -0.016666666666666663
Elapsed time = 0.009358082956817896
====================
One die with 6 sides
Number of trials =  1000
s,    N_s,     N_s-N/6,         N_s/N,       N_s/N-1/6
1    160  -6.666666666666657  0.16     -0.006666666666666654
2    158  -8.666666666666657  0.158    -0.008666666666666656
3    151  -15.666666666666657  0.151   -0.015666666666666662
4    175  8.333333333333343   0.175    0.008333333333333331
5    181  14.333333333333343  0.181    0.014333333333333337
6    175  8.333333333333343   0.175    0.008333333333333331
Elapsed time = 0.0038818656007654773
====================
One die with 6 sides
Number of trials =  10000
s,   N_s,     N_s-N/6,          N_s/N,       N_s/N-1/6
1   1690  23.333333333333258  0.169    0.002333333333333354
2   1709  42.33333333333326   0.1709   0.004233333333333339
3   1670  3.3333333333332575  0.167    0.00033333333333335213
4   1675  8.333333333333258   0.1675   0.0008333333333333526
5   1604  -62.66666666666674  0.1604   -0.00626666666666667
6   1652  -14.666666666666742  0.1652  -0.001466666666666644
Elapsed time = 0.02190565890267231
====================
One die with 6 sides
Number of trials =  100000
s,   N_s,     N_s-N/6,           N_s/N,         N_s/N-1/6
1   16714  47.33333333333212   0.16714    0.00047333333333335337
2   16770  103.33333333333212  0.1677     0.0010333333333333306
3   16587  -79.66666666666788   0.16587   -0.0007966666666666677
4   16621  -45.66666666666788   0.16621   -0.0004566666666666608
5   16611  -55.66666666666788   0.16611   -0.0005566666666666498
6   16697  30.33333333333212    0.16697   0.0003033333333333499
Elapsed time = 0.0827748431108925
====================
One die with 6 sides
Number of trials =  2000000
s, N_s, N_s-N/6, N_s/N, N_s/N-1/6
1  332447   -886.3333333333139    0.1662235   -0.00044316666666666116
2  332614   -719.3333333333139    0.166307    -0.00035966666666664704
3  333467   133.66666666668607    0.1667335   6.683333333334929e-05
4  333219   -114.33333333331393    0.1666095  -5.71666666666637e-05
5  333686   352.66666666668607    0.166843    0.0001763333333333339
6  334567   1233.666666666686    0.1672835    0.0006168333333333442
Elapsed time = 1.394806731724955


4.
As the number of trials increase, differences between the number of times a given side occurs and one-sixth of the number of trials increase.

5.
Yes,as the number of trials increase, the ratio of the number of times each side occurs to the total number of trials approach closer to 1/6.
