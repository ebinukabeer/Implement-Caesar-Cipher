# Caesar Cipher Tool

This is a basic command-line tool written in Python to **encrypt** or **decrypt** messages using the **Caesar Cipher** technique. The Caesar Cipher is a simple substitution cipher where each letter in the plaintext is shifted a certain number of places down or up the alphabet.

## 🔧 Features

* Encrypts text using a shift value
* Decrypts previously encrypted text
* Preserves the case of letters
* Keeps non-alphabetic characters (spaces, punctuation) unchanged

## 🧱 How It Works

The script prompts the user to choose between encryption (`e`) and decryption (`d`), takes the input message and a shift value, and returns the result.

## 📝 Example Usage

Caesar Cipher Tool
Type 'e' to encrypt or 'd' to decrypt: e
Enter your message: Hello, World!
Enter the shift value: 3
Encrypted message: Khoor, Zruog!


## 🔁 Decryption Example


Caesar Cipher Tool
Type 'e' to encrypt or 'd' to decrypt: d
Enter your message: Khoor, Zruog!
Enter the shift value: 3
Decrypted message: Hello, World!


## 🖥️ Running the Script

Make sure you have Python installed, then run:


python caesar_cipher.py
