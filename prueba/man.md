**PRINTF**                **Linux Programmer's Manual**                         **PRINTF**


**NAME**

_printf - compilation of macros, structures and functions to perform the "printf" function.



**SYNOPSIS**


**#include [<stdio.h>](http://man7.org/linux/man-pages/man3/stdio.3.html)**


**#include [<stdarg.h>](https://linux.die.net/man/3/stdarg)**


**#include "Holberton.h"**


**int _printf**(**const char** *_format, ...);



**DESCRIPTION**


The function **_printf()** prints arguments depending of the


typeof input data provided by the user, whether character,


integer, string, float, among others.


This function is the analogy of the printf function of the


standard library.



**OPTIONS**


A description of the command-line options accepted by a

program and how they change its behavior.


This section should appear only for Section 1 and 8

manual pages.


**EXIT STATUS**


A list of the possible exit status values of a program


and the conditions that cause these values to be


returned.


This section should appear only for Section 1 and 8


manual pages.


**RETURN VALUE**


This function return the characters printed excluding the


null.


**Referenced By**


[printf(3)](https://linux.die.net/man/3/printf); [stdio(3)](http://man7.org/linux/man-page\s/man3/stdio.3.html), [stdarg(3)](https://linux.die.net/man/3/std\arg).

