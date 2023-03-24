# process of encryption and decryption

The major of process of sending a message safely.

Suppose Allen want to send a message "Hello World" to Bob.

    1) Allen encrypts the plaintext "Hello World" to ciphertext.
    2) Allen sends the ciphertext to Bob.
    3) Bob recieves the ciphertext from Allen.
    4) Bob decrypts the ciphertext to plaintext.
    
Now, you may have came up with questions, how to encrypt and decrypt it?    

There are two major category to encrypt the plaintext.

    1) Symmetric encryption (中文譯:對稱加密法)
    2) Asymmetric encryption (中文譯:非對稱加密法，又稱公開加密法)
    
## Symmetric encryption

Suppose Allen want to send a message "Hello World" to Bob.

    1) Allen encrypts the plaintext "Hello World" to ciphertext using the private key (it behaves as a program, it can translate any plaintexts and ciphertexts using an algorithm).
    2) Allen sends the ciphertext and private key to Bob.
    3) Bob recieves the ciphertext and private key from Allen.
    4) Bob decrypts the ciphertext to plaintext using the private key.
    
NOTE that 
    
    1) It is important to protect the private key. If it is intercepted by others, then the ciphertext may be decrypted in a very short time.
    
    If it is lost, it may be very hard to decrypt the ciphertext.
    
    2) Using a safe algorithm as private keys. If NOT do so, the ciphertext will be decrypt in a very short time.
    
    3) Here a safe algorithm refers an algorithm which, for any ciphertext, it can NOT be decrypted in available time (theoretically, it is the best to use a NP-time algorithm.)
    
    
## Asymmetric encryption 

Suppose Allen want to send a message "Hello World" to Bob.

    1) Allen encrypts the plaintext "Hello World" to ciphertext using the private key (it behaves as a program, it can translate any plaintexts and ciphertexts using an algorithm).
    2) Allen sends the ciphertext and private key to Bob.
    3) Bob recieves the ciphertext and private key from Allen.
    4) Bob decrypts the ciphertext to plaintext using the private key.
    
