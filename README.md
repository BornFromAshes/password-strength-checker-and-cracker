# password-strength-checker-and-cracker
A password strength checker and cracker
This project consists of two phases and the first phase consists of two parts. 

## Phase 1 - Part 1
With the section related to password security in the standard document NIST.sp.800-63b in mind we want to  implement the password security evaluation tool with Python language.
The program will receive the word as an input and after checking it, displays its strength as an output according to the standard.
The password will also be checked if it's available in a dictionary used by attackers.

## Phase 1 - Part 2
In this section, we are implementing a password-cracking tool using Python.
The tool takes a string as input as a password to be cracked and then tries to find that password and displays the guess of the duration of the check as well as the number of guesses as an output to the user. For convenience, you can enter the number of password characters as input to the program.
The program includes the following work modes:
1.  Standard mode that takes only the number of password characters from the user.
2. Search mode by knowing the first letter: in this mode, the first letter of the password is given as input to the program.
3. Search mode knowing k characters of the password: in this mode, the value of k characters out of n characters of the password is given to the program as input.


## Phase 2
In this phase, we implemented a cryptographic tool using Python.
This tool is implemented in the following two working modes.
1. Encryption mode: In this mode, the program takes a file as input and saves it encrypted in the system after encryption.
2. Decoding mode: In this mode, the program takes an encrypted file as input and after decoding it, saves the file in the system.

**Important note:** In both working modes, the encryption key must be taken from the user as a text string of the password.
