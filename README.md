import math #I didn't know why I did import math but just in case xd

#this my calculator programm
first_number = float(input("Enter first number: "))
second_number = float(input("Enter second number: "))

operation = input("Enter operation desired(+;-;*;/): ")

if operation == "+":
    print(f"{first_number+second_number}")
elif operation == "-":
    print(f"{first_number-second_number}")
elif operation == "*":
    print(f"{first_number*second_number}")
elif operation == "/":
    print(f"{first_number/second_number}")
else:
    print("Error: you have made a mistake in selecting the correct operator")
