# Shell-Scripts

Simple Password Generator

Overview

This is a simple password generator script written in Bash. It generates random passwords using the OpenSSL tool, which are suitable for securing accounts, services, or any other scenario where a strong password is needed. The script allows you to specify the length of the password, and it will generate five passwords of that specified length.

Prerequisites

Bash: This script runs in a Bash shell, which is available on most Unix-like operating systems, including Linux and macOS.
OpenSSL: The script uses OpenSSL to generate random data. OpenSSL should be installed on your system. You can verify its presence by running openssl version in the terminal.

Usage

Clone or Download the Script: Save the script to your local machine.

Make the Script Executable:

bash

chmod +x password_generator.sh
Run the Script:

bash

./password_generator.sh

Input the Desired Password Length: When prompted, enter the length of the password you need. The script will then generate five random passwords of that length.

Example Output

This is a simple password generator

Please enter the length of the password:
12
V0dTqD9k3FzY
P4bLtQxvNyHg
7lKdGpCxMrJ8
2JhFkZnR5TbL
D3fLtVb8RkHs

Notes

Password Length: The length you input will determine how long each generated password will be.
Number of Passwords: The script generates five passwords each time it is run.
Security: The passwords are generated using a base64 encoding of random bytes, which is then truncated to the desired length. This method ensures that the passwords are fairly secure.