num1 = int(input("Enter the first number: "))
num2 = int(input("Enter the second number: "))

while True:
    rem = num1 % num2
    num1 = num2
    num2 = rem
    if num2 == 0:
        break

print("GCD is:", num1)
