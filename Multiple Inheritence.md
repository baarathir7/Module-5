# Arithmetic Operations Using Multiple Inheritance in Python

This Python program demonstrates **multiple inheritance** by performing basic arithmetic operations — Addition, Subtraction, and Division — using three classes.

## 🎯 Aim

To write a Python program to calculate **Add, Sub & Division** using **Multiple Inheritance**.

## 🧠 Algorithm

1. **Define `Calculation1` class**
   - Contains `Summation(a, b)` method to return the sum of two numbers.
2. **Define `Calculation2` class**
   - Contains `Subtraction(a, b)` method to return the difference of two numbers.
3. **Define `Derived` class**
   - Inherits from both `Calculation1` and `Calculation2`.
   - Contains `Division(a, b)` method to return the division result.
4. **Input**
   - Prompt the user to enter two numbers.
5. **Process**
   - Create an object of the `Derived` class.
   - Call `Summation`, `Subtraction`, and `Division` methods.
6. **Output**
   - Display the results of the three operations.

## 💻 Program 
```class Calculation1:
    def Summation(self, a, b):
        return a + b



class Calculation2:
    def Subtraction(self, a, b):
        return a - b


class Derived(Calculation1, Calculation2):
    def Division(self, a, b):
        if b == 0:
            return "Division by zero not allowed"
        return a / b



num1 = int(input())
num2 = int(input())


obj = Derived()

sum_result = obj.Summation(num1, num2)
sub_result = obj.Subtraction(num1, num2)
div_result = obj.Division(num1, num2)


print("\nResults:")
print("Addition:", sum_result)
print("Subtraction:", sub_result)
print("Division:", div_result)
```
## Output Example
<img width="306" height="80" alt="530751025-6ce523b4-5ce3-4103-8f75-d01a4dfe1494" src="https://github.com/user-attachments/assets/0c524dff-b8e4-49df-a6ee-bf5b83ec06e7" />

## Result
Thus , the program has been executed successfully.

