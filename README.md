# 0x11. C - printf
> ALX Software Engineering, Group Project on C programming. Project to be done in teams of 2 people (your team: Kebron araya, Godswill Ubah). The project will start Mar 24, 2023 6:00 AM, must end by Mar 29, 2023 7:00 AM. An auto review will be launched at the deadline




![Example screenshot](./img/printf.png)





## Table of contents
* [Concepts](#concepts)
* [Requirements](#requirements)
* [Compilation](#compilation)
* [Code Example](#code_example)
* [Tasks](#tasks)
* [Status](#status)
* [Contact](#contact)


## Concepts
For this project, we expect you to look at these concepts:

* Printf function in C
    * Prints a string to the standard output according to a given format.
    * The \_printf() is a variadic function that accepts arguments and replaces the tags written in the strings.
    * If the program runs successfully, the return value is the amount of chars printed or -1 otherwise.
* Group Projects
* Pair Programming
* Flowcharts
* Technical Writing


## Reqirements

### General

* Allowed editors: ```vi```, ```vim```, ```emacs```
* All your files will be compiled on Ubuntu 20.04 LTS using ```gcc```, using the options ```-Wall -Werror -Wextra -pedantic -std=gnu89```
* All your files should end with a new line
* A ```README.md``` file, at the root of the folder of the project is mandatory
* Your code should use the ```Betty style```. It will be checked using ```betty-style.pl``` and ```betty-doc.pl```
* You are not allowed to use global variables
* No more than 5 functions per file
* In the following examples, the ```main.c``` files are shown as examples. You can use them to test your functions, but you don’t have to push them to your repo (if you do we won’t take them into account). We will use our own ```main.c``` files at compilation. Our ```main.c``` files might be different from the one shown in the examples
* The prototypes of all your functions should be included in your header file called ```main.h```
* Don’t forget to push your header file
* All your header files should be include guarded
* Note that we will not provide the ```_putchar``` function for this project

### Github
**There should be one project repository per group. The other members do not fork or clone the project to ensure only one of the team has the repository in their github account otherwise you risk scoring 0%**


## Compilation
* Your code will be compiled this way:
```bash
$ gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c
```
* As a consequence, be careful not to push any c file containing a ```main``` function in the root directory of your project (you could have a ```test``` folder containing all your tests files including ```main``` functions)
* Our main files will include your main header file (```main.h```): ```#include main.h```
* You might want to look at the gcc flag ```-Wno-format``` when testing with your ```_printf``` and the standard ```printf```
* We strongly encourage you to work all together on a set of tests
* If the task does not specify what to do with an edge case, do the same as ```printf```


## Code_Example
Print the string of characters in "Hello World":

**Input:** 
```c
\_printf("Hello World!");
```
**Output:**
```c
 Hello World!
```


## Tasks

### 0. I'm not going anywhere. You can print that wherever you want to. I'm here and I'm a Spur for life 
>Write a function that produces output according to a format.

* Prototype: int _printf(const char *format, ...);
* Returns: the number of characters printed (excluding the null byte used to end output to strings)
* write output to stdout, the standard output stream
* format is a character string. The format string is composed of zero or more directives. See man 3 printf for more detail. You need to handle the following conversion specifiers: ```c``` ```s``` ```%```
* You don’t have to reproduce the buffer handling of the C library printf function
* You don’t have to handle the flag characters
* You don’t have to handle field width
* You don’t have to handle precision
* You don’t have to handle the length modifiers

**Solution:** 

### 1. Education is when you read the fine print. Experience is what you get if you don't
>Handle the following conversion specifiers:

* ```d```
* ```i```
* You don’t have to handle the flag characters
* You don’t have to handle field width
* You don’t have to handle precision
* You don’t have to handle the length modifiers

**Solution:** 


## Status
The project is **finished**


## Contributors
**Created** **by** [kbtisuu](https://github.com/kbtisuu) **and**  [supersudouser](https://github.com/supersudouser)


