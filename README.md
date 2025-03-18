# 🐍 Python Programming - Learning Blog

Welcome to my **Python Programming Blog**! 🚀  
This blog is a collection of posts covering Python from the basics to advanced topics, helping both beginners and enthusiasts gain a strong foundation in Python.

## 📌 Table of Contents

### **1️⃣ Basic Syntax and Data Types**
Understanding the fundamental building blocks of Python.

| Topic                         | Description |
|-------------------------------|-------------|
| **1.1 Introduction to Python** | Why Python? Its applications and advantages. |
| **1.2 Installing Python**      | Setting up Python on Windows, macOS, and Linux. |
| **1.3 Writing Your First Python Program** | Running Python scripts and interactive shell usage. |
| **1.4 Variables in Python**    | Declaring and using variables. |
| **1.5 Data Types in Python**   | Understanding strings, numbers, lists, tuples, sets, and dictionaries. |
| **1.6 Type Conversion**        | Converting between different data types. |
| **1.7 Operators in Python**    | Arithmetic, comparison, logical, assignment, bitwise, and membership operators. |
| **1.8 Comments in Python**     | Writing single-line and multi-line comments. |
| **1.9 Taking User Input**      | Using `input()` function in Python. |
| **1.10 Python’s Print Function** | Formatting and displaying output. |

This section will provide a step-by-step explanation of Python’s fundamental concepts, ensuring a strong foundation for advanced topics.

---
Some Sources used in the Blogs are https://javaconceptoftheday.com/division-operators-in-python/

# 📌 Basic Syntax and Data Types in Python

## 📝 Table of Contents

| **Topic**                   | **Description** |
|-----------------------------|----------------|
| **Variables**               | Storing values in named references. |
| **Variable Naming Rules**    | Rules and best practices for naming variables. |
| **Data Types**              | Understanding different types: integers, floats, strings, lists, tuples, sets, and dictionaries. |
| **Mutable vs Immutable**    | Difference between mutable (lists, dictionaries) and immutable (strings, tuples) objects. |
| **Type Conversion**         | Converting between different data types (`int()`, `float()`, `str()`, `list()`, etc.). |
| **Operators**               | Arithmetic (`+`, `-`, `*`, `/`), Comparison (`==`, `!=`, `>`, `<`), Logical (`and`, `or`, `not`), Bitwise, Assignment, Membership, and Identity operators. |
| **Comments in Python**      | Single-line (`#`) and multi-line (`""" """`) comments. |
| **User Input**              | Taking user input using `input()`. |
| **Print Function**          | Printing output and using format specifiers (`print()`, `f-strings`). |

This table provides a structured overview of **Basic Syntax and Data Types** in Python.

![image](https://github.com/user-attachments/assets/a5963932-4b71-48ac-be92-c6a6e9e46354)
![image](https://github.com/user-attachments/assets/32ebbbae-485d-4664-9104-cf6ae6032885)

![image](https://github.com/user-attachments/assets/b5f376f5-54ad-4bbe-a426-3dd113fd25ce)

Python Data Types
![image](https://github.com/user-attachments/assets/52916b28-931e-491e-89bd-62c8929551d9)

Python Operators
![image](https://github.com/user-attachments/assets/93f47230-3192-4323-9189-3fc3378789d8)

Python Difference between / and // operators
![image](https://github.com/user-attachments/assets/611b9783-427c-45a0-8292-1ba4294df156)


Python Type Conversions
![image](https://github.com/user-attachments/assets/2fa7a246-b97b-4019-9594-d11c851b4e34)

# 📌 Implicit Type Conversion (Automatic)

# Integer to Float
a = 10       # Integer
b = 3.5      # Float
result = a + b  # Python converts 'a' (int) to float automatically
print(result)   # Output: 13.5
print(type(result))  # Output: <class 'float'>

# Integer to Float in Division
x = 5
y = 2.0
z = x / y   # Python automatically converts 'x' to float
print(z)    # Output: 2.5
print(type(z))  # Output: <class 'float'>

# 📌 Explicit Type Conversion (Manual)

# Float to Integer
a = 5.9
b = int(a)   # Explicitly converting float to int
print(b)     # Output: 5 (Decimal part removed)
print(type(b))  # Output: <class 'int'>

# String to Integer
num_str = "100"
num_int = int(num_str)  # Converts string "100" to integer 100
print(num_int + 10)  # Output: 110
print(type(num_int))  # Output: <class 'int'>

# Integer to String
num = 42
num_str = str(num)  # Converts integer to string
print(num_str + " is a number")  # Output: "42 is a number"
print(type(num_str))  # Output: <class 'str'>

# String to Float
str_num = "12.34"
float_num = float(str_num)  # Converts string to float
print(float_num + 1.66)  # Output: 14.0
print(type(float_num))  # Output: <class 'float'>

# List to Tuple
list_data = [1, 2, 3]
tuple_data = tuple(list_data)
print(tuple_data)  # Output: (1, 2, 3)
print(type(tuple_data))  # Output: <class 'tuple'>

# Tuple to List
tuple_data = (4, 5, 6)
list_data = list(tuple_data)
print(list_data)  # Output: [4, 5, 6]
print(type(list_data))  # Output: <class 'list'>

# Set to List
set_data = {7, 8, 9}
list_data = list(set_data)
print(list_data)  # Output: [7, 8, 9]
print(type(list_data))  # Output: <class 'list'>

# Dictionary Keys to List
dict_data = {'a': 1, 'b': 2, 'c': 3}
keys_list = list(dict_data.keys())
print(keys_list)  # Output: ['a', 'b', 'c']
print(type(keys_list))  # Output: <class 'list'>

# Common Mistake: Converting Non-Numeric String to Integer
text = "hello"
# num = int(text)  # ❌ This will raise ValueError


