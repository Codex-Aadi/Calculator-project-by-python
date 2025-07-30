# Calculator-project-by-python
I have made this simple calculator project for my leaning using basic functions and statements
# STEP 1 - CREATE FUNCTIONS To make Calculator

# Functions to add two Functions
def add(num1,num2):
  return num1 + num2

# functions to subtract
def subtract(num1,num2):
  return num1 - num2

# functions to multiply
def multiply (num1,num2):
  return num1 * num2

# functions to divide
def divide(num1,num2):
  return num1 / num2

# function to average
def average (num1,num2):
  return (num1 + num2) / 2

# Step 2 - user inputprint("Select an operation:\n" \
# Step 2 - user input
print("Select an operation:\n" \
        "1. Add\n" \
        "2. Subtract\n" \
        "3. Multiply\n" \
        "4. Divide\n" \
        "5. Average\n")

select = int(input("Select operations from 1,2,3,4,5: "))

number1 = int(input("Enter first number: "))
number2 = int(input("Enter second number: "))

# Step 3 - conditional statements

if select == 1:
  print(number1, "+", number2, "= ", add(number1, number2))

elif select == 2:
  print(number1, "-", number2, "= ", subtract(number1, number2))

elif select == 3:
  print(number1, "*", number2, "= ", multiply(number1, number2))

elif select == 4:
  print(number1, "/", number2, "= ", divide(number1, number2))

elif select == 5:
  print("(",number1, "+", number2, ")", "/", "2", "=", average(number1, number2))

else:
  print("Invalid input")
