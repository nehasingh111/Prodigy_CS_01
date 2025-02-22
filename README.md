Caesar Cipher GUI Application
This is a simple graphical user interface (GUI) application for text encryption and decryption using the Caesar cipher method. The application is built using Python's tkinter library.

Features
Encrypt Text: Encrypts the input text using the Caesar cipher with a specified key.
Decrypt Text: Decrypts the input text using the Caesar cipher with a specified key.
Reset Fields: Clears the input text and key fields.

Prerequisites
Python 3.x
tkinter library (comes pre-installed with Python)

Installation
Clone the repository or download the script file.
Ensure you have Python 3.x installed on your system.
Run the script using the following command:
python caesar_cipher_gui.py

Usage
Enter Text: Input the text you want to encrypt or decrypt in the text box.
Enter Key: Provide the key for the Caesar cipher in the key entry field.
Encrypt: Click on the "ENCRYPT" button to encrypt the text.
Decrypt: Click on the "DECRYPT" button to decrypt the text.
Reset: Click on the "RESET" button to clear the input fields.

Code Explanation
Main Screen
The mainscreen() function initializes the main GUI window with the title "Caesar Cipher". The window contains:

A text box for inputting the text to be encrypted or decrypted.
An entry field for specifying the key.
Buttons for encryption, decryption, and resetting the fields.
Encryption Function
The encrypt() function retrieves the input text and key, performs the Caesar cipher encryption, and displays the encrypted text in a new message box.

Decryption Function
The decrypt() function retrieves the input text and key, performs the Caesar cipher decryption, and displays the decrypted text in a new message box.

Reset Function
The reset() function clears the text box and key entry field.

Show Message Function
The show_message() function creates a new window to display the encrypted or decrypted text.

License
This project is licensed under the MIT License.

Acknowledgements
Python.org for the Python programming language.
tkinter for the GUI library.