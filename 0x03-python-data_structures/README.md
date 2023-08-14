#0x03. Python - Data Structures: Lists, Tuples (Name)
#0x03-python-data_structures (repo)
#files and descriptions

#README >> Carry all desxription on what to do in this project
#Lists.h >> prototypes and header file

#Mendatory task files and descriptions
#file0 >> 0-print_list_integer.py
0. Print a list of integers
Write a function that prints all integers of a list.
#file1 >> 1-element_at.py
1. Secure access to an element in a list
Write a function that retrieves an element from a list like in C.
#file2 >> 2-replace_in_list.py
2. Replace element
Write a function that replaces an element of a list at a specific position (like in C).
#file3 >> 3-print_reversed_list_integer.py
3. Print a list of integers... in reverse!
Write a function that prints all integers of a list, in reverse order.
#file4 >> 4-new_in_list.py
4. Replace in a copy
Write a function that replaces an element in a list at a specific position without modifying the original list (like in C).
#file5 >> 5-no_c.py
5. Can you C me now?
Write a function that removes all characters c and C from a string.
#file6 >> 6-print_matrix_integer.py
6. Lists of lists = Matrix
Write a function that prints a matrix of integers.
#file7 >> 7-add_tuple.py
7. Tuples addition
Write a function that adds 2 tuples.
#file8 >> 8-multiple_returns.py
8. More returns!
Write a function that returns a tuple with the length of a string and its first character.
#file9 >> 9-max_integer.py
9. Find the max
Write a function that finds the biggest integer of a list.
#file10 >> 10-divisible_by_2.py
10. Only by 2
Write a function that finds all multiples of 2 in a lis
#file11 >> 11-delete_at.py
11. Delete at
Write a function that deletes the item at a specific position in a list.
#file12 >> 12-switch.py
12. Switch
Complete the source code in order to switch value of a and b
#file 13 >> 13-is_palindrome.c
13. Linked list palindrome
Write a function in C that checks if a singly linked list is a palindrome.

#Advanced/optional tasks
#file14 >> 100-print_python_list_info.c
14. CPython #0: Python lists
#advanced
CPython is the reference implementation of the Python programming language. Written in C, CPython is the default and most widely used implementation of the language.
Since we now know a bit of C, we can look at what is happening under the hood of Python. Let’s have fun with Python and C, and let’s look at what makes Python so easy to use.
Create a C function that prints some basic info about Python lists.

Prototype: void print_python_list_info(PyObject *p);
Format: see example
Python version: 3.4
Your shared library will be compiled with this command line: gcc -Wall -Werror -Wextra -pedantic -std=c99 -shared -Wl,-soname,PyList -o libPyList.so -fPIC -I/usr/include/python3.4 100-print_python_list_info.c
OS: Ubuntu 14.04 LTS
Start by reading:
listobject.h
object.h
Common Object Structures
List Objects
