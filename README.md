0x11. C - printf

C

Group project

 By: Julien Barbier, co-founder & CEO

 Weight: 5

 Project to be done in teams of 2 people (your team: Mfumu Mabunda, Edidiong Udoh)

 Project over - took place from Oct 14, 2022 6:00 AM to Oct 19, 2022 6:00 AM

 An auto review will be launched at the deadline

In a nutshell…

Contribution: 100.0%

Auto QA review: 0.0/101 mandatory & 0.0/1123 optional

Altogether:  0.0%

Mandatory: 0.0%

Optional: 0.0%

Contribution: 100.0%

Calculation:  100.0% * (0.0% + (0.0% * 0.0%) )  == 0.0%

Challenge #3 has started!

Concepts

For this project, we expect you to look at these concepts:



Group Projects

Pair Programming - How To

Flowcharts

Technical Writing

Background Context

Write your own printf function.







^ In this picture, Kris, and Jul



Resources

Read or watch:



Secrets of printf

Group Projects concept page (Don’t forget to read this)

Flowcharts concept page

man or help:



printf (3)

Requirements

General

Allowed editors: vi, vim, emacs

All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89

All your files should end with a new line

A README.md file, at the root of the folder of the project is mandatory

Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl

You are not allowed to use global variables

No more than 5 functions per file

In the following examples, the main.c files are shown as examples. You can use them to test your functions, but you don’t have to push them to your repo (if you do we won’t take them into account). We will use our own main.c files at compilation. Our main.c files might be different from the one shown in the examples

The prototypes of all your functions should be included in your header file called main.h

Don’t forget to push your header file

All your header files should be include guarded

Note that we will not provide the _putchar function for this project

GitHub

There should be one project repository per group. The other members do not fork or clone the project to ensure only one of the team has the repository in their github account otherwise you risk scoring 0%



More Info

Authorized functions and macros

write (man 2 write)

malloc (man 3 malloc)

free (man 3 free)

va_start (man 3 va_start)

va_end (man 3 va_end)

va_copy (man 3 va_copy)

va_arg (man 3 va_arg)

Compilation

Your code will be compiled this way:

$ gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c

As a consequence, be careful not to push any c file containing a main function in the root directory of your project (you could have a test folder containing all your tests files including main functions)

Our main files will include your main header file (main.h): #include main.h

You might want to look at the gcc flag -Wno-format when testing with your _printf and the standard printf
