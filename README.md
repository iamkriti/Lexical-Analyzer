# Lexical-Analyzer
# Introduction
This program is a simple lexical analyzer written in C. It is designed to tokenize a given string of characters and categorize them into various tokens, such as identifiers, numeric values, and specific symbols (like arithmetic operators and parentheses). The program is built to recognize a basic set of reserved words and symbols commonly used in programming languages.

# Features
Tokenization: Splits a string into recognizable tokens.<br/>
Reserved Words Identification: Recognizes a set of predefined reserved words.<br/>
Numeric Value Recognition: Identifies and processes numeric values.<br/>
Symbol Recognition: Handles various symbols like arithmetic operators and parentheses.<br/>
Error Handling: Provides basic error handling for unrecognized inputs.<br/>

# How to Use
Compile the Program: Use a C compiler to compile the source code.


# Program Structure
Main Function: Handles the input and orchestrates the tokenizing process.<br/>
letter Function: Checks if a character is a letter.<br/>
digit Function: Checks if a character is a digit.<br/>
Tokenization Logic: Located in the main function, it processes the input string and identifies tokens.<br/>
Error Handling: Provides feedback for unrecognized characters.<br/>

# Token Definitions
Reserved Words: "begin", "if", "then", "while", "do", "end"<br/>
Symbols: '<', '>', ':', '+', '-', '*', '/', ';', '(', ')'<br/>
Numeric Values: Any sequence of digits.<br/>

# Limitations
Fixed Token Size: Tokens are limited to 8 characters.<br/>
Limited Set of Tokens: Only recognizes a basic set of reserved words and symbols.<br/>
Basic Error Handling: Simple error messages without detailed information.<br/>

# Dependencies
Standard C library