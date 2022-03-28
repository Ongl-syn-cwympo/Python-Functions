# Python Functions

# What is a function in Python?

In Python, a function is a block of organized, reusable code with a name that is used to perform a single, specific task. 
Functions help break our program into smaller and modular chunks. This is for better organization of the code, so it's easier to read. This overall
improves efficiency and reduces errors because of the reusability of the code.

# Types of Functions

Python support two types of functions:

- Built-in function
- User-defined function

# Built-in function

The functions which are come along with Python itself are called a built-in function or predefined function. Some of them are: range(), print(), input() ect.

# User-defined function

Functions which are created by programmer explicitly according to the requirement.

# Defining a function

1. def is a keyword that marks the start of the function header.

2. function_name to uniquely identify the function. Function naming follows the same rules of writing identifiers in Python.

3. parameter is the value passed to the function. They are optional.

4. : (colon) to mark the end of the function header.

5. function body is a block of code that performs some task and all the statements in function body must have the same indentation level (usually 4 spaces).

6. """docstring""" documentation string is used to describe what the function does.

7. return is a keyword to return a value from the function.. A return statement with no arguments is the same as return None.

  - Note: While defining a function, we use two keywords, def (mandatory) and return (optional).

# Docstrings

The first string after the function header is called the docstring and is short for documentation string. It is a descriptive text (like a comment) written 
by a programmer to let others know what block of code does.

# Function pass statement

In Python, the pass is the keyword, which won’t do anything. Sometimes there is a situation where we need to define a syntactically empty block. We can 
define that block using the pass keyword. When the interpreter finds a pass statement in the program, it returns no operation.
