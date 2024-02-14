# Lexical-Analyzer
# Introduction
This program is a simple lexical analyzer written in C. It is designed to tokenize a given string of characters and categorize them into various tokens, such as identifiers, numeric values, and specific symbols (like arithmetic operators and parentheses). The program is built to recognize a basic set of reserved words and symbols commonly used in programming languages.

# Features
Tokenization: Splits a string into recognizable tokens.
Reserved Words Identification: Recognizes a set of predefined reserved words.
Numeric Value Recognition: Identifies and processes numeric values.
Symbol Recognition: Handles various symbols like arithmetic operators and parentheses.
Error Handling: Provides basic error handling for unrecognized inputs.

# How to Use
Compile the Program: Use a C compiler to compile the source code.


# Program Structure
Main Function: Handles the input and orchestrates the tokenizing process.
letter Function: Checks if a character is a letter.
digit Function: Checks if a character is a digit.
Tokenization Logic: Located in the main function, it processes the input string and identifies tokens.
Error Handling: Provides feedback for unrecognized characters.

# Token Definitions
Reserved Words: "begin", "if", "then", "while", "do", "end"
Symbols: '<', '>', ':', '+', '-', '*', '/', ';', '(', ')'
Numeric Values: Any sequence of digits.

# Limitations
Fixed Token Size: Tokens are limited to 8 characters.
Limited Set of Tokens: Only recognizes a basic set of reserved words and symbols.
Basic Error Handling: Simple error messages without detailed information.

# Dependencies
Standard C library