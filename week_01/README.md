### assignment 1

This week we were asked to create a simple calculator.

x = int(input("please enter the first number : "))
y = int(input("please enter the second number : "))
operator = input("please neter the operator: ")

if operator == "*":
    print(x * y)
elif operator == "+":
    print(x + y)
elif operator == "-":
    print(x - y)
elif operator == "/":
    print (x / y)
else:
    print("Invalid operator, please try again!")