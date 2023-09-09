# Shell, I/O Redirections and Filters - Holberton School

Welcome to the "Shell, I/O Redirections and Filters" project! The scripts in this directory were completed as part of the Shell, I/O Redirections and Filters curriculum at Holberton School.

![hello_world](https://media.giphy.com/media/h408T6Y5GfmXBKW62l/giphy.gif)

## Table of Contents

1. [Scripts](#scripts)
2. [Learning Objectives](#learning-objectives)
3. [Requirements](#requirements)

---

## Scripts

#### [0-hello_world](0-hello_world)

  - This script prints "Hello, World" followed by a new line to the standard output.

#### [1-confused_smiley](1-confused_smiley)

  - This script displays a confused smiley "(Ôo)'.

#### [2-hellofile](2-hellofile)

  - Displays the content of the `/etc/passwd` file.

#### [3-twofiles](3-twofiles)

  - Displays the content of `/etc/passwd` and `/etc/hosts` files.

#### [4-lastlines](4-lastlines)

  - Displays the last 10 lines of the `/etc/passwd` file.

#### [5-firstlines](5-firstlines)

  - Displays the first 10 lines of the `/etc/passwd` file.

#### [6-third_line](6-third_line)

  - Displays the third line of the file `iacta` in the working directory. (You're not allowed to use `sed`)

#### [7-file](7-file)

  - Creates a file named `\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)` containing the text "Best School" ending by a new line.

#### [8-cwd_state](8-cwd_state)

  - Writes the result of the command `ls -la` into the file `ls_cwd_content`. If the file already exists, it should be overwritten; if it doesn't exist, create it.

#### [9-duplicate_last_line](9-duplicate_last_line)

  - Duplicates the last line of the file `iacta` in the working directory.

#### [10-no_more_js](10-no_more_js)

  - Deletes all regular files (not directories) with a `.js` extension in the current directory and its subfolders.

#### [11-directories](11-directories)

  - Counts the number of directories and subdirectories in the current directory, excluding the current and parent directories. Hidden directories should be counted.

#### [12-newest_files](12-newest_files)

  - Displays the 10 newest files in the current directory, one file per line, sorted from newest to oldest.

#### [13-unique](13-unique)

  - Takes a list of words as input and prints only words that appear exactly once. Input and output format should be one line, one word, and words should be sorted.

#### [14-findthatword](14-findthatword)

  - Displays lines containing the pattern "root" from the file `/etc/passwd`.

#### [15-countthatword](15-countthatword)

  - Displays the number of lines containing the pattern "bin" in the file `/etc/passwd`.

#### [16-whatsnext](16-whatsnext)

  - Displays lines containing the pattern "root" and 3 lines after them in the file `/etc/passwd`.

#### [17-hidethisword](17-hidethisword)

  - Displays all lines in the file `/etc/passwd` that do not contain the pattern "bin".

#### [18-letteronly](18-letteronly)

  - Displays all lines of the file `/etc/ssh/sshd_config` starting with a letter, including capital letters.

#### [19-AZ](19-AZ)

  - Replaces all occurrences of characters 'A' and 'c' from input with 'Z' and 'e' respectively.

#### [20-hiago](20-hiago)

  - Removes all occurrences of letters 'c' and 'C' from input.

#### [21-reverse](21-reverse)

  - Reverses its input.

#### [22-users_and_homes](22-users_and_homes)

  - Displays all users and their home directories, sorted by users, based on the `/etc/passwd` file.

#### [23-empty_casks](23-empty_casks)

  - Finds all empty files and directories in the current directory and its subdirectories. Only the names of the files and directories should be displayed, and hidden files should be listed.

#### [24-gifs](24-gifs)

  - Lists all files with a `.gif` extension in the current directory and its subdirectories. Hidden files should be listed, and only regular files (not directories) should be listed. The names of the files should be displayed without their extensions, sorted by byte values in a case-insensitive manner.

#### [25-acrostic](25-acrostic)

  - Decodes acrostics that use the first letter of each line. The decoded message should end with a new line.

#### [26-the_biggest_fan](26-the_biggest_fan)

  - Parses web server logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests. The output should be ordered by the number of requests, with the most active host or IP at the top.

---

## Learning Objectives

By the end of this project, you will:

- Understand shell scripting basics.
- Be proficient in I/O redirections.
- Master common Unix commands and filters.
- Handle special characters effectively in shell scripts.
- Interact with system files such as `/etc/passwd` and `/etc/shadow`.

---

## Requirements

- Allowed editors: vi, vim, emacs
- All your scripts will be tested on Ubuntu 20.04 LTS
- All your scripts should be exactly two lines long (`$ wc -l file` should print 2)
- All your files should end with a new line
- The first line of all your files should be exactly `#!/bin/bash`
- A `README.md` file at the root of the project folder describing each script's purpose
- You are not allowed to use backticks, `&&`, `||`, or `;`
- All your files must be executable
- You are not allowed to use `sed` or `awk`
