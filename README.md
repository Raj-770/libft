# libft

## Introduction

This project is an integral part of the 42 School curriculum, designed to deepen your understanding of the C programming language by creating a custom library of functions. The goal is to implement a set of standard C library functions, prefixed with "ft_", and to further enhance your library with bonus functions focused on linked list manipulation.

## Key Functions

### Mandatory Part

1. **ft_isalpha**
   - Checks if a character is an alphabetic character.

2. **ft_isdigit**
   - Checks if a character is a digit (0-9).

3. **ft_isalnum**
   - Checks if a character is alphanumeric.

4. **ft_isascii**
   - Checks if a character is within the ASCII character set.

5. **ft_isprint**
   - Checks if a character is printable (including space).

6. **ft_strlen**
   - Calculates the length of a string.

7. **ft_memset**
   - Fills a block of memory with a specified value.

8. **ft_bzero**
   - Sets the first n bytes of the memory area pointed to by s to zero.

9. **ft_memcpy**
   - Copies n bytes from memory area src to memory area dest.

10. **ft_memmove**
    - Copies n bytes from src to dest, handling overlapping memory.

11. **ft_strlcpy**
    - Copies up to size - 1 characters from the NUL-terminated string src to dest.

12. **ft_strlcat**
    - Appends the NUL-terminated string src to the end of dest.

13. **ft_toupper**
    - Converts a lowercase letter to uppercase.

14. **ft_tolower**
    - Converts an uppercase letter to lowercase.

15. **ft_strchr**
    - Locates the first occurrence of a character in a string.

16. **ft_strrchr**
    - Locates the last occurrence of a character in a string.

17. **ft_strncmp**
    - Compares the first n characters of two strings.

18. **ft_memchr**
    - Locates the first occurrence of c in the first n bytes of the string pointed to by s.

19. **ft_memcmp**
    - Compares two memory blocks.

20. **ft_strnstr**
    - Locates a substring in a string.

21. **ft_atoi**
    - Converts a string to an integer.

22. **ft_calloc**
    - Allocates memory for an array of nmemb elements of size bytes each and initializes the memory to zero.

23. **ft_strdup**
    - Allocates sufficient memory for a copy of the string, does the copy, and returns a pointer to it.

### Bonus Part (Linked List Functions)

24. **ft_lstnew**
    - Allocates and returns a new element with the given content.

25. **ft_lstadd_front**
    - Adds the element ’new’ at the beginning of the list.

26. **ft_lstsize**
    - Counts the number of elements in a list.

27. **ft_lstlast**
    - Returns the last element of the list.

28. **ft_lstadd_back**
    - Adds the element ’new’ at the end of the list.

29. **ft_lstdelone**
    - Takes as a parameter an element and frees the memory of the element’s content using the function ’del’ given as a parameter and free the element.

30. **ft_lstclear**
    - Deletes and frees the given element and every successor of that element, using the function ’del’ and free.

31. **ft_lstiter**
    - Iterates the list ’lst’ and applies the function ’f’ to the content of each element.

32. **ft_lstmap**
    - Iterates the list ’lst’ and applies the function ’f’ to the content of each element. Creates a new list resulting from the successive applications of ’f’.

## How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/libft.git
   ```

2. Navigate to the project folder:

   ```bash
   cd libft
   ```

3. Compile the library:

   ```bash
   make
   ```

   This will generate the `libft.a` library.

4. Use the library in your C projects:

   - Copy the `libft.a` file to your project folder.
   - Include the `libft.h` header file in your C files.
   - Compile your project with the library:

     ```bash
     gcc -Wall -Wextra -Werror -o your_program your_file.c libft.a
     ```

5. Clean up:

   ```bash
   make clean
   ```

   This removes object files.

6. If you want to remove the library and object files:

   ```bash
   make fclean
   ```

## Bonus Part (If Applicable)

To include the bonus functions in the library, use:

```bash
make bonus
```

Ensure that the mandatory part is perfect before attempting the bonus part.

**Note:** The bonus part will only be assessed if the mandatory part is completed without any issues.

## Additional Notes

- It is recommended to create test programs to validate your functions, even though they are not required for submission.
- Submit your work to your assigned git repository. Only the work in the git repository will be graded.

Feel free to explore and expand your library throughout the year, and good luck with your future C programming assignments!
