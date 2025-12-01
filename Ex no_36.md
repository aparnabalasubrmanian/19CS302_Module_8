
# Task - Hackerrank Problem

This challenge requires you to print Hello Saveetha! on a single line, and then print the already provided input string to stdout. If you are not familiar with C, you may want to read about the printf() command.

# Example:

Saveetha

The required output is: Hello, Saveetha! C Programming

# AIM:
To write a C program to print the given string.
# ALGORITHM:
1. Start.
2. Define a variables.
3. Write a program to print the given string.
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End.
# PROGRAM:
```
/*
Developed by: Aparna RB
RegisterNumber:  212222220005
*/
#include <stdio.h>

int main()
{
    char s[100];

    fgets(s, sizeof(s), stdin);

    printf("Hello, Saveetha!\n");
    printf("%s", s);

    return 0;
}

```
# OUTPUT:
![image](https://github.com/user-attachments/assets/271a45d4-a6ba-43c0-a45e-b529ef0e63e0)

# RESULT:
Thus, the program is executed and verified successfully.
