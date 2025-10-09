# Unit_3-class-work-Assignment
Class Assignment for Python Code


**Created a Simple Calculation Program using Python**

```Python
def add(a, b):
    return a + b

def sub(a, b):
    return a - b

def mul(a, b):
    return a * b

def div(a, b):
    return a / b

print("1 for Addition, 2 for Subtraction, 3 for Multiplication, 4 for Division")
choice = input("Enter your choice (1/2/3/4): ")

a = float(input("Enter the value of a: "))
b = float(input("Enter the value of b: "))

if choice == '1':
    print("Result:", add(a, b))
elif choice == '2':
    print("Result:", sub(a, b))
elif choice == '3':
    print("Result:", mul(a, b))
elif choice == '4':
    if b != 0:
        print("Result:", div(a, b))
    else:
        print("Error: Division by zero is not allowed.")
else:
    print("Invalid choice")

    


```
