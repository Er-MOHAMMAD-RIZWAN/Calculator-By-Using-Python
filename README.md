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
