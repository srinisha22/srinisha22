def add(num1, num2):
    return num1+num2
def subtract(num1, num2):
    return num1-num2
def multiply(num1, num2):
    return num1*num2
def divisor(num1, num2):
    if num2==0:
        return "Error: cannot be divided by zero"
    return num1/num2
    
print("Simple Calculator\n" \
       "1.Addition\n" \
       "2.Subtraction\n" \
       "3.Multiplication\n" \
       "4.Division")
choice = int(input("Enter the choice (1/2/3/4): "))    

a = int(input("Enter the value of num1: "))
b = int(input("Enter the value of num2: "))
 
if choice == 1:
    print(a, "+" , b, "=", add(a,b))
elif choice == 2:
    print(a, "-" , b, "=", subtract(a,b))
elif choice == 3:
    print(a, "*" , b, "=", multiply(a,b))
elif choice == 4:
    print(a, "/" , b, "=", divisior(a,b))
else:
    print("Invalid input")
