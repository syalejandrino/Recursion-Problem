# Recursion-Problem
A Curious Recursion problem with pre-defined arguments
Define a function H that takes three non-negative integer arguments and returns an integer as follows:

 H(0, a, b) = b+1
 
 H(1, a, 0) = a 

 H(2, a, 0) = 0 
 
 H(n, a, 0) = 1, if n >= 3
 H(n, a, b) = H(n-1, a, H(n, a, b-1)), if n >= 1 and b >= 1

Part 2:

Prove that  H(n, 2, 2) = 4 , for all strictly positive n. Submit a written proof (in English, since we have not talked about doing this kind of proof in Natural Deduction).
