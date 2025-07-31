# Calculator-By-Using-Python

#calculator
def calculator():
    print("Welcome to a Calculator Made By Rizwan")
    print("Simple Calculator By Using Python")
    print("You can perform calculations in these operation: +  -  *  /")

    
num1 = float(input("Enter first number: "))
    op = input("Enter operation: ")
    num2 = float(input("Enter second number: "))

 if op == "+":
        result = num1 + num2
    elif op == "-":
        result = num1 - num2
    elif op == "*":
        result = num1 * num2
    elif op == "/":
        if num2 != 0:
            result = num1 / num2
        else:
            result = "Error (division by zero)"
    else:
        result = "Invalid operation"

 print("Result:", result)
 print("Thank You!")
