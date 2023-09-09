# Holberton School Shell, Init Files, Variables, and Expansions

Welcome to the "Shell, Init Files, Variables, and Expansions" project! The scripts in this directory were completed as part of the Shell, Init Files, Variables, and Expansions curriculum at Holberton School.

![Shell GIF](https://media.giphy.com/media/fmkYSBlJt3XjNF6p9c/giphy.gif)

## Table of Contents

1. [Scripts](#scripts)
2. [Learning Objectives](#learning-objectives)
3. [Requirements](#requirements)

---

## Scripts

### 0-alias_ls

This script creates an alias for 'ls' with the value 'rm *'.

### 1-hello_you

This script prints 'hello user,' where 'user' is the current Linux user.

### 2-path_to_success

This script adds '/action' to the PATH, making it the last directory the shell looks into when searching for a program.

### 3-path_beautiful

This script counts the number of directories in the PATH.

### 4-global_variables

This script lists environment variables.

### 5-local_variables

This script lists all local variables, environment variables, and functions.

### 6-create_local_variable

This script creates a new local variable.

### 7-create_global_variable

This script creates a new global variable named 'BEST' with the value 'School.'

### 8-true_knowledge

This script prints the result of adding 128 to the value stored in the environment variable 'TRUEKNOWLEDGE.'

### 9-divide_and_rule

This script prints the result of dividing the value in the environment variable 'POWER' by 'DIVIDE.'

### 10-love_exponent

This script displays the result of 'BREATH' raised to the power of 'LOVE.'

### 11-binary_to_decimal

This script converts a number from base 2 to base 10, with the number in base 2 stored in the environment variable 'BINARY.'

### 12-combinations

This script prints all possible combinations of two lowercase letters, except 'oo,' in alphabetical order.

### 13-floats

This script prints a number with two decimal places, with the number stored in the environment variable 'NUM.'

### 14-decimal_to_hexadecimal

This script converts a number from base 10 to base 16, with the number in base 10 stored in the environment variable 'DECIMAL.'

### 15-ls_command

This script explains step by step what happens when you type 'ls *.c' and hit Enter in your shell, including examples.

### 16-rot13_encoding

This script encodes and decodes text using the rot13 encryption.

### 17-odd_lines

This script prints every other line from the input, starting with the first line.

### 18-base_conversion

This script adds two numbers stored in the environment variables 'WATER' (base 'water') and 'STIR' (base 'stir'), and prints the result in base 'bestchol.'

---

## Learning Objectives

By the end of this project, you will:

- Understand how shell initialization files work.
- Be able to create, update, and delete shell variables.
- Know the roles of important reserved variables like HOME, PATH, and PS1.
- Understand shell expansions and how to use them effectively.
- Perform shell arithmetic operations.
- Create and manage aliases.
- Understand the process of encoding and decoding text using rot13 encryption.

---

## Requirements

- Allowed editors: vi, vim, emacs
- All your scripts will be tested on Ubuntu 20.04 LTS
- All your scripts should be exactly two lines long (`$ wc -l file` should print 2)
- All your files should end with a new line
- The first line of all your files should be exactly `#!/bin/bash`
- A `README.md` file at the root of the project folder describing each script's purpose
- You are not allowed to use `&&`, `||`, or `;`
- You are not allowed to use `bc`, `sed`, or `awk`
- All your files must be executable
