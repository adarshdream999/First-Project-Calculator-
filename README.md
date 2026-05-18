# First-Project-Calculator-
A simple calculator application built using Python.

# Absolute Beginner Calculator

# Step 1: User se input lena
num1 = float(input("Pehla number likhein: "))
operator = input("Sign dalein (+, -, *, /): ")
num2 = float(input("Doosra number likhein: "))

# Step 2: Calculation karna
if operator == "+":
    print("Result:", num1 + num2)
elif operator == "-":
    print("Result:", num1 - num2)
elif operator == "*":
    print("Result:", num1 * num2)
elif operator == "/":
    print("Result:", num1 / num2)
else:
    print("Galat sign dala hai!")
