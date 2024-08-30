<h1 align=center># 42_FT_PRINTF</h1>
<div align=center>My own custom printf function</div>

# About ✍
Ft_printf is part of 42 Common Core and aims to replicate the functionality of the standard C library function `printf` supporting the conversions "cspdiuxX%". The project provides a learning of new concepts that certainly will be useful for next Common Core activities. The main goal is to deepen your understanding of the inner workings of printf, enhancing your proficiency in C programming.

# Prototype 🖥️
```c
int ft_printf(const char *, ...);
```

# Challenges and Learning Objectives
- Variadic Functions: Dealing with a variable number of arguments.
- String Parsing and Formatting: Parsing format strings and handling various specifiers.

# Conversions
- `%c` -> Prints a single character.
- `%s` -> Prints a string (as defined by the common C convention).
- `%p` -> The void * pointer argument has to be printed in hexadecimal format.
- `%d` -> Prints a decimal (base 10) number.
- `%i` -> Prints an integer in base 10.
- `%u` -> Prints an unsigned decimal (base 10) number.
- `%x` -> Prints a number in hexadecimal (base 16) lowercase format.
- `%X` -> Prints a number in hexadecimal (base 16) uppercase format.
- `%%` -> Prints a percent sign.
