0x0B. C - malloc, free C Memory allocation

Tasks 0. Float like a butterfly, sting like a bee mandatory Write a function that creates an array of chars, and initializes it with a specific char.

Prototype: char *create_array(unsigned int size, char c); Returns NULL if size = 0 Returns a pointer to the array, or NULL if it fails

The woman who has no imagination has no wings mandatory Write a function that returns a pointer to a newly allocated space in memory, which contains a copy of the string given as a parameter.
Prototype: char *_strdup(char *str); The _strdup() function returns a pointer to a new string which is a duplicate of the string str. Memory for the new string is obtained with malloc, and can be freed with free. Returns NULL if str = NULL On success, the _strdup function returns a pointer to the duplicated string. It returns NULL if insufficient memory was available FYI: The standard library provides a similar function: strdup. Run man strdup to learn more.

He who is not courageous enough to take risks will accomplish nothing in life mandatory Write a function that concatenates two strings.
Prototype: char *str_concat(char *s1, char *s2); The returned pointer should point to a newly allocated space in memory which contains the contents of s1, followed by the contents of s2, and null terminated if NULL is passed, treat it as an empty string The function should return NULL on failure

If you even dream of beating me you'd better wake up and apologize mandatory Write a function that returns a pointer to a 2 dimensional array of integers.
Prototype: int **alloc_grid(int width, int height); Each element of the grid should be initialized to 0 The function should return NULL on failure If width or height is 0 or negative, return NULL

It's not bragging if you can back it up mandatory Write a function that frees a 2 dimensional grid previously created by your alloc_grid function.
Prototype: void free_grid(int **grid, int height); Note that we will compile with your alloc_grid.c file. Make sure it compiles.

It isn't the mountains ahead to climb that wear you out; it's the pebble in your shoe #advanced Write a function that concatenates all the arguments of your program.
Prototype: char *argstostr(int ac, char **av); Returns NULL if ac == 0 or av == NULL Returns a pointer to a new string, or NULL if it fails Each argument should be followed by a \n in the new string

I will show you how great I am #advanced Write a function that splits a string into words.
Prototype: char **strtow(char *str); The function returns a pointer to an array of strings (words) Each element of this array should contain a single word, null-terminated The last element of the returned array should be NULL Words are separated by spaces Returns NULL if str == NULL or str == "" If your function fails, it should return NULL# alx-low_level_programming 0x00. C - Hello, World. So, today I started C programming language. At the end of this project, I am expected to be able to explain to anyone, without the help of Google: Why C programming is awesome Who invented C Who are Dennis Ritchie, Brian Kernighan and Linus Torvalds What happens when you type gcc main.c What is an entry point What is main How to print text using printf, puts and putchar How to get the size of a specific type using the unary operator sizeof How to compile using gcc What is the default program name when compiling with gcc What is the official C coding style and how to check your code with betty-style How to find the right header to include in your source code when using a standard library function How does the main function influence the return value of the program

