# # Constructors in Python: Welcome Message with Student Name

## 🎯 Aim
To write a Python program that creates a **Student** class with a **default constructor** and a method to display a welcome message along with the student’s name provided by the user.

## 🧠 Algorithm
1. **Get user input**: Accept the student's name from the user.
2. **Define the class**: Create a class `Student` with a default constructor (`__init__`).
3. **Default Constructor**: In the constructor, assign the user input (student name) to an instance variable `self.a`.
4. **Display Message**: Define a method `show` that prints "This is non-parameterized constructor" and a welcome message with the student’s name.
5. **Execute the Program**: Instantiate the `Student` class and call the `show` method.

## 🧾 Program
```
# Python program using default constructor

# Get student name from user
name = input("Enter student name: ")

# Define class
class Student:

    # Default constructor
    def __init__(self):
        self.a = name

    # Method to display message
    def show(self):
        print("This is non-parameterized constructor")
        print("Welcome", self.a)

# Create object
obj = Student()

# Call method
obj.show()
```
## Output
<img width="1155" height="232" alt="530749055-3b057e4c-8618-467f-9f07-c00ca95bcfe4" src="https://github.com/user-attachments/assets/85589689-ad97-412f-a37f-810b18f02848" />

## Result
The program is verified.


