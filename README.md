# printf
A printf function built by Vanessa Olago and Brian Muriithi.
# Welcome
Rebuild of the standard printf function in C. 
# Format Specifiers
We added %x ,%X, %b, %o, %u, %r, %R, and %p formatting.
# Supported Format Types
TYPE - OUTPUT

c - Single character

s - String

r - String in reverse

R - String in rot13

d - Integer in decimal

i - integer

% - Percent sign

Xl - Lowercase hex

X - Uppercase hex

b - binary

o - octal

u - unsigned

p - pointer

F - expletive
# Examples
Character: printf("%c", A); Output:: A

String: printf("%s", This is a string.); Output: This is a string.

Integer: printf("%i", 5); Output: 5

Expletive: printf("%F", anything); Output: FUCK
# Requirements
Allowed editors: vi, vim, emacs All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89 
All your files should end with a new line A README.md file, at the root of the folder of the project is mandatory Your code should use the Betty style.
 It will be checked using betty-style.pl and betty-doc.pl You are not allowed to use global variables No more than 5 functions per file In the following examples, the main.c files are shown as examples. 
 You can use them to test your functions, but you don’t have to push them to your repo (if you do we won’t take them into account). We will use our own main.c files at compilation. Our main.c files might be different from the one shown in the examples The prototypes of all your functions should be included in your header file called main.h 
 Don’t forget to push your header file All your header files should be include guarded Note that we will not provide the _putchar function for this project GitHub There should be one project repository per group. If you clone/fork/whatever a project repository with the same name before the second deadline, you risk a 0% score.
