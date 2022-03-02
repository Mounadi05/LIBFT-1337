



>This project aims to code a C library regrouping usual functions that you’ll be allowed to use in all your other projects.

---

### :wrench: :wrench: Mandatory parts [part I] [part II] :

---

<h3 align=center>
Part I :
</h3>

---

</p>
<p align="center">
<img src="https://media3.giphy.com/media/PiQejEf31116URju4V/giphy.gif?cid=790b76118ba41a4e1b4161c3938a263d41c72d85f85788ca&amp;rid=giphy.gif&amp;ct=g" width="500">
</p>

---

> <i>In this first part, you must re-code a set of the libc functions, as defined in their man. Your functions will need to present the same prototype and behaviors as the originals. Your functions’ names must be prefixed by “ft_”. For instance strlen becomes ft_strlen.</i>

<p align=center>

---

| # | Assignement name | Description |
|---|---               |---          |
|   | [LIBFT-1337.h](https://github.com/mounadi05/LIBFT-1337/blob/master/libft.h) |  Contains all prototypes of functions and structures. |

---

| FUNCTION      | Allowed functions | Prototype | Description | Library |
|---		|---                |---        |---          |---      |
| • [isalpha()](https://github.com/mounadi05/LIBFT-1337/blob/master/ft_isalpha.c) | NONE	   | int	ft_isalpha (int	c)     | Checks for an alphabetic character.                   | <ctype.h> |
| • [isdigit()](https://github.com/mounadi05/LIBFT-1337/blob/master/ft_isdigit.c) | NONE	   | int	ft_isdigit (int	c)     | Checks for a digit (0 through 9).                     | <ctype.h> |
| • [isalnum()](https://github.com/mounadi05/LIBFT-1337/blob/master/ft_isalnum.c) | NONE	   | int	ft_isalnum (int	c)     | Checks for an alphanumeric character.                 | <ctype.h> |
| • [isascii()](https://github.com/mounadi05/LIBFT-1337/blob/master/ft_isascii.c) | NONE	   | int	ft_isascii (int c)     | Checks whether c fits into the ASCII character set.   | <ctype.h> |
| • [isprint()](https://github.com/mounadi05/LIBFT-1337/blob/master/ft_isprint.c) | NONE	   | int	ft_isprint (int c)     | Checks for any printable character.                   | <ctype.h> |
| • [strlen()](https://github.com/mounadi05/LIBFT-1337/blob/master/ft_strlen.c)   | NONE	   | size_t 	strlen(const char *s)  | Calculate the length of a string.                     | <string.h> | 
| • [memset()](https://github.com/mounadi05/LIBFT-1337/blob/master/ft_memset.c)   | NONE   	   | void	*ft_memset(void *b, int c, size_t len) | Fill memory with a constant byte. | <string.h> |
| • [bzero()](https://github.com/mounadi05/LIBFT-1337/blob/master/ft_bzero.c)     | NONE	   | void	ft_bzero(void *s, size_t n) | Zero a byte string.                          | <string.h> |
| • [memcpy()](https://github.com/mounadi05/LIBFT-1337/blob/master/ft_memcpy.c)   | NONE	   | void	*ft_memcpy(void *dest, const void *src, size_t n)   | Copy memory area.    | <string.h> | 
| • [memmove()](https://github.com/mounadi05/LIBFT-1337/blob/master/ft_memmove.c) | NONE	   | void	*ft_memmove(void *dst, const void *src, size_t len) | Function copies n bytes from memory area src to memory area dest. | <string.h> |
| • [strlcpy()](https://github.com/mounadi05/LIBFT-1337/blob/master/ft_strlcpy.c) | NONE	   | size_t	ft_strlcpy(char *dst, const char *src, size_t dstlen) |  Copy string to a specific size. | <string.h> |
| • [strlcat()](https://github.com/mounadi05/LIBFT-1337/blob/master/ft_strlcat.c) | NONE	   | size_t	ft_strlcat(char	*dst, const char	*src, size_t	dstsize) | Concatenate string to a specific size. | <string.h> |
| • [toupper()](https://github.com/mounadi05/LIBFT-1337/blob/master/ft_toupper.c) | NONE	   | int	ft_toupper(int c) | Convert chat to uppercase | <ctype.h> |
| • [tolower()](https://github.com/mounadi05/LIBFT-1337/blob/master/ft_tolower.c) | NONE	   | int	ft_tolower(int c) |  Convert char to lowercase. | <ctype.h> |
| • [strchr()](https://github.com/mounadi05/LIBFT-1337/blob/master/ft_strchr.c)   | NONE   	   | char	*ft_strchr(const char *s, int c)  |  Locate character in string (first occurrence). | <string.h> |
| • [strrchr()](https://github.com/mounadi05/LIBFT-1337/blob/master/ft_strrchr.c) | NONE	   | char	*ft_strrchr(const char *s, int c) |  Locate character in string (last occurrence).  | <string.h> |
| • [strncmp()](https://github.com/mounadi05/LIBFT-1337/blob/master/ft_strncmp.c) | NONE	   | int	ft_strncmp(const char *s1, const char *s2, size_t n)  | Compare n bytes of two strings.  | <string.h> |
| • [memchr()](https://github.com/mounadi05/LIBFT-1337/blob/master/ft_memchr.c)   | NONE	   | void	*ft_memchr(const void *s, int c, size_t n) | Scan memory for a character. | <string.h> |
| • [memcmp()](https://github.com/mounadi05/LIBFT-1337/blob/master/ft_memcmp.c)   | NONE	   | int	ft_memcmp(const void *s1, const void *s2, size_t n) | Compare memory areas.  | <string.h> |
| • [strnstr()](https://github.com/mounadi05/LIBFT-1337/blob/master/ft_strnstr.c) | NONE	   | char	*ft_strnstr(const char	*haystack, const char	*needle, size_t	len) | Locate a substring in a string.  | <string.h> |
| • [atoi()](https://github.com/mounadi05/LIBFT-1337/blob/master/ft_atoi.c)       | NONE	   |  int	ft_atoi(const char *s)  |  | <stdlib.h> |

---


|  #  | FUNCTION    | MANUAL |
|---  |---	   |---     |
|     | • [isalpha](https://github.com/mounadi05/LIBFT-1337/blob/master/ft_isalpha.c) | [man](https://www.programiz.com/c-programming/library-function/ctype.h/isalpha)  |
|     | • [isdigit](https://github.com/mounadi05/LIBFT-1337/blob/master/ft_isdigit.c) | [man](https://www.programiz.com/c-programming/library-function/ctype.h/isdigit)  |
|     | • [isalnum](https://github.com/mounadi05/LIBFT-1337/blob/master/ft_isalnum.c) | [man](https://www.programiz.com/c-programming/library-function/ctype.h/isalnum)  |
|     | • [isascii](https://github.com/mounadi05/LIBFT-1337/blob/master/ft_isascii.c) | [man](https://www.ibm.com/docs/en/i/7.3?topic=functions-isascii-test-character-representable-as-ascii-value) |
|     | • [strlen](https://github.com/mounadi05/LIBFT-1337/blob/master/ft_strlen.c)   | [man](http://manpagesfr.free.fr/man/man3/strlen.3.html)     |
|     | • [memset](https://github.com/mounadi05/LIBFT-1337/blob/master/ft_memset.c)   | [man](https://man7.org/linux/man-pages/man3/memset.3.html)  |
|     | • [bzero](https://github.com/mounadi05/LIBFT-1337/blob/master/ft_bzero.c)     | [man](https://man7.org/linux/man-pages/man3/bzero.3.html)   |
|     | • [memcpy](https://github.com/mounadi05/LIBFT-1337/blob/master/ft_memcpy.c)   | [man](https://man7.org/linux/man-pages/man3/memcpy.3.html)  |
|     | • [memmove](https://github.com/mounadi05/LIBFT-1337/blob/master/ft_memmove.c) | [man](https://man7.org/linux/man-pages/man3/memmove.3.html) |
|     | • [strlcpy](https://github.com/mounadi05/LIBFT-1337/blob/master/ft_strlcpy.c) | [man](https://www.cs.auckland.ac.nz/~mjd/prog_contest/www.cppreference.com/c/string/strlcpy) |
|     | • [strlcat](https://github.com/mounadi05/LIBFT-1337/blob/master/ft_strlcpy.c) | [man](https://www.mkssoftware.com/docs/man3/strlcat.3.asp)  |
|     | • [toupper](https://github.com/mounadi05/LIBFT-1337/blob/master/ft_toupper.c) | [man](https://man7.org/linux/man-pages/man3/toupper.3.html) |
|     | • [tolower](https://github.com/mounadi05/LIBFT-1337/blob/master/ft_tolower.c) | [man](https://linux.die.net/man/3/tolower) |
|     | • [strchr](https://github.com/mounadi05/LIBFT-1337/blob/master/ft_strchr.c) | [man](https://man7.org/linux/man-pages/man3/strchr.3.html) |
|     | • [strncmp()](https://github.com/mounadi05/LIBFT-1337/blob/master/ft_strncmp.c) | [man](https://linux.die.net/man/3/strncmp) |
|     | • [memchr()](https://github.com/mounadi05/LIBFT-1337/blob/master/ft_memchr.c) | [man](https://man7.org/linux/man-pages/man3/memchr.3.html) |
|     | • [memcmp()](https://github.com/mounadi05/LIBFT-1337/blob/master/ft_memcmp.c) | [man](https://man7.org/linux/man-pages/man3/memcmp.3.html) |
|     | • [strnstr()](https://github.com/mounadi05/LIBFT-1337/blob/master/ft_strnstr.c) | [man](https://www.freebsd.org/cgi/man.cgi?query=strnstr&sektion=3) |
|     | • [atoi()](https://github.com/mounadi05/LIBFT-1337/blob/master/ft_atoi.c) | [man](https://man7.org/linux/man-pages/man3/atoi.3.html) |

---

</p>

> You must also re-code the following functions, using the function “malloc”:

|  Function    | Allowed function  | Prototype | Description | Manual  |
|---           |---                |---	       |---          |---      |
| •[strdup](https://github.com/mounadi05/LIBFT-1337/blob/master/ft_strdup.c)   |  malloc()         | char	*ft_strdup(const char *s)  | Duplicate a string. |  [man](https://man7.org/linux/man-pages/man3/strdup.3.html) |
| • [calloc](https://github.com/mounadi05/LIBFT-1337/blob/master/ft_calloc.c)   |  malloc()         |    void	*ft_calloc(size_t count, size_t size);   | Allocate memory by filling it with zeros. | [man](https://linux.die.net/man/3/calloc) |

---

### :wrench: :factory: Additional functions :

---

<h3 align=center>
Part II :
</h3>

---

</p>
<p align="center">
<img src="https://c.tenor.com/uYqsM9uIyuYAAAAS/simple-easy.gif" width="500">
</p>

---


> <i>In this second part, you must code a set of functions that are either not included in the libc, or included in a different form. Some of these functions can be useful to write Part 1’s functions.</i>

<p align=center>

| FUNCTION | BEHAVIOR |
|--- |--- |
| - ft_substr | - returns a substring from a string |
| - ft_strjoin.c | - concatenates two strings |
| - ft_strtrim.c | - trims the beginning and end of string with specific set of chars |
| - ft_split.c | - splits a string using a char as parameter |
| - ft_itoa.c | - converts a number into a string |
| - ft_strmapi.c | - applies a function to each character of a string |
| - ft_striteri.c | - applies a function to each character of a string |
| - ft_putchar_fd.c | - output a char to a file descriptor |
| - ft_putstr_fd.c | - output a string to a file descriptor |
| - ft_putendl_fd.c | - output a string to a file descriptor, followed by a new line |
| - ft_putnbr_fd.c | - output a number to a file descriptor |

</p>

---

### :wrench: :white_check_mark: BONUS :

---

<h3 align=center>
</h3>

> <i>The following functions will allow you to easily use your lists.</i>
<p align=center>

| FUNCTION | BEHAVIOR |
|--- |--- |
| - ft_lstnew | - creates a new list element |
| - ft_lstadd_front | - adds an element at the beginning of a list |
| - ft_lstsize | - counts the number of elements in a list |
| - ft_lstlast | - returns the last element of the list |
| - ft_lstadd_back | - adds an element at the end of a list |
| - ft_lstclear | - deletes and free list |
| - ft_lstiter | - applies a function to each element of a list |
| - ft_lstmap | - applies a function to each element of a list |

</p>

---
