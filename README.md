🔐 Substitution Cipher

A simple C program that encrypts plaintext using a user-provided key. Implements a classical substitution cipher in the command line.

💡 How It Works

The user inputs a 26-letter key and a plaintext string. The program validates the key and substitutes each letter in the plaintext with the corresponding letter from the key, preserving case.

Example:
- Key: QWERTYUIOPASDFGHJKLZXCVBNM
- Input: hello
- Output: itssg

🛠️ Tech

- Language: C  
- Compilation: Uses `clang` 

## ▶️ Usage

```bash
$ clang substitution.c -o substitution

$ ./substitution QWERTYUIOPASDFGHJKLZXCVBNM

plaintext:  hello

ciphertext: itssg


Key must meet the following criteria:

Exactly 26 alphabetic characters

No duplicate letters

Case-insensitive


👤 Author

Alina Miret Shah – @amshah1022

📄 License

This project is open source under the MIT License.
