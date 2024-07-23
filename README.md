Password Generator
This is a simple command-line Password Generator application written in Python. It allows users to generate a secure, random password of a specified length.

Features
Generate a random password
Supports uppercase and lowercase letters, digits, and special characters
How to Use
Clone the repository:

sh
Copy code
git clone  https://github.com/Shaik-Nihal/CODSOFT_TASK_3.git 
cd password-generator
Run the application:

sh
Copy code
python Codsoft_Task_03.py
Follow the on-screen instructions:

Enter the desired length of the password.
Example
sh
Copy code
Enter the desired length of the password: 12
Generated Password: H$8sD!9tQw4p
Code Overview
Function: generate_password(length)
Generates a random password of the specified length.
Uses a combination of uppercase letters, lowercase letters, digits, and special characters.
Function: main()
Prompts the user for the desired password length.
Calls generate_password to generate the password.
Prints the generated password.
