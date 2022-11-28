
## Python - Hello, World
In this project the task is knowing the bases of python.

## Learning Objectives

* Why Python programming is awesome
* Who created Python
* Who is Guido van Rossum
* Where does the name ‘Python’ come from
* What is the Zen of Python
* How to use the Python interpreter
* How to print text and variables using print
* How to use strings
* What are indexing and slicing in Python
* What is the official Python coding style
* How to check your code with [pycodestyle] (https://pypi.org/project/pycodestyle/)


## Tasks
# Run Python file

Write a Shell script that runs a Python script.

The Python file name will be saved in the environment variable '$PYFILE'

**Solution:** [0-run]

''' 
$ guillaume@ubuntu:~/py/0x00$ cat main.py 
#!/usr/bin/python3
print("Best School")

$ guillaume@ubuntu:~/py/0x00$ export PYFILE=main.py
$ guillaume@ubuntu:~/py/0x00$ ./0-run
Best School
$ guillaume@ubuntu:~/py/0x00$ 
'''
## Run inline

Write a Shell script that runs Python code.

The Python code will be saved in the environment variable '$PYCODE'

'''
guillaume@ubuntu:~/py/0x00$ export PYCODE='print(f"Best School: {88+10}")'
guillaume@ubuntu:~/py/0x00$ ./1-run_inline 
Best School: 98
guillaume@ubuntu:~/py/0x00$ 
'''


## Hello, print

Write a Python script that prints exactly "Programming is like building a multilingual puzzle, followed by a new line.

'''
Use the function print
guillaume@ubuntu:~/py/0x00$ ./2-print.py 
"Programming is like building a multilingual puzzle
guillaume@ubuntu:~/py/0x00$
'''

## Print integer

Complete this source code in order to print the integer stored in the variable number, followed by Battery street, followed by a new line.

You can find the source code here
The output of the script should be:
the number, followed by Battery street,
followed by a new line
You are not allowed to cast the variable number into a string
Your code must be 3 lines long
You have to use f-strings tips

'''
guillaume@ubuntu:~/py/0x00$ ./3-print_number.py
98 Battery street
guillaume@ubuntu:~/py/0x00$ 
'''

## Print float

Complete the source code in order to print the float stored in the variable number with a precision of 2 digits.

You can find the source code here
The output of the program should be:
Float:, followed by the float with only 2 digits
followed by a new line
You are not allowed to cast number to string
You have to use f-strings

'''
guillaume@ubuntu:~/py/0x00$ ./4-print_float.py
Float: 3.14
guillaume@ubuntu:~/py/0x00$ 
'''
   
## Print string
