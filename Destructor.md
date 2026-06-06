# Destructor in Python

This project demonstrates how to implement a **destructor** in Python using a simple class.

## 🚀 Overview

The program defines a class `Demo` with:

- A **constructor** `__init__` that initializes an instance variable and prints a message.
- A **destructor** `__del__` that prints a message when the object is destroyed.

## 🧠 Algorithm

1. Define a class named `Demo`.
2. Inside the class, define the `__init__` method:
   - Initialize an instance variable `status` with the value `"Alive"`.
   - Print the value of `status`.
3. Define the `__del__` method:
   - Print a message indicating the object is being destroyed.
4. Outside the class:
   - Create an instance of the `Demo` class.
   - Delete the object using the `del` keyword.
## Program
```# Python program to demonstrate destructor

# Define class
class Demo:

    # Constructor
    def __init__(self):
        self.status = "Alive"
        print("Object status:", self.status)

    # Destructor
    def __del__(self):
        print("Object is destroyed")

# Create object
obj = Demo()

# Delete object
del obj
```
## 🧪 Output
<img width="717" height="147" alt="530749590-af6797a5-f2bc-496f-9465-5f7513f73678" src="https://github.com/user-attachments/assets/eb4c0dca-71e2-4438-8e78-4acde1e2f442" />

## Result
The program is verified.



