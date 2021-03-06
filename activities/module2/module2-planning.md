# MTH 225 Module 2

Main concepts: 

- Division algorithm
- The `%` operator 
- Arithmetic with the `%` operator 
- Cryptography

Possible AEP material: 
- Extended Euclidean Algorithm and finding multiplicative inverses -- application to crypto


Learning objectives 

- State the Division Algorithm and explain the main points 
- State the Euclidean Algorithm 
- Use the Euclidean Algorithm to find the gcd of two integers 
- Given two integers a, n with n > 0, find `a % n`
- Use the repeated squaring technique to find large powers of a mod n
- Employ basic cryptosystems involving modular arithmetic 


Remixed

On second thought, no Euclidean Algorithm

Module 2A: 
- Basic
  - State the Division Algorithm and explain the main points 
  - Given two integers a, n with n > 0, find `a % n`
  - Encrypt and decrypt using the shift cipher given the key 
- Advanced
  - Decipher a shift cipher with no key (given ciphertext, or just brute force) 
  - Encrypt and decrypt using the multiplicative cipher 

For later: 
  - Use the repeated squaring technique to find large powers of a mod n


## In class 

### Module 2A 

- Part 1: Review/QA 
- Part 2: Main ideas 
  - Writing a program to do the shift cipher
  - Writing a program to decrypt the shift cipher -- do it without subtraction 
  - Multiplicative cipher -- try it out 
  - How to decrypt? Only certain numbers work 
- Part 3: Wrap up
  - What were the main points
  - Brief polling quiz 
  - Feedback form 


- Recap of DP 
- Arithmetic with `%` 
- Application: Shift cipher 
- Application: Multiplicative cipher (which keys do you not want to use?) 
- Powers: Don't raise power first then `%` 
- Explanation of the technique 
- Then they practice 

### Module 2B 

- Crypto challenge -- they learn the cryptosystems before class then come to class ready to work 
- Encrypt
- Decrypt with a sample ciphertext 
- Decrypt with no ciphertext 

Systems: 
- Basic shift
- Multiplicative 
- Basic public key ()