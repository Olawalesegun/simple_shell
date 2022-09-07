### README FILE ON SHELL PROJECT
```
	1. Segun Olawale
	2. Tionge Mughogho
```

## Here are some of the guidelines that helped us in the execution of this project:

   - Who designed and implemented the original Unix operating system
   - Who wrote the first version of the UNIX shell
   - Who invented the B programming language (the direct predecessor to the C programming language)
   - Who is Ken Thompson
   - How does a shell work
   - What is a pid and a ppid
   - How to manipulate the environment of the current process
   - What is the difference between a function and a system call
   - How to create processes
   - What are the three prototypes of main
   - How does the shell use the PATH to find the programs
   - How to execute another program with the execve system call
   - How to suspend the execution of a process until one of its children terminates
   - What is EOF / “end-of-file”?

   Compilation

## Our shell will be compiled this way:

gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hsh

Testing

At the end of this project our shell should work like this in interactive mode:

$ ./hsh
($) /bin/ls
hsh main.c shell.c
($)
($) exit
$

