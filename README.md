RC4 Encryption and Decryption Program
This program allows you to securely encrypt and decrypt messages using the RC4 stream cipher. RC4 is a symmetric key cipher known for its efficiency in generating a pseudo-random stream of bytes, which is used to protect the confidentiality of your messages. By providing an encryption key, you can encode your messages, and then decode them back to their original form using the same key.

Usage
Encrypt and Decrypt a Message from a Text File:
Enter the name of the key file, input file, and output file.
The program will read the key and plaintext from the input file, encrypt the plaintext using RC4, and write the ciphertext to the output file.
Encrypt and Decrypt a Manually Entered Message:
Enter a key between 5 and 32 bytes.
Enter the message to encrypt/decrypt.
The program will encrypt the message using RC4 and display the encrypted message in hexadecimal format.
It will then decrypt the ciphertext and display the decrypted message.
Note
The key must be between 5 and 32 bytes long.
The input file and output file should be in binary format.
The program will overwrite the output file if it already exists.
Getting Started
Clone the repository: git clone https://github.com/your-username/rc4-encryption.git
Compile the program: g++ rc4.cpp -o rc4
Run the program: ./rc4
