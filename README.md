# bashScripts  
  
## Assignment Details  
  
### fibonnaci,sh

``` 
Write a shell script called fibonacci which outputs the Fibonacci sequence.

`` 
### fixCprogram

```
Write a script called fixCprogram which looks up every .c file in the current directory for the strings printf or fprintf. If found, the script adds the statement #include <stdio.h> at the beginning of the file but only if it doesn’t already have it included.

```  
  
### getopts.sh

```
Write a shell script called getopts, your script should understand the following command line arguments (options):  -c -d -m -e
where options work as
     -c clear the screen
     -d show list of files in current working directory
     -m show the current date
     -e start the vi editor editing the file name specified after the –e option.
When an invalid option or no option is provided the script should print the usage (information on how to use the command).
 
```  
  
### jean.sh
 
```
Write a script called jean.sh that is difficult to kill: Upon receiving Control-C it will create a copy of itself before dying. The only way to kill phoenix.sh will be by issuing a SIGKILL signal. Please make sure Control-C terminates the original phoenix.sh process.

```  
  
### mode.sh

``` 
Write a Unix shell script named 'mode' that accepts two or more arguments, a file mode, a command and an optional list of parameters and performs the given command with the optional parameters on all files with that given mode.
For example, mode 644 ls -l should perform the command ls -l on all files in the current directory that have mode 644.

```  
  
## phoneNumbers.sh

``` 
1.      Write a shell script called phoneNumber.sh that accepts a 10-digit number as its argument and writes it to the standard output in the form nnn-nnn-nnnn. Perform validation checks to ensure that
a.      a single argument is entered
b.      the number can’t start with 0
c.      the number comprises 10 digits only

```  
  
## printRange.sh

```
Write a shell script called printrange that prints the content of a file from the given line number to the next given line number.
For example:
$ ./printrange 5 7 myfile

```  
  
### tasks.sh
 
``` 
1.      Write a shell script that allows some system-administration tasks to be preformed automatically from a menu-driven interface. Automate the following useful tasks: 
•       Copy directory tree
•       Delete files or directories
•       Output Information
Menu
Should be well designed and displayed on a clean screen.
The menu should display the name of the host machine, the login name of the current user,
and the current date in dd/mm/yyyy form.
 
Copy directory tree
The “Copy directory tree” selection should prompt for two arguments: src & dest.
The script then copies all the files from src, including all the subdirectories, to dest,
creating all the necessary sub-directories.
The script must perform necessary argument validation, assuming that the first argument may be either a directory name or the name of a regular file, while the second may be only a directory name.
 
Delete files or directories
The “Delete files or directories” selection should prompt for a list of files or directories to be deleted. The script asks user for confirmation before deleting a file or a whole directory. The script must perform reasonable argument validation.
 
Output Information
The “Output Information” selection should display; the number of possible users on the system, the number of users logged onto the system, and the number of processes running on the system. This menu produces output similar to the following:
        Number of possible users on the system: 103
        Number of users logged onto the system: 43
        Total number of processes running: 167


``` 
