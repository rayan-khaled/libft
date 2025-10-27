# Libft - Your First C Library

A foundational **C library** built from scratch.
This project re-implements essential **standard C functions** and introduces you to creating, compiling, and maintaining a **static library (`libft.a`)**.  

You’ll learn the inner workings of the C standard library, memory management, and the fundamentals of writing clean, reusable, and reliable C code.

##  Features

- Custom re-implementation of key **Libc** functions (`strlen`, `memcpy`, `strlcat`, etc.)
- Additional helper functions for:
  - String manipulation  
  - Memory allocation  
  - Character checks  
  - File descriptor output  
- **Linked list utilities** (bonus part)
- Fully functional **Makefile** with required rules (`all`, `clean`, `fclean`, `re`, `bonus`)

## 🧠 Learning Goals

- Deep understanding of **C standard functions**
- Proper **memory management** (malloc, free)
- Writing **modular and reusable code**
- Mastery of the **Makefile** system
- Understanding **static libraries** and linking

## Main Function Categories

### Part 1 — Libc Functions
Re-implementation of functions from `<ctype.h>`, `<string.h>`, and `<stdlib.h>`:
```
isalpha, isdigit, isalnum, isascii, isprint,
strlen, memset, bzero, memcpy, memmove,
strlcpy, strlcat, toupper, tolower, strchr,
strrchr, strncmp, memchr, memcmp, strnstr, atoi,
calloc, strdup
```

### Part 2 — Additional Functions
Helper functions for string manipulation and file descriptor output:
```
ft_substr, ft_strjoin, ft_strtrim, ft_split,
ft_itoa, ft_strmapi, ft_striteri,
ft_putchar_fd, ft_putstr_fd, ft_putendl_fd, ft_putnbr_fd
```

### Bonus Part — Linked Lists
Implemented using the `t_list` structure:
```c
typedef struct s_list
{
    void            *content;
    struct s_list   *next;
} t_list;
```
Functions include:
```
ft_lstnew, ft_lstadd_front, ft_lstsize, ft_lstlast,
ft_lstadd_back, ft_lstdelone, ft_lstclear, ft_lstiter, ft_lstmap
```

## Author
**Rayan Khaled**  
[rayannkhaled@outlook.com] [rayan-khaled]


**Mahdi Chihime**  
📧 [chihimemahdi@gmail.com]  
🏫 42 Student — Libft Project  
🧱 Version: 16.4  
