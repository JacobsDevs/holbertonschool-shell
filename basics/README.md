# Basics
This is the Shell lesson for the Basics.

## Overview
The following scripts are contained:

### 0-current_working_directory:
prints the absolute path of the current working directory with **pwd**

### 1-listit:
prints the current directories contents with **ls**

### 2-bring_me_home:
changes the working directory to user home with **cd \~**

### 3-listfiles:
prints the current directories contents in long format with **ls -l**

### 4-listmorefiles:
prints the current directories contents in long format including hidden files with **ls -la**

### 5-listfilesdigitonly:
prints the current directories contents in long format including hidden files with **ls -lan**

### 6-firstdirectory:
creates a directory in /tmp called my_first_directory with **mkdir /tmp/my_first_directory**

### 7-movethatfile:
moves the file betty from /tmp to /tmp/my_first_directory with **mv /tmp/betty /tmp/my_first_directory**

### 8-firstdelete:
deletes the betty file from /tmp/my_first_directory with **rm /tmp/my_first_directory/betty**

### 9-firstdirdeletion:
deletes the directory my_first_directory with **rmdir /tmp/my_first_directory**

### 10-back:
changes the directory to the previous directory with **cd -**

### 11-lists:
prints the content of the current, parent and /boot directories in long format including hidden files with **ls . .. /boot -la**

### 12-file_type:
prints the file type of the file /tmp/iamafile with **file /tmp/iamafile**

### 13-symbolic_link:
creates a symbolic link between /bin/ls and \_\_ls__ with **ln -s /bin/ls \_\_ls__**

### 14-copy_html:
copies all .html files to the parent directory with **cp -n \*.html ..**

### 15-lets_move:
moves all uppercase files to /tmp/u with **mv [[:upper:]]\* /tmp/u**

### 16-clean_emacs:
removes all files creates by Emacs (ending in ~) with <b>rm *~<b>

### 17-tree:
make directories that don't already have parents with **mkdir -p welcome/to/school**

## Usage
All of these scripts can be run with ./ followed by the scripts name.  e.g. ./0-current_working_directory
