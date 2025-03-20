 Caesar Cipher

 Overview
This is a simple Python implementation of the Caesar Cipher, a basic encryption and decryption technique that shifts the letters of a message by a specified number of positions in the alphabet.

 Features
- Encrypts messages using the Caesar Cipher technique.
- Decrypts messages by reversing the shift.
- Preserves non-alphabetic characters (such as spaces and punctuation).
- Supports both uppercase and lowercase letters.

 How It Works
The script takes user input for:
1. The message to be encrypted or decrypted.
2. The shift value (number of positions to shift in the alphabet).
3. Whether to encrypt or decrypt the message.

 Usage
Run the script and follow the prompts:

```sh
python caesar_cipher.py
```

Example
```
Enter your message: Hello, World!
Enter shift value: 3
Do you want to (E)ncrypt or (D)ecrypt? e
Encrypted Message: Khoor, Zruog!
```

```
Enter your message: Khoor, Zruog!
Enter shift value: 3
Do you want to (E)ncrypt or (D)ecrypt? d
Decrypted Message: Hello, World!
```

 Code Explanation
- The function `caesar_cipher(text, shift, encrypt=True)` performs both encryption and decryption based on the shift value.
- The shift is reversed for decryption by setting `shift = -shift`.
- Alphabetic characters are shifted while non-alphabetic characters remain unchanged.

 Requirements
- Python 3.x

 Contributing
Feel free to fork this repository, submit pull requests, or report issues.

 License
This project is licensed under the MIT License.

