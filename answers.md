# CMPS 2200 Assignment 5
## Answers

**Name:**_________________________


Place all written answers from `assignment-05.md` here for easier grading.





- **1a.**
Explanation:

Let X be the possible number of solutions when exchanging ____ dollars for Geometrica. When exchanging ____ dollars the algorithm will determine which combination of sums of 2^k is most efficient. For example, when exchanging $9 the algorithm will compute 2^0 + 2^3.

  The algorithm would first check if the number of dollars being exchanged is 0 or 1.
  
If the value is zero, the algorithm returns zero. If the value is one, then the algorithm returns 2^0.

The algorithm would then check for if the exchanged number of dollars is an odd number. If it is, it would subtract 2^0 in order to make the new value an even number.

The algorithm would then calculate the greatest power of two that can be subtracted from the exchanged value (for example if there were 72 dollars then 64 dollars would be subtracted because 2^6 is 64)
    
Each time the algorithm subtracts 2^k from the exchanged dollar value, it adds the 2^k to a total sum. 

The algorithm would then repeat this process by calling itself until it reaches 0, and returns the sum of the powers of 2^k.
***
**Optimal?**

This algorithm is optimal because it will always select the highest value of 2^k that can be subtracted from the total exchanged value. It will continue to call itself until the value is reduced to zero.

**1b.**
For when exchanging 63 dollars.

O(log_2^63)

The Work of the algorithm would be

The Span of the algorithm would be


**2a.**
The greedy algorithm from 1a is not optimal because there may not be a bill to the power of two in that denomination. For example, I could be trying to exchange 17 dollars.
  In the original algorithm, it would subtract 2^0 and then 2^4.
However, as the denominations in Fortuito are random. The most optimal solution could be using a bill of the denomination of 5 and 12. 

- **2b.**



