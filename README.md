# 1 Завдання
print("Hello world!")

# 2 Завдання
name = input("Enter the name: ")
print(f"Hello {name}!")

# Завдання 3
a = int(input("Enter the first integer: "))
b = int(input("Enter the second integer: "))
print("Sum:", a + b)
print("Difference:", a - b)
print("Product:", a * b)

# 4 завдання
A = float(input("Enter the length (A): "))
B = float(input("Enter the width (B): "))
C = float(input("Enter the height (C): "))
surface_area = 2 * (A * B + B * C + A * C)
volume = A * B * C
print(f"Surface Area: {surface_area:.2f}")
print(f"Volume: {volume:.2f}")

# 5 завдання
R = float(input("Enter the radius of the circle (R): "))
pi = 3.14
area = pi * R ** 2
circumference = 2 * pi * R
print(f"Circle Area: {area:.2f}")
print(f"Circumference: {circumference:.2f}")

# 6 завдання
P = float(input("Enter the principal amount (P): "))
T = int(input("Enter the time period (T) in years: "))
R = float(input("Enter the interest rate (R) in percentage: "))
I = (P * T * R) / 100
print(f"Simple Interest (float): {I:.2f}")
print(f"Simple Interest (int): {int(I)}")
