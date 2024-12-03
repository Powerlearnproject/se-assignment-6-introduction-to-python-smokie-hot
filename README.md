[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15343437&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.

   Python is a high-level, interpreted programming language known for its readability and versatility. It supports multiple programming paradigms, including procedural, object-oriented, and functional programming.
   Key Features:

 Readability: Simple and clear syntax that emphasizes readability.
 Interpreted: Executes code line by line, which makes debugging easier.
 Dynamic Typing: Variables do not need explicit declaration to reserve memory space.
 Extensive Libraries: Rich set of libraries and frameworks (e.g., NumPy, Pandas, Django).
 Cross-Platform: Runs on various operating systems like Windows, macOS, and Linux.

2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.

   Download the installer from Python's official website.
   Run the installer and check the box to add Python to PATH.
   Follow the installation instructions.

   python --version
   python3 --version
   Install virtualenv (if not already installed): pip install virtualenv.
   Create a virtual environment: virtualenv myenv.
   Activate the virtual environment:
   Windows: myenv\Scripts\activate.


3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.

   print("Hello, World!")
   Explanation:
   print: A built-in function to output text to the console.
   "Hello, World!": A string literal enclosed in double quotes.

4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.

   Basic Data Types:

  int: Integer numbers (e.g., 1, 2, 3).
  float: Floating-point numbers (e.g., 1.0, 2.5).
  str: String literals (e.g., "hello").
  bool: Boolean values (e.g., True, False).
  list: Ordered collection of items (e.g., [1, 2, 3]).
  tuple: Immutable ordered collection of items (e.g., (1, 2, 3)).
  dict: Key-value pairs (e.g., {"name": "John", "age": 30}).

  # Creating variables of different data types
integer_var = 10
float_var = 20.5
string_var = "Hello, Python!"
bool_var = True
list_var = [1, 2, 3]
tuple_var = (4, 5, 6)
dict_var = {"name": "John", "age": 30}

# Using the variables
print(integer_var)
print(float_var)
print(string_var)
print(bool_var)
print(list_var)
print(tuple_var)
print(dict_var)

5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.
   
   age = 18
if age >= 18:
    print("You are an adult.")
else:
    print("You are a minor.")

# For loop
for i in range(5):
    print(i)

# While loop
count = 0
while count < 5:
    print(count)
    count += 1


6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.

   Functions are reusable blocks of code that perform a specific task. They help in organizing code and avoiding repetition.

   def add_numbers(a, b):
    return a + b

# Calling the function
result = add_numbers(5, 3)
print(result)  # Output: 8


7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.

List: Ordered, mutable, allows duplicate elements.
Dictionary: Unordered, mutable, stores key-value pairs, keys must be unique.

# List example
numbers = [1, 2, 3, 4, 5]
print(numbers)

# Dictionary example
person = {"name": "Alice", "age": 25, "city": "New York"}
print(person)

# Basic operations
numbers.append(6)
print(numbers)

person["email"] = "alice@example.com"
print(person)


8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.

   Exception handling in Python allows you to handle errors gracefully using try, except, and finally blocks.

   try:
    x = int(input("Enter a number: "))
    y = 10 / x
except ZeroDivisionError:
    print("Error: Division by zero is not allowed.")
except ValueError:
    print("Error: Invalid input. Please enter a number.")
finally:
    print("Execution completed.")


9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.

   Module: A single file containing Python code.
Package: A collection of modules in a directory that includes a special __init__.py file.

import math

print(math.sqrt(16))  # Output: 4.0


10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.

    Reading from a file.

    with open('input.txt', 'r') as file:
    content = file.read()
    print(content)
   
   Writing to a file.

   lines = ["Hello, world!", "Python is great!"]
with open('output.txt', 'w') as file:
    for line in lines:
        file.write(line + "\n")




# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


