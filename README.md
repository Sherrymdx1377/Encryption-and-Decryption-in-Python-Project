# Case Description

Cryptography is a critical problem in programming that has engaged researchers for many decades. With better encryption methods, we can better protect sensitive information—such as passwords and personal data—and ensure secure online communication. Exploring such methods as the transposition cipher (the topic of this project) is an essential step towards contributing to the ongoing efforts to maintain data integrity and confidentiality.

The transposition cipher is a simple yet effective way of encrypting a text in a way that becomes unreadable to anyone who doesn’t possess the key to decryption. It relies on scrambling the words in plaintext by rearranging its characters.

Transposition ciphers come in various forms, each contributing a unique layer of complexity. Among these variants, the columnar transposition cipher stands as a foundational pillar, offering an accessible entry point for understanding the core concepts of this encryption methodology involving Python cryptography.

The Encryption and Decryption in Python project requires you to implement a TranspositionCipher class incorporating the following elements:

- A constructor function that accepts the cipher's key as an argument
- A method designated for encrypting a message requiring a single parameter—the plaintext message to be encrypted
- A method dedicated to decrypting a message that calls for one argument—the previously encrypted message in ciphertext format
- Optional: As an additional challenge—not required for completing the project—you can implement a function outside the TranspositionCipher class, which hacks the columnar transposition cipher, i.e., it decrypts a - ciphertext without knowing the key. The function should return the decrypted message and the key.

# Project requirements

For this Encryption and Decryption in Python project, you’ll work with Python 3 or newer and an IDE of your choice (Jupyter Notebook, Spyder, PyCharm, Visual Studio, etc.) Still, note that the file attached to this project is a Jupyter Notebook. For the optional part of the project, you must install the PyDictionary library.

# Project content

- Part 1: Create the Constructor
- Part 2: Encrypt a Message
- Part 3: Decrypt a Message
