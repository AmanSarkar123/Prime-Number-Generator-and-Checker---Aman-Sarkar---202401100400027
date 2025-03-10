# Prime-Number-Generator-and-Checker---Aman-Sarkar---202401100400027
Prime Number Generator and Checker This program efficiently generates prime numbers and checks whether a given number is prime. 

Prime Number Generator and Checker - Problem Summary
The task involves two main functions:
1.	Prime Number Generator: Generate all prime numbers within a given range [a, b].
2.	Prime Number Checker: Verify whether a given number n is prime.
Constraints
•	1 ≤ a ≤ b ≤ 10^6 (for prime generation).
•	1 ≤ n ≤ 10^6 (for prime checking).
Methodology:-
1. Prime Number Generator: Use the Sieve of
Eratosthenes to mark non-prime numbers
efficiently.
2. Start with an array assuming all numbers are prime
and eliminate multiples of each prime.
3. Extract the remaining numbers in the given range
[a, b] as prime numbers.
4. Prime Number Checker: Use Trial Division to check
divisibility up to √n.
5. If n is divisible by any number in this range, it is not
prime; otherwise, it is prime.
6. The generator runs in O(n log log n), while the
checker runs in O(√n), ensuring efficiency.
7. The approach is optimized for handling large
inputs up to 10^6.
