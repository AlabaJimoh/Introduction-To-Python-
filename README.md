# Introduction-To-Python-
num1 = float(input("Enter the first number: "))

num2 = float(input("Enter the second number: "))

operation = input("Enter the operation (+, -, *, /): ")

if operation == '+':
    result = num1 + num2
elif operation == '-':
    result = num1 - num2
elif operation == '*':
    result = num1 * num2
elif operation == '/':
    if num2 == 0:
        result = "Error: Division by zero!"
    else:
        result = num1 / num2
else:
    result = "Error: Invalid operation"

print(f"{num1} {operation} {num2} = {result}")
