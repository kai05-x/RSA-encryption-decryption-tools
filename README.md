# project
**RSA Encryption and Decryption Tool**
This repository contains a simple RSA encryption and decryption tool built using Python and Tkinter for the graphical user interface (GUI). The tool allows users to generate RSA keys, encrypt messages, and decrypt messages using a user-friendly interface.

**Files**
The repository contains the following files:
1. main.py: The main script for the application, handling the GUI and main functionality for RSA encryption and decryption.
2. keygen.py: Contains the logic for generating RSA keys.
3. encryption.py: Contains the logic for RSA encryption and decryption.
4. README.md: This is  README file.
   
**Requirements**
To run this application, you need Python installed on your system. Additionally, you need the Tkinter library for the GUI. Tkinter is included with Python standard library, so no extra installation is required for it.

**Generating RSA Keys**
1. When the application starts, you will see an input form.
2. Enter 1 to generate RSA keys.
3. A message box will appear indicating that the keys have been generated. The keys will be saved in the output.txt file.
   
**Encrypting a Message**
1. Enter 2 in the input form to open the RSA encryption window.
2. Enter the encryption key, N, and the message you want to encrypt.
3. Click the "Encrypt" button. The encrypted message will be displayed in the "Encrypted Message" field.
   
**Decrypting a Message**
1. Enter 2 in the input form to open the RSA decryption window.
2. Enter the encryption key, N, the decryption key, and the message you want to decrypt.
3. Click the "Decrypt" button. The decrypted message will be displayed in the "Decrypted Message" field.
   
**Exiting the Application**

Enter 3 in the input form to exit the application.

**Code Overview**

`main.py`
This file contains the main GUI code using Tkinter. It handles the user input for selecting encryption, decryption, and key generation. It also contains the logic for opening new windows for encryption and decryption, as well as calling the appropriate functions from encryption.py.

`keygen.py`
This file contains the logic for generating RSA keys. It includes functions for checking prime numbers, generating large prime numbers, and calculating the RSA keys.

`encryption.py`
This file contains the logic for RSA encryption and decryption. It includes functions for encrypting and decrypting messages using the RSA algorithm.

**Contributing**

Contributions are welcome! If you have any suggestions or improvements, please feel free to open an issue or create a pull request.

