# AES Encryption and Decryption Script

This project provides a command-line script for AES (Advanced Encryption Standard) encryption and decryption. AES is a widely-used symmetric encryption algorithm known for its security and efficiency. This script allows users to encrypt plaintext files and decrypt encrypted files using AES with a specified key.

### Installation
* Python 3.x
* pycrypto

You can install the missing dependencies thorugh `pip`

## Features

- AES encryption and decryption using a specified key.
- Support for different key sizes (128-bit, 192-bit, and 256-bit).
- Input validation and error handling for invalid files or keys.

## Prerequisites

Before running the script, ensure you have the following prerequisites:

- Python 3 installed on your machine.

## Usage

1. Clone this repository: `git clone https://github.com/CodeWreckPro/AES_Encryption_and_Decryption_Script.git`
2. Navigate to the project directory: `cd AES_Encryption_and_Decryption_Script`
3. Run the script with the following command:


Options:
- `-e` or `--encrypt`: Perform encryption.
- `-d` or `--decrypt`: Perform decryption.
- `-k <key>` or `--key <key>`: Specify the encryption/decryption key.
- `-s <key_size>` or `--key-size <key_size>`: Specify the key size (128, 192, or 256 bits).
- `-i <input_file>` or `--input <input_file>`: Specify the input file.
- `-o <output_file>` or `--output <output_file>`: Specify the output file.

Example commands:
- Encrypt a file: `python aes_script.py -e -k my_key -s 128 -i plaintext.txt -o encrypted.bin`
- Decrypt a file: `python aes_script.py -d -k my_key -s 128 -i encrypted.bin -o decrypted.txt`

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature: `git checkout -b feature-name`.
3. Make the necessary changes and commit them: `git commit -m 'Add some feature'`.
4. Push your changes to the branch: `git push origin feature-name`.
5. Open a pull request in the original repository.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

If you have any questions, suggestions, or feedback, please feel free to contact the project maintainer:

- Name: RAkshith S
- Email: rakshiths2001@gmail.com

Thank you for using the AES Encryption and Decryption Script!
