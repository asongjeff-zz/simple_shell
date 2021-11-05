# SIMPLE SHELL #
Shell is a program that takes the command inputs written from the the user’s keyboard and passes them to the machine to execute them through the kernel. It also verifies if the command inputs from the user are correct.


## OVERVIEW ##
The simple shell project is a collaboration by redit abdisa and Jeffrey ASONGANYI, Software Engineering students at ALX, which contains some of its most basic characteristics, such as : Handling PATHS, implementing BUILT-INS and executing commands.

<<<<<<< HEAD
## Requirements
What is required to implement this project.

### General
* Allowed editors: [vi](), [vim](), [emacs]()
* All files will be compiled on Ubuntu 20.04 LTS using [gcc](), using the options [-Wall -Werror -Wextra -pedantic -std=gnu89]()
* All your files should end with a new line
* A [README.md]() file, at the root of the folder of the project is mandatory
* Code should use the [Betty]() style. It will be checked using [betty-style.pl]() and [betty-doc.pl]()
* Your shell should not have any memory leaks
* No more than 5 functions per file
* All your header files should be include guarded
* Use system calls only when you need to ([why?]())

***

## More Info

### Output
* Unless specified otherwise, your program **must have the exact same output** as [sh]() ([/bin/sh]() as well as the exact same error output.
* The only difference is when you print an error, the name of the program must be equivalent to your [argv[0]]() (See below)

Example of error with [sh]():
```Bash
$ echo "qwerty" | /bin/sh
/bin/sh: 1: qwerty: not found
$ echo "qwerty" | /bin/../bin/sh
/bin/../bin/sh: 1: qwerty: not found
$
```

Same error with your program [hsh]():

```Bash
$ echo "qwerty" | ./hsh
./hsh: 1: qwerty: not found
$ echo "qwerty" | ./././hsh
./././hsh: 1: qwerty: not found
$
```
=======
## DESCRIPTION ##
Simple Shell is a simple program which akes the keyboard commands and delivers them to the system to be executed. This shell is developed in the programming language C.  some built-in commands implement: exit, env, cd.
>>>>>>> ee968e2a1f6eaf3de4a9ae73848f6258cfd3aa2e
