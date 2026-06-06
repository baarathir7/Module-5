# Multilevel Inheritance Example in Python

This Python project demonstrates the concept of **Multilevel Inheritance** to collect and display the **name**, **age**, and **location** of a person.

## 🎯 Aim

To write a Python program that uses multilevel inheritance to get and display a person’s name, age, and location.

## 🧠 Algorithm

1. **Parent Class**  
   - `__init__(name)` initializes the `name` attribute.  
   - `getName()` returns the `name`.

2. **Child Class (inherits Parent)**  
   - `__init__(name, age)` initializes `name` using `super()` and adds `age`.  
   - `getAge()` returns the `age`.

3. **Grandchild Class (inherits Child)**  
   - `__init__(name, age, location)` initializes `name` and `age` using `super()` and adds `location`.  
   - `getLocation()` returns the `location`.

4. **Input & Output**  
   - Take user input for name, age, and location.  
   - Create an instance of `Grandchild`.  
   - Print all details using class methods.

## Program
```
def getName(self):
    return self.name
def getAge(self):
    return self.age
 def __init__(self, name, age, location):
     super().__init__(name, age)
     self.location = location

 def getLocation(self):
     return self.location



name = input()
age = int(input())
location = input( )


obj = Grandchild(name, age, location)


print("\n--- Details ---")
print("Name:", obj.getName())
print("Age:", obj.getAge())
print("Location:", obj.getLocation())
```
## Sample Output
<img width="458" height="122" alt="530750455-74fbcece-25c9-4057-a745-9aa45b095bce" src="https://github.com/user-attachments/assets/811d44ab-7422-4c14-8f96-7ef229fa9615" />

## Result
Thus , the program has been executed successfully.

