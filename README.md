# week1PYTHON

This is  a simple Python program that asks the user to input two numbers and a mathematical operation.

num1 = int(input("Enter your first number: "))
num2 = int(input("Enter your second number: "))
operator = input("Enter an operator(+, *, -, /: ")

if operator == '+':
    print(num1 + num2)
elif operator == '-':
    print(num1 - num2)
elif operator == '*':
    print(num1 * num2)
elif operator == '/':
    print(num1 / num2)

