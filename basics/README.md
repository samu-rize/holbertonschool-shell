# Holberton School Shell Basics

Welcome to the "Basics" project! This directory scripts completed as part of the shell basics curriculum at Holberton School.

![Television Wizard GIF](https://media.giphy.com/media/5WAdRevloGjuw/giphy.gif)

## Table of Contents

1. [Scripts](#scripts)
2. [Learning Objectives](#learning-objectives)
3. [Requirements](#requirements)

---

## Scripts

### 0-current_working_directory

This script prints the absolute path name of the current working directory.

### 1-listit

Displays the contents list of the current directory.

### 2-bring_me_home

Changes the working directory to the user's home directory.

### 3-listfiles

Displays the current directory contents in long format.

### 4-listmorefiles

Displays the current directory contents, including hidden files, in long format.

### 5-listfilesdigitonly

Displays the current directory contents in long format with user and group IDs displayed numerically, including hidden files.

### 6-firstdirectory

Creates a directory named "my_first_directory" in the /tmp/ directory.

### 7-movethatfile

Moves the file "betty" from /tmp/ to /tmp/my_first_directory.

### 8-firstdelete

Deletes the file "betty" from /tmp/my_first_directory.

### 9-firstdirdeletion

Deletes the directory "my_first_directory" from the /tmp directory.

### 10-back

Changes the working directory to the previous one.

### 11-lists

Lists all files, including hidden ones, in the current directory, parent directory, and /boot directory in long format.

### 12-file_type

Prints the type of the file named "iamafile" located in the /tmp directory.

### 13-symbolic_link

Creates a symbolic link to /bin/ls, named "__ls__," in the current working directory.

### 14-copy_html

Copies all HTML files from the current working directory to the parent directory, preserving newer versions and avoiding overwrites.

### 15-lets_move

Moves files beginning with an uppercase letter to the directory /tmp/u.

### 16-clean_emacs

Deletes all files in the current working directory that end with the character "~."

### 17-tree

Creates the directories "welcome/," "welcome/to/," and "welcome/to/school" in the current directory.

---

## Learning Objectives

Upon completing this project, you should be able to:

- Explain the concept of "RTFM."
- Understand what a Shebang is and its significance in shell scripts.
- Define what the Shell is and distinguish it from a terminal.
- Utilize various shell commands and built-ins like cd, pwd, ls, and more.
- Navigate the filesystem effectively.
- Identify special directories like ".", ".." and "/".
- Work with hidden files and directories.
- Manage symbolic links and hard links.
- Perform file manipulation tasks using commands like cp, mv, rm, and mkdir.
- Use wildcards for pattern matching.
- Access command help using type, which, help, and man.
- Create and understand aliases.
- Read and navigate man pages.
- Master keyboard shortcuts for Bash.

---

## Requirements

- All scripts should be two lines long, ending with a new line.
- Each script must begin with the following line: "#!/bin/bash."
