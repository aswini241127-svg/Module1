# 🧮 Datatypes-Complex Number Creation in Python

## 🎯 Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

## 🧠 Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.

## 💻 Program
# Read two integers from the user
x = int(input("Enter the real part: "))
y = int(input("Enter the imaginary part: "))

# Create a complex number using x and y
c = complex(x, y)

# Print the complex number
print("Complex Number:", c)

# Print real and imaginary parts
print("Real Part:", c.real)
print("Imaginary Part:", c.imag)

## Output
<img width="1036" height="400" alt="exp1" src="https://github.com/user-attachments/assets/f12febb2-327f-4aa2-80c2-25445d57777b" />

## Result
Enter the real part: 2 Enter the imaginary part: 3 Complex Number: (2+3j) Real Part: 2.0 Imaginary Part: 3.0
