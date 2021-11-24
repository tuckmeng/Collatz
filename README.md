# Collatz

This is my solution to the Collatz Conjecture from a non-mathematician point of view. Wrote this on 24 Nov 2021 Singapore time. 

# Summary

Collatz Conjecture says for any number n, if it's odd, apply 3n+1 and if it's even, divide by 2 and eventually, you will get a continuing series of the same numbers. It asks you to prove it for all whole numbers.

# My Simple Thoughts

I set out a second conjecture: For any number n, if it's odd, apply n+1 and if it's even, divide by 2 and eventually, you will eventually get a continuing series of the same numbers.

If n is odd, n+1 will always make it even.
If n is even, dividing it by 2 will make it odd at some point.
So for any number, if you keep applying the second conjecture, you will get the same outcome as Collatz Conjecture. 

To me, this second conjecture looks true.

If we agree with above and accept the second conjecture as true, the first conjecture must be true because the possible numbers for 3n+1 is a subset of all possible numbers for n+1 (because n+1 is basically is the list of all even numbers if n is the list of all odd numbers). 
