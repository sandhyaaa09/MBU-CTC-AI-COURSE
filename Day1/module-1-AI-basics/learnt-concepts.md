Python Basics (Core Concepts)

Python is a high-level interpreted language widely used in AI because it is simple and has many AI libraries.

Python Characteristics:

Easy syntax

Cross-platform

Huge ecosystem (NumPy, TensorFlow, PyTorch)

Great for data processing

Variables:

Variables store data in memory.

Example:

name = "Diya"
age = 21
height = 5.4

Python automatically detects the data type.

Data Types:
Type	      Example       	Description
int	       10	            whole numbers
float	     3.14	          decimal numbers
str	       "hello"        text
bool      	True	          logical value

Example:

x = 10
y = 3.5
name = "AI"
is_student = True

Lists:

Lists store multiple values.

numbers = [10,20,30,40]
print(numbers[0])

Output:

10

Lists are mutable (can change).

Dictionary:

Stores key-value pairs.

student = {
 "name":"Diya",
 "age":21,
 "course":"BCA"
}

print(student["name"])

Output:

Diya

Dictionaries are very important when working with JSON APIs in AI-102.

Functions:

Functions help reuse code.

def greet(name):
    print("Hello", name)

greet("Diya")

Output:

Hello Diya
