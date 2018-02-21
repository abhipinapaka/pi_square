# pi_square
The mathematical constant Pi is an irrational number with value approximately 3.1415928... The precise value of this constant can be obtained from the following inﬁnite sum:

Pi^2 = 8 + 8/3^2 + 8/5^2 + 8/7^2 + 8/9^2 + ...

(Pi is of course just the square root of this value.) 

Although we cannot compute the entire inﬁnite series, we get a good approximation of the value of Pi^2 by computing the beginning of such a sum. 
Write a function approxPIsquared() that takes as input float error and approximates constant Pi^2 to within error by computing the above sum, term by term, until the difference between the new and the previous sum is less than error. The function should return the new sum. 

>>> approxPIsquared(0.0001)
9.855519952254232

>>> approxPIsquared(0.00000001)
9.869462988376474
