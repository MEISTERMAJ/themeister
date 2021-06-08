
from functions import *

print("Which calculations do want to do?")
print("1 Division")
print("2 Subtraction")
print("3 Addition")
print("4 Multiplication")

choice = input("Enter your choice : ")

num1 = float(input("Enter the Number 1 : "))
num2 = float(input("Enter the Number 2 : "))

if choice == '1':
    division(num1, num2)
elif choice == '2':
    subtraction(num1, num2)
elif choice == '3':
    addition(num1, num2)
elif choice == '4':
    multiplication(num1, num2)
else:
    print("Invalid Choice")
