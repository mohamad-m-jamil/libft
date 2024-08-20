# libft

**`libft`** is a custom C library created to provide implementations of various standard library functions, additional utilities, and data structures. This project helps understand how these functions work, improves C programming skills, and serves as a useful tool for subsequent projects in the curriculum.

## Table of Contents

- [Introduction](#introduction)
- [Common Instructions](#common-instructions)
- [Mandatory Part](#mandatory-part)
  - [Part 1 - Libc Functions](#part-1---libc-functions)
  - [Part 2 - Additional Functions](#part-2---additional-functions)
- [Bonus Part](#bonus-part)
- [Installation](#installation)
- [Usage](#usage)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)

## Introduction

C programming can be challenging without access to standard functions. The `libft` project is designed to create a custom library of these functions, enabling better control and understanding of their implementation. This library will be valuable for future C assignments and projects.

## Common Instructions

- **Language**: C
- **Norm Compliance**: Ensure all code complies with the project norms. Bonus functions must also adhere to these norms.
- **Memory Management**: Properly manage and free all allocated memory. Memory leaks are not tolerated.
- **Makefile**: Your Makefile should include rules for `NAME`, `all`, `clean`, `fclean`, and `re`. Use `cc` with `-Wall`, `-Wextra`, and `-Werror` flags.
- **Submission**: Include `Makefile`, `libft.h`, and all `ft_*.c` files. Unused files must not be submitted.
- **Testing**: Create and use test programs for validation, though they are not part of the submission.

## Mandatory Part

### Program Name

- `libft.a`

### Files to Submit

- `Makefile`
- `libft.h`
- `ft_*.c`

### Makefile Rules

- `NAME`, `all`, `clean`, `fclean`, `re`

### External Functions

- Detailed in the instructions below

### Libft Authorized Functions

- None

### Description

Implement a collection of functions useful for C programming. The library should replicate standard libc functions and provide additional utility functions.

#### Part 1 - Libc Functions

Implement the following functions with the `ft_` prefix:

- `ft_isalpha()`
- `ft_isdigit()`
- `ft_isalnum()`
- `ft_isascii()`
- `ft_isprint()`
- `ft_strlen()`
- `ft_memset()`
- `ft_bzero()`
- `ft_memcpy()`
- `ft_memmove()`
- `ft_strlcpy()`
- `ft_strlcat()`
- `ft_toupper()`
- `ft_tolower()`
- `ft_strchr()`
- `ft_strrchr()`
- `ft_strncmp()`
- `ft_memchr()`
- `ft_memcmp()`
- `ft_strnstr()`
- `ft_atoi()`

Use `malloc()` for:

- `ft_calloc()`
- `ft_strdup()`

#### Part 2 - Additional Functions

Implement the following functions:

- `ft_substr()`
- `ft_strjoin()`
- `ft_strtrim()`
- `ft_split()`
- `ft_itoa()`
- `ft_strmapi()`
- `ft_striteri()`
- `ft_putchar_fd()`
- `ft_putstr_fd()`
- `ft_putendl_fd()`
- `ft_putnbr_fd()`

## Bonus Part

If the mandatory part is perfect, implement the following functions for manipulating lists:

Add the following structure to `libft.h`:

```c
typedef struct s_list
{
    void *content;
    struct s_list *next;
} t_list;
