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

# Cryptanalysis

The science of recovering the plaintext of a message without accessing the key. Breaking an encryption without the key being lost is a type of compromise.

If you attempt this, it's an attack.

# Cryptanalytic Attacks

* Ciphertext-only attack
* * The cryptanalyst has the ciphertext of several messages, all of which have been encrypted using the same encryption algorithm. 
* Known-plaintext attack
* * The cryptanalyst has access not only to the ciphertext of several messages, but also to the plaintext of those messages.
* Chosen-plaintext attack
* * The cryptanalyst not only has access to the ciphertext and associated plaintext for several messages, but he also chooses the plaintext that gets encrypted.
* Adaptive-chosen-plaintext attack
* * When the cryptanalyst can choose the plaintext that is encrypted, but also modify the choice based on the results of previous encryptions. 
* Chosen-ciphertext attack
* * The cryptanalyst is able to choose multiple types of ciphertext to be decrypted and has access to the plaintext
* Chosen-key attack
* * The cryptanalyst has some knowledge about the relationship between different keys. Not practical apparently.
* Rubber-host cryptanalysis
* * When a cryptanalyst tries to threaten, blackmail, or torture someone until they provide the key. If it's bought, that's a purchase-key attack. Unfortunately a powerful attack and possibly common...


