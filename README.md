             # DSP -  "" DATA SCIENCE WITH PYTHON ""
             
                                                                UNIT-01
                                                                
                                                      PYTHON BASICS FOR DATA SCIENCE
                                                      
 INTRODUCTION TO PYTHON :
 -------------------------
 1) What is Python?
 * Python is a popular programming language. It was created by Guido van Rossum, and released in 1991.

It is used for:
* web development (server-side),
* software development,
* mathematics,
* system scripting.


2) What can Python do?
* Python can be used on a server to create web applications.
* Python can be used alongside software to create workflows.
* Python can connect to database systems. It can also read and modify files.
* Python can be used to handle big data and perform complex mathematics.
* Python can be used for rapid prototyping, or for production-ready software development.

3) Why Python?
* Python works on different platforms (Windows, Mac, Linux, Raspberry Pi, etc).
* Python has a simple syntax similar to the English language.
* python has syntax that allows developers to write programs with fewer lines than some other programming languages.
* Python runs on an interpreter system, meaning that code can be executed as soon as it is written. This means that prototyping can be very quick.
* python can be treated in a procedural way, an object-oriented way or a functional way.

4) Good to know:
* The most recent major version of Python is Python 3, which we shall be using in this tutorial. However, Python 2, although not being updated with anything other than security updates, is still quite popular.
* In this tutorial Python will be written in a text editor. It is possible to write Python in an Integrated Development Environment, such as Thonny, Pycharm, Netbeans or Eclipse which are particularly useful when managing larger collections of Python files.

5) Python Syntax compared to other programming languages:
* Python was designed for readability, and has some similarities to the English language with influence from mathematics.
* Python uses new lines to complete a command, as opposed to other programming languages which often use semicolons or parentheses.
* Python relies on indentation, using whitespace, to define scope; such as the scope of loops, functions and classes. Other programming languages often use curly-brackets for this purpose.

Example:
print("Hello, World!")

TYPES IN PYTHON:
----------------

Built-in Data Types:
* In programming, data type is an important concept.
* Variables can store data of different types, and different types can do different things.

Python has the following data types built-in by default, in these categories:

* Text Type:	str
* Numeric Types:	int, float, complex
* Sequence Types:	list, tuple, range
* Mapping Type:	dict
* Set Types:	set, frozenset
* Boolean Type:	bool
* Binary Types:	bytes, bytearray, memoryview
* None Type:	NoneType
  
Examples:
In Python, the data type is set when you assign a value to a variable:

* x = "Hello World"                                                   	str	
* x = 20                                                              	int	
* x = 20.5                                                             	float	
* x = 1j	                                                              complex	
* x = ["apple", "banana", "cherry"]	                                    list	
* x = ("apple", "banana", "cherry")                                    	tuple	
* x = range(6)	                                                        range	
* x = {"name" : "John", "age" : 36}                                     	dict	
* x = {"apple", "banana", "cherry"}                                    	set	
* x = frozenset({"apple", "banana", "cherry"})                        	frozenset	
* x = True	                                                            bool	
* x = b"Hello"                                                         	bytes	
* x = bytearray(5)                                                    	bytearray	
* x = memoryview(bytes(5))	                                            memoryview	
* x = None                                                            	NoneType


EXPRESSIONS AND VARIABLES:
----------------------------

Variables:
* Variables are containers for storing data values.

Creating Variables:
* Python has no command for declaring a variable.
* A variable is created the moment you first assign a value to it.

Example:
* x = 5
* y ="John"
* print(x)
* print(y)

EXPRESSIONS:
* An expression is a combination of operators and operands that is interpreted to produce some other value.

 We have many different types of expressions in Python.
 1. Constant Expressions: These are the expressions that have constant values only.
Example:
# Constant Expressions
x = 15 + 1.3
print(x)
Output:
16.3

2. Arithmetic Expressions:
* An arithmetic expression is a combination of numeric values, operators, and sometimes parenthesis. The result of this type of expression is also a numeric value. The operators used in these expressions are arithmetic operators like addition, subtraction, etc.
*  Here are some arithmetic operators in Python:
*  Example:
# Arithmetic Expressions
* x = 40
* y = 12
  
* add = x + y
* sub = x - y
* pro = x * y
* div = x / y
  
* print(add)
* print(sub)
* print(pro)
* print(div)
Output:
52
28
480
3.3333333333333335
