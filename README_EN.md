<p align="center">
  <img src="https://github.com/jotavare/jotavare/blob/main/42/banners/piscine_and_common_core/github_piscine_and_common_core_banner_libft.png">
</p>

<p align="center">
	<img src="https://img.shields.io/badge/status-finished-success?color=%2312bab9&style=flat-square" />
	<img src="https://img.shields.io/badge/evaluated-27%20%2F%2010%20%2F%202024-success?color=%2312bab9&style=flat-square" />
	<img src="https://img.shields.io/badge/score-100%20%2F%20100-success?color=%2312bab9&style=flat-square" />
	<a href='https://www.linkedin.com/in/kerem0zcn' target="_blank"><img alt='Linkedin' src='https://img.shields.io/badge/LinkedIn-100000?style=flat-square&logo=Linkedin&logoColor=white&labelColor=0A66C2&color=0A66C2'/></a>
</p>

## Project Description

The `ft_libft` project aims to reimplement the standard library functions in C. This project focuses on better understanding and creating a customizable version of these library functions.

## File Structure

- `ft_atoi.c`: Converts a string to an integer.
- `ft_bzero.c`: Clears a memory area.
- `ft_calloc.c`: Allocates and clears memory.
- `ft_isalnum.c`: Checks if a character is alphanumeric.
- `ft_isalpha.c`: Checks if a character is alphabetic.
- `ft_isascii.c`: Checks if a character is in the ASCII range.
- `ft_isdigit.c`: Checks if a character is a digit.
- `ft_isprint.c`: Checks if a character is printable.
- `ft_itoa.c`: Converts an integer to a string.
- `ft_memchr.c`: Searches for a character in a memory block.
- `ft_memcmp.c`: Compares two memory blocks.
- `ft_memcpy.c`: Copies a memory block to another location.
- `ft_memmove.c`: Safely moves memory blocks.
- `ft_memset.c`: Fills memory blocks with a specified value.
- `ft_putchar_fd.c`: Writes a character to a specified file descriptor.
- `ft_putendl_fd.c`: Writes a string with a newline to a specified file descriptor.
- `ft_putnbr_fd.c`: Writes an integer to a specified file descriptor.
- `ft_putstr_fd.c`: Writes a string to a specified file descriptor.
- `ft_split.c`: Splits a string using a specified delimiter.
- `ft_strchr.c`: Searches for a character in a string.
- `ft_strdup.c`: Creates a copy of a string.
- `ft_striteri.c`: Applies a function to each character of a string.
- `ft_strjoin.c`: Joins two strings together.
- `ft_strlcat.c`: Appends strings while tracking the total length.
- `ft_strlcpy.c`: Copies a string while tracking the total length.
- `ft_strlen.c`: Returns the length of a string.
- `ft_strmapi.c`: Applies a function to each character of a string and returns a new string.
- `ft_strncmp.c`: Compares two strings up to a specified length.
- `ft_strnstr.c`: Searches for a substring in a string.
- `ft_strrchr.c`: Searches for the last occurrence of a character in a string.
- `ft_strtrim.c`: Trims specified characters from the beginning and end of a string.
- `ft_substr.c`: Creates a substring from a string.
- `ft_tolower.c`: Converts an uppercase character to lowercase.
- `ft_toupper.c`: Converts a lowercase character to uppercase.
- `libft.h`: Contains function prototypes and macro definitions.
- `Makefile`: Script for building the project.

## Usage

### Compilation

To compile the project, use the following command:

```bash
make
```

This command compiles all files and creates a `libft.a` library.

### Example Usage

```c
#include "libft.h"

int main(void)
{
    char str[50] = "Hello World!";
    ft_memset(str, '*', 5);
    printf("%s\n", str);
    return (0);
}
```

This code outputs the following:

```
*****o World!
```

## Function Prototypes

All function prototypes are defined in the `libft.h` header file. Example:

```c
void *ft_memset(void *s, int c, size_t n);
```

### Parameters
- `ft_memset`: Specifies the memory block, fill value, and length.
- `ft_strcpy`: Specifies the source string and destination buffer.
- `ft_strlen`: Specifies the string to calculate the length.

### Return Values
- `ft_memset`: Returns the modified memory block.
- `ft_strcpy`: Returns the copied string.
- `ft_strlen`: Returns the length of the string.

## Contribution

To contribute, please create a "pull request" and share your work. All contributions and feedback are welcome.

