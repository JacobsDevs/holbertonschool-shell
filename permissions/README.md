# Permissions
This is the Shell lesson for Permissions.

## Overview
The following scripts are contained

### 0-iam_betty:
change the current user to betty with **su betty**

### 1-who_am_i:
prints the current user with **whoami**

### 2-groups:
print the groups the current user is part of with **groups**

### 3-new_owner:
change the owner of hello to betty with **chown betty hello**

### 4-empty:
create an empty file called hello with **touch hello**

### 5-execute:
add execute permissions to the owner of hello with **chmod u+x hello**

### 6-multiple_permissions:
add execute permissions to the owner and the group and read permissions to other users for the file hello with **chmod ug+x,o+r hello**

### 7-everybody:
add execute permission to everyone for the file hello with **chmod ugo+x hello**

### 8-James_Bond:
set permissions of file hello to be **Owner:** none, **Group:** none, **Other:** all, with **chmod 007 hello**

### 9-John_Doe:
set permissions of file hello to be **-rwxr-x-wx** with **chmod 753 hello**

### 10-mirror_permissions:
copy permissions from file olleh to file hello with **chmod --reference=olleh hello**

### 11-directories_permissions:
set permissions of all users, groups and other users in all subdirectories to execute without changing the file permissions with **chmod -R +X .**

### 12-directory_permissions:
create directory my_dir and set permissions to 751 with **mkdir -m751 my_dir**

### 13-change_group:
change group owner of file hello to school with **chgrp school hello**

### 14-change_owner_and_group:
change the owner and group of all files and directories in the current directory to vincent & staff respectively with **chown -R vincent:staff .**

### 15-symbolic_link_permissions:
change the owner and group of \_hello to vincent and staff respectively noting that \_hello is a symbolic link with **chown -h vincent\:staff \_hello**

### 16-if_only:
change the owner of the file hello to vincent only if it's currently owned by guillaume with **chown --from=guillaume vincent hello**

## Usage
ll of these scripts can be run with ./ followed by the scripts name. e.g. ./0-iam_betty
