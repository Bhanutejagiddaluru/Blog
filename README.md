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

# 📌 Type Conversion in Python

## 🔹 1️⃣ Implicit Type Conversion (Automatic)
Python automatically converts one data type to another when needed.

| **Example** | **Code** | **Output** |
|------------|---------|------------|
| Integer to Float | `a = 10`  <br> `b = 3.5`  <br> `result = a + b`  <br> `print(type(result))` | `<class 'float'>` |
| Integer to Float (Division) | `x = 5`  <br> `y = 2.0`  <br> `z = x / y`  <br> `print(type(z))` | `<class 'float'>` |

---

## 🔹 2️⃣ Explicit Type Conversion (Manual)
We use built-in functions to manually convert data types.

| **Conversion** | **Code** | **Output** |
|--------------|---------|------------|
| Float to Integer | `a = 5.9`  <br> `b = int(a)`  <br> `print(b, type(b))` | `5 <class 'int'>` |
| String to Integer | `num_str = "100"`  <br> `num_int = int(num_str)`  <br> `print(num_int, type(num_int))` | `100 <class 'int'>` |
| Integer to String | `num = 42`  <br> `num_str = str(num)`  <br> `print(num_str, type(num_str))` | `"42" <class 'str'>` |
| String to Float | `str_num = "12.34"`  <br> `float_num = float(str_num)`  <br> `print(float_num, type(float_num))` | `12.34 <class 'float'>` |

---

## 🔹 3️⃣ Collection Type Conversion
Converting lists, tuples, sets, and dictionaries.

| **Conversion** | **Code** | **Output** |
|--------------|---------|------------|
| List to Tuple | `list_data = [1, 2, 3]`  <br> `tuple_data = tuple(list_data)`  <br> `print(tuple_data, type(tuple_data))` | `(1, 2, 3) <class 'tuple'>` |
| Tuple to List | `tuple_data = (4, 5, 6)`  <br> `list_data = list(tuple_data)`  <br> `print(list_data, type(list_data))` | `[4, 5, 6] <class 'list'>` |
| Set to List | `set_data = {7, 8, 9}`  <br> `list_data = list(set_data)`  <br> `print(list_data, type(list_data))` | `[7, 8, 9] <class 'list'>` |
| Dictionary Keys to List | `dict_data = {'a': 1, 'b': 2, 'c': 3}`  <br> `keys_list = list(dict_data.keys())`  <br> `print(keys_list, type(keys_list))` | `['a', 'b', 'c'] <class 'list'>` |

---

## ❌ Common Mistake: Invalid Type Conversion
🚨 **Trying to convert an invalid string to an integer will cause an error.**
```python
text = "hello"
num = int(text)  # ❌ ValueError: invalid literal for int()
```

# Print Statements
![image](https://github.com/user-attachments/assets/323e5e06-b89f-42e1-9f71-9a25d7dc5a8e)

![image](https://github.com/user-attachments/assets/5f420d2b-14a3-412c-9c55-799dd1893394)

# 📌 Python `print()` Function

The `print()` function in Python is used to display output on the screen. It supports multiple parameters for formatting and customization.


# 🔹 1️⃣ Basic Usage of `print()`

| **Example** | **Code** | **Output** |
|------------|---------|------------|
| Print a String | `print("Hello, World!")` | `Hello, World!` |
| Print Multiple Arguments | `print("Hello", "Python", 2025)` | `Hello Python 2025` |
| Print with Separator | `print("A", "B", "C", sep="-")` | `A-B-C` |
| Print with End Parameter | `print("Hello", end=" ")` <br> `print("World!")` | `Hello World!` |
| Print a Newline Character | `print("Line1\nLine2")` | `Line1` <br> `Line2` |

---

## 🔹 2️⃣ `print()` Function Parameters

| **Parameter** | **Description** | **Example** |
|--------------|----------------|-------------|
| `sep` | Defines a separator between multiple arguments. | `print("Python", "Rocks", sep="🎉")` → `Python🎉Rocks` |
| `end` | Defines what comes at the end instead of a newline. | `print("Hello", end="!")` → `Hello!` |
| `file` | Redirects output to a file. | `print("Hello", file=open("output.txt", "w"))` |
| `flush` | Forces the output to be printed immediately. | `print("Loading...", flush=True)` |

---

# 3️⃣ Advanced Printing Techniques

# Using f"" (Formatted String)
name = "Bhanu"
age = 25
print(f"My name is {name} and I am {age} years old.")
# Output: My name is Bhanu and I am 25 years old.

# Printing Variables Inside Strings (Old Method)
print("My name is {} and I am {} years old.".format(name, age))
# Output: My name is Bhanu and I am 25 years old.

# Printing in Reverse Order
print("Hello"[::-1])  # Output: olleH

# Printing Without a Newline
print("Hello", end=" ")
print("World!")
# Output: Hello World!

# 4️⃣ Printing Special Characters

# Table of Special Characters (as comments)
"""
| Character | Usage            | Example |
|-----------|-----------------|--------------------------------|
| \n       | Newline         | print("Hello\nWorld") → Hello  |
|          |                 |                              |
| \t       | Tab space       | print("Hello\tPython") → Hello    Python |
| \\       | Print backslash | print("C:\\Users\\Bhanu") → C:\Users\Bhanu |
| \'       | Single quote    | print('It\'s Python!') → It's Python! |
| \"       | Double quote    | print("\"Python is great!\"") → "Python is great!" |
"""

# Newline character
print("Hello\nWorld")
# Output:
# Hello
# World

# Tab space
print("Hello\tPython")
# Output: Hello    Python

# Print a backslash
print("C:\\Users\\Bhanu")
# Output: C:\Users\Bhanu

# Single quote inside a string
print('It\'s Python!')
# Output: It's Python!

# Double quotes inside a string
print("\"Python is great!\"")
# Output: "Python is great!"

# 5️⃣ Print with Emojis & Unicode

# Printing an emoji
print("Hello 😊")  # Output: Hello 😊

# Printing Unicode character (Heart Symbol)
print("\u2764")  # Output: ❤

# 6️⃣ Redirecting Print Output to a File
with open("output.txt", "w") as f:
    print("This is saved in a file.", file=f)

# 7️⃣ Common Mistakes in print()

# ✅ Correct usage of separators and end parameters
print("Hello", "World", sep="-", end="!")  # Output: Hello-World!

# ❌ Incorrect usage - Missing comma before sep
# print("Hello", "World" sep="-")  # SyntaxError: Missing comma

