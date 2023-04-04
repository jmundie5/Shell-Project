# Shell-Project


Shell in C
This is a simple shell implemented in C programming language. The shell is able to execute simple commands like ls, cd, pwd, cat, etc., and supports redirection and pipes.

Installation
Clone the repository to your local machine and compile the code using the following command:

**$ git clone https://github.com/jmundie5/Shell-Project.git**
**$ cd repo**
**$ gcc -o main main.c**

Usage
Once you have compiled the code, run the shell by executing the following command:


**$ ./main**

The shell will now be running and you can start entering commands. The shell supports the following features:

Basic commands
The shell supports basic commands like ls, cd, pwd, echo, cat, etc. E

**$ ls**


Redirection
The shell supports output and input redirection using > and < respectively. To redirect the output of a command to a file, use >. To redirect the input of a command from a file, use <.

**$ ls > output.txt**
**$ cat < input.txt**

Pipes

The shell supports pipes using |. To pipe the output of one command to the input of another command, use |.
**$ ls | cat **
