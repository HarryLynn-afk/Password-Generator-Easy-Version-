# Password Generator (Easy Version)

## Overview
This is a simple password generator written in Python. It allows users to generate a password by selecting the number of letters, symbols, and numbers they want. The program then randomly selects characters from predefined lists to create a secure password.

## Features
- Allows users to specify the number of letters, symbols, and numbers in the password.
- Uses Python's `random.sample()` function to ensure unique selection of characters.
- Provides an easy way to generate a password with a mix of letters, symbols, and numbers.

## Prerequisites
- Python 3.x installed on your system.

## How to Use
1. Run the Python script.
2. Enter the number of letters, symbols, and numbers when prompted.
3. The program will generate and display a randomly generated password based on your input.

## Example Usage
```sh
Welcome to the PyPassword Generator!
How many letters would you like in your password?
5
How many symbols would you like?
2
How many numbers would you like?
3
Generated Password: aXy$P84!
```

## Code Explanation
- The script defines lists of letters (uppercase and lowercase), symbols, and numbers.
- It prompts the user for input regarding the desired composition of the password.
- The `random.sample()` function is used to randomly select characters from each list.
- The selected characters are combined and displayed as the final password.

## Notes
- The password characters are not shuffled in this version; they appear in the order of letters, symbols, and numbers.
- Ensure that the total number of characters requested does not exceed the available options in each category to prevent errors.

## Author
This script was created as a basic password generator for educational purposes.

