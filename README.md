# SMNG's BASIC (BLAB And SMAC Intro to Computing) series

### Worksheet for February 12, 2020 and Feb 19, 2020


Skills introduced: 
- Command line basics
	- Navigating through directories
	- Creating, deleting, removing directories and files 
- Github basics
	- Cloning a repository
	- Git add, commit, push

### Presented by Sarah Bakst and Robin Karlin

Before going through this worksheet, you should: 
1. Have a github account
2. Have installed either git bash (if you are on a PC) or know how to open the terminal (mac) 

## COMMAND LINE BASICS
1. Open git bash (PC) or your command line (terminal program, mac)
2. How do you know what directory you're in?  
`pwd`
Print working directory (this is also a Matlab command) 

3. Now you want to switch into a different directory. How do we know what's available to us? 
`ls` lists the contents of the working directory 
Check for a directory inside your current directory 
**Note:** the `#` symbol denotes a "comment", i.e. everything that follows the `#` in the same line is ignored when running commands. So, running 

`ls # comment comment comment` 

...is equivalent to running 

`ls`

4. Okay, now that we know what directories exist, we can move into one! 
`cd DirectoryName` This will take you downward, into a subfolder
`cd ../` This takes you up into a superfolder
`cd ../OtherDirectoryName` This moves you "across", i.e., into the superfolder, and then back down into another folder
