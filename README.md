Caeser Cipher Encryption and Decryption Tool

Overview
This is a simple Python program that implements the Caesar Cipher encryption and decryption algorithm. The Caesar Cipher is a type of substitution cipher where each letter in the text is shifted by a certain number of positions in the alphabet.

Users can input a message and choose to either encrypt or decrypt it using a shift value (also known as the key). The program supports both uppercase and lowercase letters, while non-alphabetic characters (such as spaces and punctuation) remain unchanged.

Features
Encryption: Shifts each letter in the message forward by the specified shift value.
Decryption: Shifts each letter in the message backward by the specified shift value.
Supports both uppercase and lowercase letters.
Non-alphabetic characters are preserved (e.g., spaces, punctuation).

How It Works
Encrypt: Each letter in the message is shifted forward by the shift value.
Example: If the shift is 3, 'A' becomes 'D', 'B' becomes 'E', etc.
Decrypt: Each letter in the message is shifted backward by the shift value.
Example: If the shift is 3, 'D' becomes 'A', 'E' becomes 'B', etc.

Requirements
Python 3.x
Usage
Clone or download the repository.

Open a terminal and navigate to the directory containing the program.

Run the program by typing:

python caesar_cipher.py

When prompted, choose whether to encrypt or decrypt by entering E or D.

Input the message you want to encrypt or decrypt.

Enter the shift value (an integer).

The program will output the encrypted or decrypted message.

Example
Do you want to (E)ncrypt or (D)ecrypt? E
Enter your message: Hello World!
Enter the shift value (integer): 3
Encrypted Message: Khoor Zruog!

Do you want to (E)ncrypt or (D)ecrypt? D
Enter your message: Khoor Zruog!
Enter the shift value (integer): 3
Decrypted Message: Hello World!

Files
caesar_cipher.py: The Python script that implements the Caesar Cipher encryption and decryption.

Code Overview
encrypt(text, shift): Encrypts the input text by shifting each letter forward by the specified shift value.
decrypt(text, shift): Decrypts the input text by shifting each letter backward by the specified shift value.
caesar_cipher(): The main function that interacts with the user and calls the encryption or decryption functions based on user input.

License
This project is licensed under the MIT License.

Acknowledgments
The Caesar Cipher algorithm is one of the oldest and simplest forms of encryption, attributed to Julius Caesar.
