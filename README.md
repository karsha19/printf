# C - printf

This project makes use of all the topics we have learned so far in ALX Low-level programming i.e loops, variables, pointers, function pointers, macros, directives, variadic functions etc.

In this group project, we re-create the C `printf` function.

[![printf.jpg](https://i.postimg.cc/QtBH3tmV/printf.jpg)](https://postimg.cc/S2hyLmwp)

The printf function sends formatted output to stdout.
A custom _printf() for learning purposes was developed by cohort  #8 students Nicks and Musa parsanka.
_printf() function format string is a character string, beginning and ending in its initial shift state, if any. 
These arguments are placed using the percentage '%' operator.

**Write a function that produces output according to a format**.

  * Prototype: `int _printf(const char *format, ...);`
  * Returns: the number of characters printed (excluding the null byte used to end output to strings)
  * write output to stdout, the standard output stream
  * `format` is a character string. The format string is composed of zero or more directives. See `man 3 printf` for more detail. You need to handle the following conversion specifiers:
    * `c`
    * `s`
    * `%`
    * `d`
    * `i`
    * `u`
    * `o`
    * `x`
    * `X`
    * `p`
  * You don’t have to reproduce the buffer handling of the C library printf function
  * You don’t have to handle the flag characters
  * You don’t have to handle field width
  * You don’t have to handle precision
  * You don’t have to handle the length modifiers

* **Handle the following custom conversion specifiers:**
  * `b`: the unsigned int argument is converted to binary
  * `S`: prints the string. Non printable characters (0 < ASCII value < 32 or >= 127) are printed this way: \x, followed by the ASCII code value in hexadecimal (upper case - always 2 characters).
  * `r`: prints the reversed string
  * `R`: prints the rot13'ed string

 * Use a local buffer of 1024 chars in order to call `write` as little as possible.
 
 * **Handle the following flag characters for non-custom conversion specifiers:**
   * `+`
   * space
   * `#`
 
* **Handle the following length modifiers for non-custom conversion specifiers:**
  * `l`
  * `h`
 Conversion specifiers to handle: `d, i, u, o, x, X`

* **Handle the field width for non-custom conversion specifiers.**

* **Handle the precision for non-custom conversion specifiers.**

* **Handle the `0` flag character for non-custom conversion specifiers.**

* Handle the `-` flag character for non-custom conversion specifiers.
 
