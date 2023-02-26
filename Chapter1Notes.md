# Sender and Receiver

All communication occurs between sender and receivers. If you want to keep private communication private, you'll need to encrypt plaintext.

Plaintext, or cleartext, is normal text without any disguising or masking. It's what I'm writing in now!

Ciphertext is text that has undergone encryption - like good ol' Julius' Caesar's Cipher??


#Public Key Algorithms

Designed so the key to encrypt is different from that used to decrypt it. Pretty obvious, I guess. 

Encryption using public key K is denoted by:

E<sub>K</sub>(M) = C

Decryption is denoted as:
D<sub>K</sub>(C) = M

Ugh... math, I wasn't expecting this.

# Types of Symmetric algorithms

Also known as conventional algorithms
 
* Stream Ciphers
* * A cipher that encrypts and decrypts bit by bit
* Block Ciphers
* * A cipher that encrypts/decrypts by blocks, normally 64-bits at a time using modern computers
* * Note: I wonder how much will change when quantum releases?


# Examples

So what if I wanted to encrypt t0m_is_@cting_w3ird , because he is... How could I send that over the internet without Weirdo Tom finding out?
Guess that's covered later.

