# Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program
~~~
def result(a, b):
    return a % b
a = int(input("Enter the first number (a): "))
b = int(input("Enter the second number (b): "))
modulo = result(a, b)
print("The result of", a, "%", b, "is:", modulo)
~~~

## Output
![2,2](https://github.com/user-attachments/assets/66a6fb5a-f536-4bae-8bed-038c4d8b3026)

## Result
Thus, the program has been successfully executed
