Linux basics
---------------

# Introduction

TODO:

# Command line

The main tool to handle Linux is the command line. It enables you to view files and directories, install and run programs, access the internet and do everything that you could do with the graphical interface like in Windows.

Terminal makes it easy to automate certain tasks. After some practice, it turns out that you are able to do many things faster with the command line than you would do with the graphical interface.

The linux command line has a bunch of built-in commands (mini programs) and a simple shell scripting language (typically bash (Bourne again shell) or sh (shell)).

## The main commands to handle a Linux system

A few basic commands:

* ls (list the directory content)
* cd directory (change directory)
* cp location/file new_location/new_file (copy)
* mv location/file new_location/new_file (move)
* mkdir directory (make directory - create directory)
* touch filename (create an empty file or update an existing one without any content changes)
* rm filename (remove file) (rm -rf directory removes a directory with its content)
* ./path/program (execute a program)
* history (show commands history)
* cat filename (shows file content)
* echo text (print text)
* stream1 > stream2 (redirect stream/move a file to another one)
* {nano/pico/vi/vim} file (open file in the selected text editor and edit)
* help (get other commands)
* man command (get more info about a command)
* cd .. (move one level up in the directory tree) **todo: explain directory tree, image**

Additionally (for Ubuntu):
* sudo apt install program (install a program from the main repository)

## Task

1. Go to the home directory (~/), create a directory named `first_dir` which contains 3 files `first_file`, `second_file`, `third_file`. Each of the files contains it's name as the content. 
2. Save `ls -la` command output to file `first_ls`.
3. remove file `second_file`
4. Save `ls-la` command output to file `second_ls`
5. copy `third_file` to `fourth_file`
6. Save `ls -la` command output to file `third_ls`
7. move `first_file` to `second_file`
8. Save `ls -la` command output to file `fourth_ls

