# Sieve-Of-Eratosthenes

The sieve of Eratosthenes is a simple, ancient algorithm for finding all prime numbers up to any given limit.

It does so by iteratively marking as composite (i.e., not prime) the multiples of each prime, starting with the first prime number, 2. 
The multiples of a given prime are generated as a sequence of numbers starting from that prime, with constant difference between them that is equal to that prime.
This is the sieve's key distinction from using trial division to sequentially test each candidate number for divisibility by each prime.


**Algorithmic complexity**

This algorithm requires time complexity of - O(n*log(log(n))).  
The basic algorithm requires O(n<sup>2</sup>) of time complexity.

The modified Sieve-Of-Eratosthenes takes O(n) of time complexity which is much less than that of basic algorithm and also less than basic Sieve-Of-Eratosthenes.  
