# CMPS 2200 Assignment 5
## Answers

**Name:**_________________________


Place all written answers from `assignment-05.md` here for easier grading.





- **1a.**
Explanation:
  Let X be the possible number of solutions when exchanging ____ dollars for Geometrica. When exchanging ____ dollars the algorithm will determine which combination of sums of 2^k is most efficient. For example, when exchanging $9 the algorithm will compute 2^0 + 2^3. 
  The algorithm would first check for if the exchanged number of dollars is an odd number.
    If it is, it would subtract 2^0.
  The algorithm would then calculate the greatest power of two that can be subtracted from the exchanged value (for example if there were 72 dollars then 64 dollars would be subtracted because 2^6 is 64)
    The algorithm would then repeat this process until it reaches 0.

Optimal?
This algorithm is optimal because it will always select the highest value of 2^k that can be subtracted from the total exchanged value. It will continue to call itself until the value is reduced to zero.






- **2b.**



