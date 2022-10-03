Automatic and dynamic allocation, malloc and free The malloc function is used to allocate a certain amount of memory during the execution of a program. It will request a block of memory from the heap. If the request is granted, the operating system will reserve the requested amount of memory and malloc will return a pointer to the reserved space

Task 0 function that creates an array of chars, and initializes it with a specific char.Prototype: char *create_array(unsigned int size, char c);

Returns NULL if size = 0

Returns a pointer to the array, or NULL if it fails
Task 1 The woman who has no imagination has no wings unction that returns a pointer to a newly allocated space in memory, which contains a copy of the string given as a parameter.



Prototype: char *_strdup(char *str);

The _strdup() function returns a pointer to a new string which is a duplicate of the string str. Memory for the new string is obtained with malloc, and can be freed with free.

Returns NULL if str = NULL

On success, the _strdup function returns a pointer to the duplicated string. It returns NULL if insufficient memory was available
