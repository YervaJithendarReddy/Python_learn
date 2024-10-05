# Python Assignments

This repository contains a collection of Python assignments that I have practiced, covering both fundamental and advanced topics. Each assignment is written in Jupyter Notebook (`.ipynb`) format, making it easy to follow and understand.

## Topics Covered

### 1. **Data Types and Variables**
   - **int, float, complex, boolean:**
     - Python provides various data types to work with, including integers (`int`), floating-point numbers (`float`), complex numbers (`complex`), and booleans (`bool`).
     - Assigning values to variables and performing basic arithmetic and logical operations.
     - Example:
       ```python
       x = 5  # int
       y = 3.14  # float
       z = 2 + 3j  # complex number
       is_active = True  # boolean
       ```

### 2. **Strings**
   - **Manipulating strings:**
     - Strings in Python are sequences of characters, and they support various operations for manipulation, slicing, and formatting.
     - Example:
       ```python
       name = "Jithendar"
       print(name.upper())  # Convert to uppercase
       print(name[0:4])  # String slicing
       ```

### 3. **Conditional Statements**
   - **if, elif, else:**
     - Conditional statements allow executing specific blocks of code based on certain conditions.
     - Example:
       ```python
       if x > 10:
           print("x is greater than 10")
       elif x == 10:
           print("x is equal to 10")
       else:
           print("x is less than 10")
       ```

### 4. **Loops**
   - **for and while loops:**
     - Python provides loops to iterate over data structures and execute repetitive tasks.
     - Example:
       ```python
       for i in range(5):
           print(i)
       
       while x > 0:
           print(x)
           x -= 1
       ```

### 5. **Lists and Dictionaries**
   - **Working with lists:**
     - Lists in Python are mutable and can contain items of various data types.
     - Example:
       ```python
       my_list = [1, 2, 3, 4, 5]
       my_list.append(6)  # Adding an element
       print(my_list)
       ```
   - **Working with dictionaries:**
     - Dictionaries are key-value pairs, allowing for fast lookups and organizing data.
     - Example:
       ```python
       my_dict = {'name': 'Jithendar', 'age': 24}
       print(my_dict['name'])  # Accessing value by key
       my_dict['age'] = 25  # Modifying a value
       ```

### 6. **Functions**
   - **Defining and using functions:**
     - Functions help structure code into reusable blocks.
     - Example:
       ```python
       def greet(name):
           return f"Hello, {name}!"
       
       print(greet("Jithendar"))
       ```

### 7. **Regular Expressions (regex)**
   - **Pattern matching and string operations:**
     - Regular expressions help in matching patterns within strings, useful for searching and data extraction.
     - Example:
       ```python
       import re
       
       pattern = r"\d+"
       text = "There are 123 numbers in this sentence."
       match = re.findall(pattern, text)
       print(match)  # ['123']
       ```

### 8. **File Handling**
   - **Reading from and writing to files:**
     - Python provides functionality to work with files to read, write, and append data.
     - Example:
       ```python
       with open('example.txt', 'w') as file:
           file.write("Hello, this is a file write operation.")
       ```

### 9. **Numpy**
   - **Working with arrays:**
     - Numpy is a powerful library for numerical operations and managing multidimensional arrays.
     - Example:
       ```python
       import numpy as np
       
       arr = np.array([1, 2, 3, 4, 5])
       print(arr * 2)  # [2 4 6 8 10]
       ```

### 10. **Pandas**
   - **Data manipulation and analysis:**
     - Pandas is an essential library for handling and analyzing data in Python. It provides DataFrames and Series, which make it easy to work with structured data.
     - Example:
       ```python
       import pandas as pd
       
       # Creating a DataFrame
       data = {'Name': ['Alice', 'Bob', 'Charlie'], 'Age': [25, 30, 35]}
       df = pd.DataFrame(data)
       print(df)

       # Data manipulation
       df['Age'] = df['Age'] + 1  # Incrementing ages
       print(df)
       ```

### 11. **Object-Oriented Programming (OOP) Concepts**
   - **Classes, Objects, Inheritance, Polymorphism:**
     - Object-Oriented Programming (OOP) in Python helps to structure code using classes and objects.
     - **Classes:** Define the blueprint for objects.
     - **Objects:** Instances of classes.
     - **Inheritance:** A way to create a new class from an existing class.
     - **Polymorphism:** Allows methods to be used in different ways based on the object.
     - Example:
       ```python
       # Defining a class
       class Person:
           def __init__(self, name, age):
               self.name = name
               self.age = age
           
           def greet(self):
               print(f"Hello, my name is {self.name} and I am {self.age} years old.")
       
       # Creating an object
       person1 = Person("Jithendar", 24)
       person1.greet()
       
       # Inheritance example
       class Student(Person):
           def __init__(self, name, age, student_id):
               super().__init__(name, age)
               self.student_id = student_id
           
           def study(self):
               print(f"Student {self.name} is studying.")
       
       student1 = Student("Jithendar", 24, "S12345")
       student1.greet()
       student1.study()
       ```

---

Each of these topics is crucial for building a strong foundation in Python programming. This repository contains practice notebooks on all these topics, designed to help improve your understanding of Python.

Feel free to explore the notebooks, clone the repository, and contribute to further improvements!
