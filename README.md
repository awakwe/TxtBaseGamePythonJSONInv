<!--
author:   U. Anthony Omegbu
email:    anthonyomegbu@gmail.com
version:  0.0.1

tags:     LiaScript, education, Python, text-based adventure game, JSON, inventory, tutorial

logo:     https://raw.githubusercontent.com/awakwe/TxtBaseGamePythonJSONInv/main/300415254_475324704602623_3287306073814126999_n.jpg

comment:  This course introduces coding a text-based adventure game in Python using JSON for inventory management. Learn the fundamentals of Python and JSON while building an interactive game.

-->

# Intro to Coding a Text-Based Adventure Game in Python using JSON Inv
Introduction to Coding a Text-Based Adventure Game in Python using JSON Inventory![image](https://user-images.githubusercontent.com/13156704/225758367-9629dfc4-f006-4f24-905e-10e630fe4bcc.png)

Welcome to this course on coding a text-based adventure game in Python using JSON for inventory management. Throughout this course, you will learn the fundamentals of Python programming and JSON while building an interactive game.
### About Me

Hello, and welcome to this course on creating a text-based adventure game using Python and JSON inventory! My name is Tony, and I'll be your instructor throughout this exciting journey. I'm a passionate engineer and educator with years of experience in the field.

I've always been intrigued by the world of game development, and text-based adventure games hold a special place in my heart. Through this course, I hope to share my enthusiasm for programming and game design with you, while equipping you with valuable skills that you can apply to various programming projects.

In my spare time, I enjoy tinkering with new programming languages, exploring open-source projects, and learning about the latest advancements in technology. I believe that education is a lifelong journey, and I'm excited to be a part of your learning experience.

I can't wait to get started on this adventure with you. Let's dive into the world of Python programming and create an engaging text-based adventure game together!

## Lesson 1: Introduction to Python Programming

### Variables and Data Types

- Variables: Storing data for later use
- Data Types: int, float, str, bool, list, dict

Variables and Data Types
========================

In this section, we'll discuss variables and data types in Python, which are essential building blocks for any program. Understanding these concepts is crucial for creating a text-based adventure game or any other programming project.

Variables
---------

Variables are used to store data in your program. They can be thought of as containers that hold information that can be accessed and manipulated throughout your code. To create a variable, you simply assign a value to a name using the equal sign `=`.

Example:

python

```python
name = "John"
age = 25
```

In this example, we create two variables: `name`, which stores the string "John" and `age`, which stores the integer 25.

Data Types
----------

Python has several built-in data types that you'll use frequently when programming. Here are some of the most common ones:

### Strings

Strings are sequences of characters, such as words or sentences. They are enclosed in either single or double quotes.

Example:

python

```python
greeting = "Hello, world!"
```

### Integers

Integers are whole numbers, both positive and negative.

Example:

python

```python
score = 42
```

### Floats

Floats, or floating-point numbers, are numbers with a decimal point.

Example:

python

```python
pi = 3.14159
```

### Lists

Lists are ordered collections of items. They can store items of any data type, and they are mutable, meaning you can change their contents.

Example:

python

```python
colors = ["red", "green", "blue"]
```

### Dictionaries

Dictionaries are unordered collections of key-value pairs. They are useful for storing data that can be easily accessed using keys.

Example:

python

```python
player_info = {
    "name": "John",
    "age": 25,
    "score": 42
}
```

By understanding variables and data types in Python, you'll be well-prepared to create complex programs and games, such as the text-based adventure game we'll be building in this course.

### Loops

- For Loops: Iterating over a sequence
- While Loops: Iterating based on a condition

Loops
=====

Loops are an essential programming concept that allows you to execute a block of code multiple times. In this section, we'll cover the two primary types of loops in Python: `for` loops and `while` loops. These will be invaluable for creating a text-based adventure game or any other programming project.

For Loops
---------

A `for` loop is used to iterate over a sequence, such as a list or a string. The loop executes a block of code once for each item in the sequence.

Example:

python

```python
colors = ["red", "green", "blue"]

for color in colors:
    print(color)
```

In this example, the `for` loop iterates through the `colors` list and prints each color.

### Range Function

The `range()` function is commonly used with `for` loops to generate a sequence of numbers that the loop can iterate over.

Example:

python

```python
for i in range(5):
    print(i)
```

This code will output the numbers 0 to 4, as the `range()` function generates a sequence of numbers starting from 0 up to, but not including, the specified number.

While Loops
-----------

A `while` loop repeatedly executes a block of code as long as a specified condition is `True`.

Example:

python

```python
counter = 0

while counter < 5:
    print(counter)
    counter += 1
```

In this example, the `while` loop will continue to execute as long as the value of `counter` is less than 5. It will print the value of `counter` and then increment it by 1 each iteration.

Loop Control Statements
-----------------------

Loop control statements can be used to change the behavior of a loop during its execution. There are two main loop control statements in Python: `break` and `continue`.

### Break

The `break` statement is used to exit the loop prematurely. When a `break` statement is encountered, the loop will terminate immediately.

Example:

python

```python
for i in range(10):
    if i == 5:
        break
    print(i)
```

In this example, the loop will terminate when `i` equals 5, and only the numbers 0 to 4 will be printed.

### Continue

The `continue` statement is used to skip the rest of the code in the current iteration and move on to the next iteration.

Example:

python

```python
for i in range(10):
    if i % 2 == 0:
        continue
    print(i)
```

In this example, the loop will skip even numbers and only print odd numbers.

Understanding loops and loop control statements in Python will enable you to create more dynamic and efficient programs, including the text-based adventure game we'll be building in this course.

### Functions

- Defining functions: Using `def` keyword
- Calling functions: Executing a function

Functions
=========

Functions are reusable pieces of code that allow you to perform a specific task in your program. They help make your code more modular, organized, and maintainable. In this section, we'll discuss how to define and call functions in Python, which will be crucial for creating a text-based adventure game or any other programming project.

Defining Functions
------------------

To define a function in Python, you use the `def` keyword, followed by the function name and a pair of parentheses containing any parameters the function accepts. Finally, you add a colon and write the function's code block, which should be indented.

Example:

python

```python
def greet(name):
    print(f"Hello, {name}!")
```

In this example, we've defined a function called `greet` that takes a single parameter, `name`. The function prints a greeting with the given name.

Calling Functions
-----------------

To call a function, you simply write the function's name followed by a pair of parentheses containing any arguments that the function expects.

Example:

python

```python
greet("John")
```

In this example, we call the `greet` function and pass the string "John" as an argument. The output will be "Hello, John!".

Return Values
-------------

Functions can return a value to the caller using the `return` keyword. This allows you to use the result of a function in other parts of your code.

Example:

python

```python
def add(a, b):
    return a + b

result = add(3, 5)
print(result)
```

In this example, the `add` function takes two parameters, `a` and `b`, and returns their sum. When we call the function with the arguments 3 and 5, it returns 8, which we store in the variable `result` and then print.

Default Parameters
------------------

You can set default values for function parameters, allowing the caller to omit those arguments when calling the function. Default parameters are specified in the function definition using the assignment operator `=`.

Example:

python

```python
def greet(name, greeting="Hello"):
    print(f"{greeting}, {name}!")

greet("John")
greet("Jane", "Good morning")
```

In this example, the `greet` function has a default value of "Hello" for the `greeting` parameter. If the caller doesn't provide a value for `greeting`, it will default to "Hello". The first function call will output "Hello, John!", while the second will output "Good morning, Jane!".

By understanding how to define and use functions in Python, you can create more organized, reusable, and efficient code, which will be essential when building a text-based adventure game or any other programming project.

## Lesson 2: JSON Inventory

### JSON Data Structures

- Objects: Enclosed by `{ }`
- Arrays: Enclosed by `[ ]`
- Properties: Separated by colons

JSON Data Structures
====================

JSON (JavaScript Object Notation) is a lightweight data interchange format that is easy for humans to read and write and easy for machines to parse and generate. It is a widely used format for data exchange between a server and a client in web applications. JSON closely resembles Python dictionaries, and in this section, we'll discuss how to work with JSON data structures in Python.

JSON and Python
---------------

In Python, the `json` module provides methods to work with JSON data. It allows you to convert between JSON text and Python objects, such as dictionaries, lists, strings, numbers, and booleans.

### Importing the JSON module

To work with JSON data in Python, you first need to import the `json` module.

python

```python
import json
```

### Converting Python Objects to JSON

To convert a Python object into a JSON string, you can use the `json.dumps()` function.

Example:

python

```python
import json

data = {
    "name": "John",
    "age": 25,
    "city": "New York"
}

json_data = json.dumps(data)
print(json_data)
```

In this example, the `data` variable contains a Python dictionary. The `json.dumps()` function converts the dictionary into a JSON-formatted string.

### Converting JSON to Python Objects

To convert a JSON string into a Python object, you can use the `json.loads()` function.

Example:

python

```python
import json

json_data = '{"name": "John", "age": 25, "city": "New York"}'
data = json.loads(json_data)

print(data["name"])
print(data["age"])
```

In this example, the `json_data` variable contains a JSON-formatted string. The `json.loads()` function converts the string into a Python dictionary.

Working with JSON Files
-----------------------

You can also read and write JSON data directly from and to files using the `json.load()` and `json.dump()` functions.

### Reading JSON from a File

To read JSON data from a file, you can use the `json.load()` function.

Example:

python

```python
import json

with open("data.json", "r") as file:
    data = json.load(file)

print(data)
```

In this example, we open a file called `data.json` in read mode and use the `json.load()` function to load the JSON data into a Python object.

### Writing JSON to a File

To write JSON data to a file, you can use the `json.dump()` function.

Example:

python

```python
import json

data = {
    "name": "John",
    "age": 25,
    "city": "New York"
}

with open("data.json", "w") as file:
    json.dump(data, file)
```

In this example, we open a file called `data.json` in write mode and use the `json.dump()` function to write the JSON data to the file.

By understanding how to work with JSON data structures in Python, you can easily exchange data between your program and various web services or APIs, which can be useful for creating text-based adventure games or any other programming projects.

### JSON Advantages

- Versatile: Wide range of information
- Easy to use: Human-readable
- Industry standard: Widely accepted

JSON Advantages
===============

JSON (JavaScript Object Notation) is a widely popular data interchange format due to its many advantages. In this section, we'll discuss the various benefits of using JSON for data exchange and storage.

1\. Readability and Simplicity
------------------------------

JSON is human-readable and easy to understand. Its syntax closely resembles the syntax of dictionaries and objects in many programming languages, including Python, JavaScript, and others. This similarity makes JSON an excellent choice for developers who want a simple way to represent and share data structures.

2\. Lightweight
---------------

JSON is a lightweight format compared to other data interchange formats like XML. JSON's minimal syntax requires less data to represent the same information, which leads to smaller data payloads and faster data transfer over networks.

3\. Language-Independent
------------------------

JSON is a language-independent format, which means it can be used with various programming languages. Many programming languages, including Python, JavaScript, Java, Ruby, and others, have built-in support or libraries for handling JSON data. This wide support makes JSON a convenient choice for cross-language data exchange.

4\. Easy to Parse and Generate
------------------------------

JSON data can be easily parsed and generated by machines, making it an efficient choice for communication between a client and a server in web applications. JSON libraries are available in most programming languages, providing simple methods for converting between JSON strings and native data structures.

5\. Native Support in JavaScript
--------------------------------

JSON has native support in JavaScript, the language used for client-side web development. This native support means that JSON data can be directly used as JavaScript objects, making it a seamless choice for data exchange in web applications.

6\. Flexible Data Structure
---------------------------

JSON supports various data structures, including nested objects and arrays, which allows for complex and flexible data representation. This flexibility makes JSON suitable for a wide range of applications, from simple key-value storage to more intricate hierarchical data modeling.

In summary, JSON's advantages include its readability, simplicity, lightweight nature, language independence, ease of parsing and generation, native support in JavaScript, and flexible data structure. These benefits make JSON a popular and versatile choice for data exchange and storage in various programming projects, including text-based adventure games, web applications, and more.

### JSON Limitations

- Large data management: Difficult to manage as data increases
- Not designed to be a database

JSON Limitations
================

While JSON has many advantages, it's important to recognize its limitations as well. In this section, we'll discuss some of the challenges and drawbacks associated with using JSON for data exchange and storage.

1\. Lack of Data Types
----------------------

JSON supports a limited set of data types, including strings, numbers, booleans, objects, and arrays. However, it does not support more advanced data types such as dates, binary data, or custom data types specific to a programming language. As a result, developers may need to use workarounds or additional encoding to represent certain types of data.

2\. No Support for Comments
---------------------------

JSON does not support comments, making it difficult to add explanatory notes within a JSON file. This limitation can affect the readability and maintainability of JSON data, particularly when working with large or complex data structures.

3\. Verbosity
-------------

Although JSON is less verbose than formats like XML, it can still be more verbose than other data representation formats such as binary formats or message pack. When working with large data sets or performance-critical applications, JSON's verbosity may be a concern due to increased data size and parsing time.

4\. No Schema Definition
------------------------

JSON does not have a built-in schema definition language, making it challenging to enforce data structure consistency or validate JSON data against a specific schema. While there are third-party JSON schema definition tools available, the lack of a native solution is a limitation to consider when choosing a data interchange format.

5\. Security Concerns
---------------------

When working with JSON in web applications, developers must be aware of potential security risks, such as Cross-site Scripting (XSS) attacks or JSON hijacking. To mitigate these risks, developers must follow best practices, such as using secure JSON parsing libraries and validating input data.

6\. Limited Error Handling
--------------------------

JSON parsers typically halt at the first error encountered, making it difficult to identify and fix multiple errors in a JSON file. This limitation can make debugging and validation more time-consuming when working with JSON data.

In conclusion, while JSON offers many advantages as a data interchange format, it's important to consider its limitations, including the lack of advanced data types, no support for comments, verbosity, absence of a native schema definition, security concerns, and limited error handling. Depending on the specific requirements of a project, these limitations may influence the decision to use JSON or opt for an alternative data format.

## Lesson 3: Skeleton Code

### Basic Code Structure

- Moving between rooms
- Collecting items

Basic Code Structure for a Text-Based Game
==========================================

Creating a text-based game requires organizing your code in a clear and logical manner. In this section, we'll discuss the basic structure of a Python program for a text-based game, which includes importing required libraries, defining functions, and implementing game logic.

markdown

```markdown
## Import Libraries

At the beginning of your program, import any necessary libraries that will be used throughout the game. For example, you might need the `random` library for generating random events or the `json` library for working with JSON data.

```python
import random
import json
```

Define Functions
----------------

Next, define functions that will be used to handle different aspects of the game, such as displaying the game's introduction, processing user input, or managing game events. Organizing your code into functions makes it easier to understand, maintain, and troubleshoot.

python

```python
def display_intro():
    # Code to display the game's introduction

def process_input(user_input):
    # Code to process and validate user input

def handle_event(event):
    # Code to manage game events
```

Game Data
---------

Define your game data, such as characters, items, and locations, using variables and data structures like dictionaries and lists. You can also load this data from external files, such as JSON or text files, if needed.

python

```python
characters = {
    "player": {"name": "John", "health": 100, "inventory": []},
    "enemy": {"name": "Goblin", "health": 50}
}

items = [
    {"name": "Sword", "damage": 10},
    {"name": "Potion", "healing": 20}
]

locations = ["forest", "cave", "castle"]
```

Main Game Loop
--------------

Create a main game loop that runs until the game is over, which can be due to the player winning, losing, or choosing to quit. Within the loop, display game information, prompt the user for input, process the input, and update the game state accordingly.

python

```python
def main():
    display_intro()

    game_over = False
    while not game_over:
        # Display game information

        # Get user input
        user_input = input("> ")

        # Process input and update game state
        game_over = process_input(user_input)

if __name__ == "__main__":
    main()
```

By following this basic code structure, you'll create a well-organized text-based game that is easy to understand and modify as you add more features and complexity.

### Adding Features

- Different paths
- New items
- Obstacles

Adding Features to a Text-Based Game
====================================

As you build your text-based game, you may want to expand its features and capabilities to create a more engaging and immersive experience for the player. In this section, we'll discuss some ideas for adding features to your game, including inventory management, character interactions, and more complex game events.

Inventory Management
--------------------

An inventory system allows players to collect, use, and manage items they find throughout the game. To add this feature, you'll need to:

1.  Create an inventory data structure, such as a list, for the player character.
2.  Add functions for managing the inventory, such as adding or removing items.
3.  Implement game events that involve inventory items, like finding items or using them in specific situations.

python

```python
def add_item_to_inventory(item):
    # Code to add an item to the player's inventory

def remove_item_from_inventory(item):
    # Code to remove an item from the player's inventory

def use_item(item):
    # Code to use an item and apply its effects
```

Character Interactions
----------------------

Character interactions bring your game world to life and can involve conversations, trading, or even combat. To add character interactions, consider:

1.  Defining characters using data structures like dictionaries, including their attributes, inventory, and dialogue.
2.  Creating functions for handling interactions, such as talking to characters or initiating combat.
3.  Implementing game events that involve character interactions, like meeting new characters or triggering quests.

python

```python
def talk_to_character(character):
    # Code to initiate a conversation with a character

def initiate_combat(character):
    # Code to start combat with a character

def trade_with_character(character):
    # Code to trade items with a character
```

Complex Game Events
-------------------

Adding more complex game events can increase the depth and variety of your game. These events can be random or triggered by specific actions or conditions. Examples of complex game events include:

1.  Random encounters: Create functions that generate random events, such as enemy attacks or finding hidden treasure, based on the player's location or actions.
2.  Puzzles: Design puzzles or challenges that the player must solve to progress in the game. This can involve using items, interacting with objects, or deciphering clues.
3.  Branching storylines: Develop multiple story paths that the player can follow based on their choices, leading to different outcomes and endings.

python

```python
def random_encounter():
    # Code to generate a random encounter

def solve_puzzle(puzzle):
    # Code to present a puzzle and process the player's solution

def make_choice(choice):
    # Code to handle player choices and update the game state accordingly
```

By adding features like inventory management, character interactions, and complex game events, you'll create a richer and more engaging text-based game for players to enjoy. Remember to keep your code organized and modular, making it easier to add, modify, and troubleshoot features as your game grows.

## Lesson 4: Debugging and Troubleshooting

### Handling Errors and Exceptions

- Syntax Errors
- ZeroDivisionError
- ValueError

Handling Errors and Exceptions
==============================

When developing a text-based game or any other software, it's crucial to handle errors and exceptions that may occur during the execution of your program. This helps maintain a smooth user experience and prevents your game from crashing due to unexpected inputs or other issues. In this section, we'll discuss how to handle errors and exceptions in Python using try-except blocks.

The try-except Block
--------------------

A try-except block is used to handle exceptions in Python. When an exception occurs within the `try` block, the code inside the `except` block is executed, allowing you to handle the exception gracefully.

Here's an example of a try-except block:

python

```python
try:
    # Code that may raise an exception
    x = int(input("Enter a number: "))
except ValueError:
    # Code to handle the exception
    print("Invalid input. Please enter a number.")
```

In this example, the `try` block contains code that might raise a `ValueError` exception if the user inputs a non-numeric value. If an exception occurs, the code inside the `except` block is executed, informing the user about the error.

Handling Multiple Exceptions
----------------------------

You can handle multiple exceptions by specifying multiple `except` blocks, each handling a different exception type:

python

```python
try:
    # Code that may raise an exception
    x = int(input("Enter a number: "))
    result = 10 / x
except ValueError:
    # Handle the ValueError exception
    print("Invalid input. Please enter a number.")
except ZeroDivisionError:
    # Handle the ZeroDivisionError exception
    print("Division by zero is not allowed.")
```

In this example, we handle both `ValueError` and `ZeroDivisionError` exceptions.

The finally Block
-----------------

You can use the `finally` block to specify code that should be executed regardless of whether an exception occurs or not:

python

```python
try:
    # Code that may raise an exception
    x = int(input("Enter a number: "))
    result = 10 / x
except ValueError:
    # Handle the ValueError exception
    print("Invalid input. Please enter a number.")
except ZeroDivisionError:
    # Handle the ZeroDivisionError exception
    print("Division by zero is not allowed.")
finally:
    # Code to be executed regardless of exceptions
    print("Program execution completed.")
```

By using try-except blocks and handling errors and exceptions in your text-based game, you can ensure a smooth and enjoyable experience for your players. Keep in mind that proper error handling is essential for creating a polished and professional game.

### Example: User Input & Exceptions

- `input` function for user input
- Exception handling with `try` and `except`

User Input & Exceptions
=======================

In a text-based game, handling user input and exceptions is crucial to creating an enjoyable and smooth gaming experience. In this section, we'll discuss how to take user input, validate it, and handle exceptions that may arise from invalid inputs.

Taking User Input
-----------------

To take input from the user in Python, you can use the `input()` function. It takes an optional string argument that you can use as a prompt, and it returns the user's input as a string.

Example:

python

```python
player_name = input("Enter your name: ")
print(f"Welcome, {player_name}!")
```

Validating User Input
---------------------

Before using the user's input, it's a good practice to validate it. For instance, you may want to ensure the user has entered a valid number or that their input matches one of the available options in your game.

Here's an example of validating user input for a simple menu system:

python

```python
options = ['start', 'load', 'quit']

user_input = input("Enter your choice (start, load, quit): ").lower()

while user_input not in options:
    print("Invalid input. Please try again.")
    user_input = input("Enter your choice (start, load, quit): ").lower()

print(f"You selected {user_input}.")
```

In this example, we use a `while` loop to keep asking the user for input until they enter a valid option.

Handling Input Exceptions
-------------------------

Sometimes, user input may lead to exceptions in your code, such as when the user enters a non-numeric value when a number is expected. To handle such exceptions, you can use try-except blocks.

Here's an example of handling exceptions while taking numeric input:

python

```python
while True:
    try:
        user_input = int(input("Enter a number between 1 and 10: "))
        if 1 <= user_input <= 10:
            break
        else:
            print("Number must be between 1 and 10.")
    except ValueError:
        print("Invalid input. Please enter a number.")
```

In this example, we use a `try` block to attempt converting the user's input to an integer. If a `ValueError` exception occurs, the code inside the `except` block is executed, prompting the user to enter a valid number.

By handling user input and exceptions in your text-based game, you can ensure a more enjoyable experience for your players and prevent unexpected issues from arising due to invalid inputs. Remember that validating user input and handling exceptions are essential aspects of creating a polished and professional game.

## Lesson 5: Project & Conclusion

### Project Submission

- Post completed project in Project Gallery
[SkillShare course](https://skl.sh/3lzpF6l)

### Key Takeaways

- Importance of data structures
- Using JSON for inventory management
- Python programming basics

Key Takeaways
=============

Throughout this course, we have covered several important concepts for building a text-based adventure game in Python. Let's recap the key takeaways:

1.  **Variables and Data Types**: Python offers various data types such as strings, integers, floats, lists, and dictionaries. Understanding these data types and their use is essential for creating efficient and readable code.
    
2.  **Loops**: Loops, including `for` and `while` loops, allow you to execute code multiple times. They are especially useful in text-based games when you need to iterate through lists, dictionaries, or repeat actions based on user input.
    
3.  **Functions**: Functions help you organize your code, making it more readable and reusable. They are a powerful tool for creating modular and maintainable games.
    
4.  **JSON Data Structures**: JSON is a lightweight data interchange format that is easy to read and write. It is useful for storing game data such as configurations, character attributes, and game progress.
    
5.  **Advantages and Limitations of JSON**: JSON offers several advantages, such as its simplicity, human readability, and widespread support. However, it also has limitations, such as lack of support for custom data types and limited data types compared to Python.
    
6.  **Basic Code Structure**: Organizing your code in a clear and logical manner is crucial for creating a maintainable and scalable text-based game. Using functions, classes, and modules can help you achieve a well-structured codebase.
    
7.  **Adding Features**: To create a rich and engaging text-based game, consider implementing features such as branching storylines, inventory systems, and character customization.
    
8.  **Handling Errors and Exceptions**: Properly handling errors and exceptions in your code helps create a more robust and user-friendly game. Using try-except blocks allows you to manage errors gracefully and provide helpful feedback to the player.
    
9.  **User Input & Exceptions**: Taking user input and validating it is essential in a text-based game. Ensuring that the user's input is properly processed and that exceptions are handled will lead to a smoother and more enjoyable gaming experience.
    

By mastering these concepts and implementing them in your text-based adventure game, you'll be well on your way to creating an engaging and enjoyable experience for your players.

### Final Message

- Thank you for joining the course
- Continue to explore new programming skills
- Happy coding!

[preview-lia](https://raw.githubusercontent.com/awakwe/TxtBaseGamePythonJSONInv/main/README.md)

[Preview-Lia](https://liascript.github.io/course/?https://raw.githubusercontent.com/awakwe/TxtBaseGamePythonJSONInv/main/README.md)
