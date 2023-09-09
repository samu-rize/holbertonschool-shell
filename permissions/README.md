# Holberton School Shell Permissions

Welcome to the "Shell Permissions" project! The scripts in this directory were completed as part of the Shell Permissions curriculum at Holberton School.

![Permission GIF](https://media.giphy.com/media/765ccrAiB0g9z6EApL/giphy.gif)

## Table of Contents

1. [Scripts](#scripts)
2. [Learning Objectives](#learning-objectives)
3. [Requirements](#requirements)

---

## Scripts

#### [0-switch_user](0-switch_user)
  - This script switches the current user to the user 'betty' in exactly 8 characters.

#### [1-who_am_i](1-who_am_i)
  - This script prints the effective username of the current user.

#### [2-groups](2-groups)
  - This script prints all the groups the current user is part of.

#### [3-new_owner](3-new_owner)
  - This script changes the owner of the file 'hello' to the user 'betty'.

#### [4-empty_file](4-empty_file)
  - This script creates an empty file called 'hello'.

#### [5-execute_permission](5-execute_permission)
  - This script adds execute permission to the owner of the file 'hello'.

#### [6-multiple_permissions](6-multiple_permissions)
  - This script adds execute permission to the owner and the group owner, and read permission to other users, to the file 'hello'.

#### [7-everybody_permissions](7-everybody_permissions)
  - This script adds execution permission to the owner, the group owner, and other users to the file 'hello'.

#### [8-james_bond_permissions](8-james_bond_permissions)
  - This script sets the permission to the file 'hello' as follows: Owner has no permission, Group has no permission, Other users have all the permissions.

#### [9-john_doe_permissions](9-john_doe_permissions)
  - This script sets the mode of the file 'hello' to [MODE].
```bash
-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello.
```
#### [10-mirror_permissions](10-mirror_permissions)
  - This script sets the mode of the file 'hello' the same as 'olleh's mode'.

#### [11-add_execute_to_directories](11-add_execute_to_directories)
  - This script adds execute permission to all subdirectories of the current directory for the owner, the group owner, and all other users. Regular files should not be changed.

#### [13-change_group_owner](13-change_group_owner)
  - This script changes the group owner to 'school' for the file 'hello'.

#### [14-change_owner_and_group](14-change_owner_and_group)
  - This script changes the owner to 'vincent' and the group owner to 'staff' for all the files and directories in the working directory.

#### [15-symbolic_links](15-symbolic_links)
  - This script changes the owner and the group owner of '_hello' to 'vincent' and 'staff' respectively. The file '_hello' is a symbolic link.

#### [16-change_owner_if_owned_by](16-change_owner_if_owned_by)
  - This script changes the owner of the file 'hello' to 'vincent' only if it is owned by the user 'guillaume'.

---

## Learning Objectives

By the end of this project, you will:

- Understand Linux file permissions.
- Know how to represent each of the three sets of permissions (owner, group, and other) as a single digit.
- Be able to change permissions, owner, and group of a file.
- Understand why a normal user can't chown a file.
- Know how to run a command with root privileges.
- Understand how to change user ID or become superuser.

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