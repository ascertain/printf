# printf
ALX-SE Programme TEAM WORK [0x11. C - printf]


Hello, welcome to our first group project, we're replicating the printf() fucntion from the C Standard Library.

Introduction to the project

Project _printf() - Produce output to stdout according to a format described below similar to the printf() function.

## Requirements
## General
- Allowed editors: vi, vim, emacs
- All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the - - options -Wall -Werror -Wextra -pedantic -std=gnu89
- All your files should end with a new line
- A README.md file, at the root of the folder of the project is mandatory
- Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl
- You are not allowed to use global variables
- No more than 5 functions per file
- In the following examples, the main.c files are shown as examples. You can use them to test your functions, but you don’t have to push them to your repo (if you do we won’t take them into account). We will use our own main.c files at compilation. Our main.c files might be different from the one shown in the examples
- The prototypes of all your functions should be included in your header file called main.h
- Don’t forget to push your header file
- All your header files should be include guarded
- Note that we will not provide the _putchar function for this project

## GitHub
- There should be one project repository per group. The other members do not fork or clone the project to ensure only one of the team has the repository in their github account otherwise you risk scorin

## Compilation
- Your code will be compiled this way:
```
$ gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c
```

- As a consequence, be careful not to push any c file containing a main function in the root directory of your project (you could have a test folder containing all your tests files including main functions)
- Our main files will include your main header file (main.h): #include main.h
- You might want to look at the gcc flag -Wno-format when testing with your _printf and the standard printf.

## Copyright - Plagiarism
- You are tasked to come up with solutions for the tasks below yourself to meet with the above learning objectives.
- You will not be able to meet the objectives of this or any following project by copying and pasting someone else’s work.
- You are not allowed to publish any content of this project.
- Any form of plagiarism is strictly forbidden and will result in removal from the program.

# Tasks
## 0. I'm not going anywhere. You can print that wherever you want to. I'm here and I'm a Spur for life
    - Write a function that produces output according to a format.
    - Prototype: int _printf(const char *format, ...);
    - Returns: the number of characters printed (excluding the null byte used to end output to strings)
    - write output to stdout, the standard output stream
    - format is a character string. The format string is composed of zero or more directives. See man 3 printf for more detail. You need to handle the following conversion specifiers:
        - c
        - s
        - %
    - You don’t have to reproduce the buffer handling of the C library printf function
    - You don’t have to handle the flag characters
    - You don’t have to handle field width
    - You don’t have to handle precision
    - You don’t have to handle the length modifiers
## 1. Education is when you read the fine print. Experience is what you get if you don't
    - Handle the following conversion specifiers:
        - d
        - i
    - You don’t have to handle the flag characters
    - You don’t have to handle field width
    - You don’t have to handle precision
    - You don’t have to handle the length modifiers


## Repository files

|**File**|**Description**|
|--------|---------------|
|README.md|this file|
|\_putchar.c|putchar function|
|get_function.c|get_function function|
|main.h|header file|
|print_char.c|print_char function|
|print_digit.c|print_digit function|
|print_string.c|print_string function|
|printf.c|main function|
|man_3_printf | man page|
|printf_flowchart.png | flowchart _printf|

## Install
To install execute in terminal
git clone https://github.com/ascertain/printf

## Compilation

``gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c``

## EXAMPLES ##
- _printf functions examples:

- _printf("Character:[%c]\n", 'H');
  + Output: char: [H]
- _printf("String:[%s]\n", "I am a string !");
  + Output: string: [I am a string !]
- _printf("decimal: [%d]\n", 10000);
  + Output: decimal: [10000]
- _printf("Percent: [%%]\n");
  + Output: Percent: [%%]

# Flowchart

![Flowchart]

![image](https://user-images.githubusercontent.com/7894354/233561490-2d76b5cf-22de-49a4-aa58-191bbb08b166.png)



Authors:
Mariem Lamouni: @ascertain

RODGY Kamota : @uncorrectedlie364
