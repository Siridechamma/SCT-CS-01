Caesar Cipher Program
Overview
This project is a simple Python implementation of the Caesar Cipher, one of the oldest and most well-known encryption techniques. The program allows users to encrypt and decrypt messages by shifting letters in the alphabet by a specified number of positions. Non-alphabetic characters remain unchanged, ensuring the structure of the message is preserved.
Features
- Encrypt messages with a user-defined shift value.
- Decrypt messages using the same shift value.
- Handles both uppercase and lowercase letters correctly.
- Leaves spaces, punctuation, and numbers unchanged.
- Input validation for shift values to prevent errors.
How It Works
The Caesar Cipher works by shifting each letter in the message by a fixed number of positions in the alphabet:
- For encryption, letters are shifted forward.
- For decryption, letters are shifted backward.
Example:
- Message: HELLO
- Shift: 3
- Encrypted: KHOOR

