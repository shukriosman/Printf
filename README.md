<h1> Printf </h1>

| TaskNo | Name | Explanation | Code |
|--------|--------|--------|--------|
| 0 | _printf.c | Write a function that produces output according to a format.<ul> <li> Prototype: `int _printf(const char *format, ...);`</li>Returns: the number of characters printed (excluding the null byte used to end output to strings)</li><li> write output to stdout, the standard output stream</li><li> `format` is a character string. The format string is composed of zero or more directives. See `man 3 printf` for more detail. You need to handle the following conversion specifiers:<ul><li> `c` </li><li> `s` </li><li> `%` </li>/ul></li><li> You don’t have to reproduce the buffer handling of the C library `printf` function</li><li> You don’t have to handle the flag characters</li><li> You don’t have to handle field width</li><li> You don’t have to handle precision</li><li> You don’t have to handle the length modifiers</li></ul> | <a href = "#"> View Code </a> |
