def add(x, y):
    return x + y

def subtract(x, y):
    return x - y

def multiply(x, y):
    return x * y

def divide(x, y):
    if y != 0:
        return x / y
    else:
        return "Cannot divide by zero"

# Main function
def calculator():
    print("Select operation:")
    print("1. Add")
    print("2. Subtract")
    print("3. Multiply")
    print("4. Divide")

  
    operation = input()

    
    if operation == "1" # PERFORM ADDITION
    num1 = float(input("Enter first number: ")
    num2 = float(input("Enter second number: ")
    print(The sum is " + str (int(num1) + int (num2)))
    elif operation == "2": # PERFORM SUBTRCTION
    num1 = input ("Enter first number:")
    num2 = input ("Enter second number:" )
    print ("The difference is " + str(int(num1) - int(num2))
    elif operation == "3": # PERFORM MULTIPLICATION
    num1 = input ("Enter first number:")
    num2 = input ("Enter second number:" )
    print ("The product is " + str(int(num1) * int(num2))
    elif operation == "4": # PERFORM DIVISION
    num1 = input ("Enter first number:")
    num2 = input ("Enter second number:" )
    print ("The result is " + str(int(num1) /  int(num2)))
    elif operation == "5": # PERFORM SQUARE ROOT
      num = int(input (Enter number:))
      print ("The squareroot is %f " %(math.sqrt(num))
      elif operation == "6": # SQUARE A NUMBER
      num = input ("Enter number:"))
      print ("The result is %d " %(pow(num,2))
    else:
        print("Invalid Entry")

# Run the calculator
calculator()
