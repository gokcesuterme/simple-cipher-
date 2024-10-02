*********************************************************************
************* Writen and Coded by Gökçesu Terme *********************
*********************************************************************


SIMPLE CHIPPER PROGRAM

- Description 

The Simple Cipher Program uses a classic encryption-decryption mechanism in two phases. It employs a polyalphabetic substitution technique followed by a simple transposition process. The program encrypts the plaintext in the first phase using a key and a conversion table. If the key is shorter than the plaintext, it repeats the key. The program divides the resulting ciphertext into two halves in the second phase. It then rearranges the characters by alternately selecting from each half. For decryption, it reverses the process, starting with rearrangement and then substituting characters using the conversion table. 

Python was chosen as the programming language for this project. Python was selected because of its simplicity, readability, and extensive standard library.


- How to Compile and Run

  Prerequisites:
	Python 3.x installed
	PyCharm IDE (recommended for running this program,it's not strictly necessary)
  How to Run:
	1. Load  the project "CNG438gokcesutermeA1" and open PyCharm: Start PyCharm and open the project directory where the script is 	located.
	2. Add Python Interpreter: Ensure a Python interpreter is configured for your project by navigating to File > Settings > Project: ProjectName > Python Interpreter. If not 	already set, add a new interpreter or select an existing one.
	3. The tabe.txt file is already located in the same directory as script, do not locate a new one.
	4. After opening the project click "gokcesutermeA1.py" and run the python code. You can use the green play button in the toolbar to run the script.
	5. Follow On-screen Instructions: when you run the program a menu will be shown as:
						"Simple Cipher
						[1] Encrypt
						[2] Decrypt
						[3] Exit
						Selection: "
	Enter 1 to encrypt text, 2 to decrypt text, or 3 to exit the program.
	Follow the on-screen instructions to enter the necessary input for encryption or decryption.

!!NOTE!! -> It is assumed that the user will not enter a key that has a length longer than the input text!
