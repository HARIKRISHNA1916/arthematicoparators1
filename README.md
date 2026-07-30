# Program to calculate area and perimeter of a rectangle

length = float(input("Enter the length: "))
width = float(input("Enter the width: "))

# Arithmetic operations
area = length * width
perimeter = 2 * (length + width)

# Additional arithmetic operators
remainder = length % width
power = length ** 2

print("\n--- Rectangle Details ---")
print("Area =", area)
print("Perimeter =", perimeter)
print("Length % Width =", remainder)
print("Length squared =", power)


# Function to compare two numbers

def compare_numbers(num1, num2):
    print("\nComparison Results")

    print("num1 > num2 :", num1 > num2)
    print("num1 < num2 :", num1 < num2)
    print("num1 == num2:", num1 == num2)
    print("num1 != num2:", num1 != num2)
    print("num1 >= num2:", num1 >= num2)
    print("num1 <= num2:", num1 <= num2)

    if num1 > num2:
        print(num1, "is larger than", num2)
    elif num1 < num2:
        print(num2, "is larger than", num1)
    else:
        print("Both numbers are equal.")

a = float(input("Enter first number: "))
b = float(input("Enter second number: "))

compare_numbers(a, b)





# Program using logical operators

number = int(input("Enter a number: "))
text = input("Enter a string: ")

# and operator
if number >= 10 and number <= 50:
    print("Number is between 10 and 50.")
else:
    print("Number is outside the range.")

# or operator
if number < 0 or number > 100:
    print("Number is either less than 0 or greater than 100.")

# not operator
if not text == "Python":
    print("The string is not 'Python'.")
else:
    print("The string is 'Python'.")


    # Demonstration of assignment operators

x = 10

print("Initial value:", x)

x += 5
print("After += :", x)

x -= 3
print("After -= :", x)

x *= 2
print("After *= :", x)

x /= 4
print("After /= :", x)

x %= 3
print("After %= :", x)

x **= 2
print("After **= :", x)



# Identity operators

list1 = [10, 20, 30]
list2 = list1
list3 = [10, 20, 30]

print("list1 is list2 :", list1 is list2)
print("list1 is list3 :", list1 is list3)
print("list1 is not list3 :", list1 is not list3)

# Membership operators

numbers = [10, 20, 30, 40, 50]

value = int(input("Enter a number: "))

if value in numbers:
    print(value, "is present in the list.")
else:
    print(value, "is not present in the list.")

word = input("Enter a word: ")

if "Py" in word:
    print("'Py' is found in the word.")
else:
    print("'Py' is not found in the word.")
