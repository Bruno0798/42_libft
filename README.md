<h1 align="center">
	42cursus' libft
</h1>

<p align="center">
	<b><i>Development repo for 42cursus' libft project</i></b><br>
</p>

<p align="center">
	<img alt="GitHub code size in bytes" src="https://img.shields.io/github/languages/code-size/bruno0798/42_libft?color=blueviolet" />
	<img alt="Number of lines of code" src="https://img.shields.io/tokei/lines/github/bruno0798/42_libft?color=blueviolet" />
	<img alt="Code language count" src="https://img.shields.io/github/languages/count/bruno0798/42_libft?color=blue" />
	<img alt="GitHub top language" src="https://img.shields.io/github/languages/top/bruno0798/42_libft?color=blue" />
	<img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/bruno0798/42_libft?color=brightgreen" />
</p>

---

## 🗣️ About

> _This project is about coding a C library.<br>
It will contain a lot of general purpose functions your programs will rely upon._

> Disclaimer: *42 makes us do this just so we can have a deeper understanding of data structures 
and basic algorithms. At 42, certain standard libraries are prohibited in our projects, compelling us to continually expand our custom library with self-built functions as we advance in the program.*

> ⚠️ **Warning**: Don't copy/paste code you don't understand: it's bad for you, and for the school.

### Functions


* [`ft_isalpha`](42_libft/ft_isalpha.c)			- alphabetic character test.
* [`ft_isdigit`](42_libft/ft_isdigit.c)			- decimal-digit character test.
* [`ft_isalnum`](42_libft/ft_isalnum.c)			- alphanumeric character test.
* [`ft_isascii`](42_libft/ft_isascii.c)			- test for ASCII character.
* [`ft_isprint`](42_libft/ft_isprint.c)			- printing character test (space character inclusive).
* [`ft_strlen`](42_libft/ft_strlen.c)				- find length of string.
* [`ft_memset`](42_libft/ft_memset.c)		- write a byte to a byte string.
* [`ft_bzero`](42_libft/ft_bzero.c)		- write zeroes to a byte string.
* [`ft_memcpy`](42_libft/ft_memcpy.c)		- copy memory area.
* [`ft_memmove`](42_libft/ft_memmove.c)	- copy byte string.
* [`ft_strlcpy`](42_libft/ft_strlcpy.c)			- size-bounded string copying.
* [`ft_strlcat`](42_libft/ft_strlcat.c)			- size-bounded string concatenation.
* [`ft_toupper`](42_libft/ft_toupper.c)			- lower case to upper case letter conversion.
* [`ft_tolower`](42_libft/ft_tolower.c)			- upper case to lower case letter conversion.
* [`ft_strchr`](42_libft/ft_strchr.c)				- locate character in string (first occurrence).
* [`ft_strrchr`](42_libft/ft_strrchr.c)			- locate character in string (last occurence).
* [`ft_strncmp`](42_libft/ft_strncmp.c) 			- compare strings (size-bounded).
* [`ft_memchr`](42_libft/ft_memchr.c)		- locate byte in byte string.
* [`ft_memcmp`](42_libft/ft_memcmp.c)		- compare byte string.
* [`ft_strnstr`](42_libft/ft_strnstr.c)			- locate a substring in a string (size-bounded).
* [`ft_atoi`](42_libft/ft_atoi.c)		- convert ASCII string to integer.
* [`ft_calloc`](42_libft/ft_calloc.c)	- memory allocation.
* [`ft_strdup`](42_libft/ft_strdup.c)				- save a copy of a string (with malloc).
* [`ft_substr`](42_libft/ft_substr.c)				- extract substring from string.
* [`ft_strjoin`](42_libft/ft_strjoin.c)			- concatenate two strings into a new string (with malloc).
* [`ft_strtrim`](42_libft/ft_strtrim.c)			- trim beginning and end of string with the specified characters.
* [`ft_split`](42_libft/ft_split.c)				- split string, with specified character as delimiter, into an array of strings.
* [`ft_itoa`](42_libft/ft_itoa.c)					- convert integer to ASCII string.
* [`ft_strmapi`](42_libft/ft_strmapi.c)			- create new string from modifying string with specified function.
* [`ft_striteri`](42_libft/ft_striteri.c)			- applies a provided function to each character in a string.
* [`ft_putchar_fd`](42_libft/ft_putchar_fd.c)		- output a character to given file.
* [`ft_putstr_fd`](42_libft/ft_putstr_fd.c)		- output string to given file.
* [`ft_putendl`](42_libft/ft_putendl.c) 	- output string to stdout with newline.
* [`ft_putnbr_fd`](42_libft/ft_putnbr_fd.c)		- output integer to given file.


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
At 42 School, aligning to the [42 Norms](https://github.com/Bruno0798/42_libft/en_norm.pdf), the school's coding standard, is a fundamental expectation for all projects.