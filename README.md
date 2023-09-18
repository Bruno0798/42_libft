<h1 align="center">
	libft
</h1>

<p align="center">
	:information_source: A C static library with recoded standard functions 
</p>
<p align="center"><a href="https://www.42porto.com" target="_blank"><img src="https://img.shields.io/static/v1?label=&message=Porto&color=000&style=for-the-badge&logo=42""></a></p>
<p align="center"><img src="https://github.com/Bruno0798/Bruno0798/blob/main/42-project-badges/badges/ft_printfn.png?raw=true"> </p>
<p align="center"> <strong>100/100</strong> ✅ </p>

<p align="center">
	<img alt="GitHub code size in bytes" src="https://img.shields.io/github/languages/code-size/bruno0798/42_libft?color=blueviolet" />
	<img alt="Code language count" src="https://img.shields.io/github/languages/count/bruno0798/42_libft?color=blue" />
	<img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/bruno0798/42_libft?color=brightgreen" />
</p>

---

## 🗣️ About

This project is about coding a C library.<br>
It will contain a lot of general purpose functions your programs will rely upon.<br>
42 makes us do this just so we can have a deeper understanding of data structures 
and basic algorithms. At 42, certain standard libraries are prohibited in our projects, compelling us to continually expand our custom library with self-built functions as we advance in the program.<br>

> ⚠️ **Warning**: Don't copy/paste code you don't understand: it's bad for you, and for the school.

### Functions

#### Functions from <ctype.h>

* [`ft_isalpha`](src/ft_isalpha.c)		- alphabetic character test.
* [`ft_isdigit`](src/ft_isdigit.c)		- decimal-digit character test.
* [`ft_isalnum`](src/ft_isalnum.c)		- alphanumeric character test.
* [`ft_isascii`](src/ft_isascii.c)		- test for ASCII character.
* [`ft_isprint`](src/ft_isprint.c)		- printing character test (space character inclusive).
* [`ft_toupper`](src/ft_toupper.c)		- lower case to upper case letter conversion.
* [`ft_tolower`](src/ft_tolower.c)		- upper case to lower case letter conversion.

#### Functions from <string.h>

* [`ft_memset`](src/ft_memset.c)		- write a byte to a byte string.
* [`ft_strlen`](src/ft_strlen.c)		- find length of string.
* [`ft_bzero`](src/ft_bzero.c)			- write zeroes to a byte string.
* [`ft_memcpy`](src/ft_memcpy.c)		- copy memory area.
* [`ft_memmove`](src/ft_memmove.c)		- copy byte string.
* [`ft_strlcpy`](src/ft_strlcpy.c)		- size-bounded string copying.
* [`ft_strlcat`](src/ft_strlcat.c)		- size-bounded string concatenation.
* [`ft_strchr`](src/ft_strchr.c)		- locate character in string (first occurrence).
* [`ft_strrchr`](src/ft_strrchr.c)		- locate character in string (last occurence).
* [`ft_strncmp`](src/ft_strncmp.c) 		- compare strings (size-bounded).
* [`ft_memchr`](src/ft_memchr.c)		- locate byte in byte string.
* [`ft_memcmp`](src/ft_memcmp.c)		- compare byte string.
* [`ft_strnstr`](src/ft_strnstr.c)		- locate a substring in a string (size-bounded).
* [`ft_strdup`](src/ft_strdup.c)		- save a copy of a string (with malloc).

#### Functions from <stdlib.h>
  
* [`ft_atoi`](src/ft_atoi.c)			- convert ASCII string to integer.
* [`ft_calloc`](src/ft_calloc.c)		- memory allocation.

#### Non-standard functions

* [`ft_substr`](src/ft_substr.c)				- extract substring from string.
* [`ft_strjoin`](src/ft_strjoin.c)			- concatenate two strings into a new string (with malloc).
* [`ft_strtrim`](src/ft_strtrim.c)			- trim beginning and end of string with the specified characters.
* [`ft_split`](src/ft_split.c)				- split string, with specified character as delimiter, into an array of strings.
* [`ft_itoa`](src/ft_itoa.c)					- convert integer to ASCII string.
* [`ft_strmapi`](src/ft_strmapi.c)			- create new string from modifying string with specified function.
* [`ft_striteri`](src/ft_striteri.c)			- applies a provided function to each character in a string.
* [`ft_putchar_fd`](src/ft_putchar_fd.c)		- output a character to given file.
* [`ft_putstr_fd`](src/ft_putstr_fd.c)		- output string to given file.
* [`ft_putendl`](src/ft_putendl_fd.c)			- output string to stdout with newline.
* [`ft_putnbr_fd`](src/ft_putnbr_fd.c)		- output integer to given file.


#### Note

- Most of the the files and function names are namespaced with an **ft** in front. It stands for Forty Two

## How does libft work?

The objective is to produce a library named libft.a from the source files, enabling its use in future 42 projects as a reusable library.

To create that library, after downloading/cloning this project, **cd** into the project and call make:
```
$ git clone https://github.com/Bruno0798/42_Libft.git
$ cd 42_Libft
$ make
```

You should see a *libft.a* file and some object files (.o).

## MAKEFILE RULES

`make` - Compile libft **mandatory** files.

`make clean` - Delete all .o (object files) files.

`make fclean` - Delete all .o (object file) and .a (executable) files.

`make re` - Use rules `fclean` + `all`.


## NORMINETTE
At 42 School, aligning to the [42 Norms](en_norm.pdf), the school's coding standard, is a fundamental expectation for all projects.
