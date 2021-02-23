# A-simple-calculator
A simple calculator made using IF ELSE and ELIF statements.

def greet():
    print("Welcome to the Calculator made by Mr.Faisal Jamil")
greet()
num1 = int(input('Enter the first number:'))
op = (input('Enter the operator: '))
num2 = int(input('Enter the second number: '))

if op == "+":
    print("Your Answer is :", num1+num2)
elif op == "-":
    print("Your Answer is :",num1-num2,)
elif op == "*":
    print("Your Answer is :", num1*num2)
elif op == "/":
    print("Your Answer is :", num1, num2)
else:
    print("Invalid operator")
