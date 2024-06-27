[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15337151&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.
      A: Python is a high-level, interpreted programming language known for its readablity and simplicity. It was created by Guido van Rossum and first released in 1991.
      B: some of its key features are:
         (i) Readable and Maintainable Code: Python its easy to read and maintain and also this makes the useability of it just like django.
         (ii) Extensive Standard Library: Python comes with a vast standard library that canbe both used in machine learning and data sciecnce which makes it compatible with many frame works.
         (iii) Interpreted Language: Python code is executed line by line, which makes debugging easier.

2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.
      Go to the Python website.
      Download the latest Python installer for Windows.
      Run the downloaded installer.
      Ensure you check the option "Add Python to PATH."
      Choose "Install Now" or customize the installation.
      Open Command Prompt.
      Type python --version to verify the installation.
      Open Command Prompt.
      Install virtualenv by running pip install virtualenv.
      Create a virtual environment: virtualenv myenv.
      Activate the virtual environment: myenv\Scripts\activate.

3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.
      Message = "Hello, World!" give the variable name message 
      print(Message) print is used to output the message that will be Hello, World!

4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.
      int: Integer values (e.g., 1, 42)
      float: Floating-point numbers (2.718)
      str: String literals ("Python")
      bool: Boolean values (True, False)
      list: Ordered collections of items (e.g., [1, 2, 3])
      dict: Key-value pairs ({"name": "Tony", "age": 25})

5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.
      A:Conditional statements are a fundamental concept in programming that allow you to make decisions in your code based on certain conditions. eg
         x = 10
         if x > 5:
            print("x is greater than 5")
         else:
            print(9)
      B:The for loop in Python is used for iterating over a sequence (such as a list, tuple, string, or range).
         word = "Power Learn"
         for letter in word:
         print(letter)

6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.
      A:Functions are reusable blocks of code that perform a specific task. They help in organizing and modularizing code.
         def add(a, b)
            return a + b
            result = add(3, 5)
            print(result)

7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.
      A: List: Ordered collection of items, accessed by index and Dictionary: Unordered collection of key-value pairs, accessed by key.
      E.g list: Names = ["Tony", "Firimicah", "Felix"]
            print(Names[0])
      E.g Dictionary Tony = {"Name" : "Tony", "Age" : 19 "Hobbies" : "Programming, Gamer, Playing, Rugby"}
      print(Tony(Name))

8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.
   A:Exception handling is a mechanism to handle runtime errors gracefully using try, except, and finally blocks.
      examples:
            try:
            result = 10 / 0
         except ZeroDivisionError:
            print("Cannot divide by zero")
         finally:
            print("This will always execute")

9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.
      Module: A file containing Python definitions and statements.
      Package: A collection of modules in a directory.
      strings to a file.
      import math
      result = math.sqrt(16)
      print(result)
10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of 
         with open('example.txt', 'r') as file:
         content = file.read()
         print(content)
         lines = ["Hello, World!", "Python is great!"]

         with open('output.txt', 'w') as file:
            for line in lines:
               file.write(line + '\n')


# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


