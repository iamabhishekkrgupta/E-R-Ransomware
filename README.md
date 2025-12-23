# E-R-Ransomware
Encrypted File Protection &amp; Recovery System  (Ransomware)
🔐 Encrypted File Protection & Recovery System
(Educational Project – Linux Only)
📌 Project Overview
This project is an educational simulation of file encryption and decryption using Python and Fernet symmetric cryptography.
It demonstrates how files inside a directory can be encrypted and later restored using a secret key and authentication phrase.

⚠️ Important Note

This project is created strictly for educational purposes only
It is intended to run only on Linux-based systems
Running this project on Windows may trigger antivirus or security software
🖥️ Supported Platform
✅ Linux (Ubuntu, Kali Linux, Parrot OS, Debian-based)
❌ Windows (Not supported)
❌ macOS (Not tested)
⚙️ Requirements
Software Requirements
Python 3.x
pip (Python package manager)
Git
Linux Terminal
Python Dependency
cryptography library (Fernet)
Install dependency using:

pip3 install cryptography

📂 Project Structure
encrypted-file-project/
│
├── encrypt.py        # Encrypts files in the directory
├── decrypt.py        # Decrypts files using secret phrase
├── README.md         # Project documentation
├── .gitignore        # Excludes sensitive files

🚀 How to Use (Step-by-Step Guide)
🔹 Step 1: Clone the Repository

Open terminal and run:

git clone https://github.com/iamabhishekkrgupta/E-R-Ransomware.git


Navigate into the project directory:

cd encrypted-file-project

🔹 Step 2: Create Test Files (IMPORTANT)

Create 2–3 dummy files for testing:

echo "This is test file 1" > file1.txt
echo "This is test file 2" > file2.txt
echo "This is test file 3" > file3.txt


Verify files:

ls

🔹 Step 3: Run Encryption Script

Execute:

python3 encrypt.py


✔️ This will:

Generate an encryption key (thekey.key)

Encrypt all files in the directory except scripts

Make files unreadable

🔹 Step 4: Run Decryption Script

Execute:

python3 decrypt.py


When prompted:

Enter secret phrase:


Enter:

coffee


✔️ Files will be decrypted successfully if the phrase is correct
❌ Files will remain encrypted if the phrase is incorrect

🔑 Authentication Details

Secret Phrase: coffee

Used as a basic authentication mechanism before decryption

Demonstrates access control in encryption systems

🛡️ Security & Best Practices

Encryption key file is never pushed to GitHub

.gitignore is used to exclude sensitive runtime files

Designed to run only inside a controlled test directory

No system or OS files are modified

🧪 Concepts Covered

File-level encryption and decryption

Symmetric cryptography (Fernet)

Key generation and management

Authentication logic

Linux file handling

Git & GitHub version control

⚠️ Disclaimer

This project is intended only for educational and academic use.
Do not use this project on real user data or production systems.
The author is not responsible for misuse of this code.

✅ Conclusion

This project provides hands-on experience with encryption concepts, secure coding practices, and Linux-based execution.
It also demonstrates professional documentation and version control practices using Git and GitHub.
