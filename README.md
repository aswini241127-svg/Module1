# Conditional Statements in Python: Even or Odd Checker

## 🎯 Aim
To write a Python program to check whether the given number is even or odd using if...else statements.

## 🧠 Algorithm
1. Get an input from the user.
2. Convert the input to an integer and store it in a variable a.
3. Use the modulo operator % to check if a % 2 == 0.
   - If true, print "EVEN".
   - Else, print "ODD".
4. End the program.

## 🧾 Program
a=int(input("Enter a number:"))
if a%2==0:
    print("EVEN")
else:
    print("ODD")
     
## Output
![WhatsApp Image 2025-10-14 at 19 47 55_3eedd69b](https://github.com/user-attachments/assets/eda03e14-a9db-4e38-ae2e-529e80ce7790)

## Result
enter: 8
EVEN

# Ex 1:Datatypes-Boolean Expression Evaluation in Python

## 🎯 Aim
To write a Python program that evaluates and prints the results of boolean and arithmetic expressions involving `True` and `False`.

## 🧠 Algorithm
1. Set variable `a` to the result of the expression `0 == True`.
2. Set variable `b` to the result of the expression `False == False`.
3. Set variable `c` to the result of the expression `True + True`.
4. Set variable `d` to the result of the expression `False + 9`.
5. Print the value of `a` with the label "a is".
6. Print the value of `b` with the label "b is".
7. Print the value of `c` with the label "c:".
8. Print the value of `d` with the label "d:".

## 💻 Program
Add Code here
```
a = (0 == True)
b = (False == False)
c = (True + True)
d = (False + 9)

print("a is", a)
print("b is", b)
print("c:", c)
print("d:", d)
```



## Output
<img width="804" height="230" alt="Screenshot 2025-10-14 194406" src="https://github.com/user-attachments/assets/b7e46a0b-0819-4f99-99dc-7fcb6dff8d83" />

## Result
```
a is False
b is True
c: 2
d: 9
```

# Datatypes-Character Literal in Python

## 🎯 Aim
To write a Python program that prints the characters `'T'` and `'a'` using character literals.

## 🧠 Algorithm
1. Print the character `'T'`.
2. Print the character `'a'`.

## 🧾 Program
```
print('T')
print('a')
```

## Output
![WhatsApp Image 2025-10-14 at 20 00 46_ffaf7bd7](https://github.com/user-attachments/assets/76d70630-b6ed-4602-87bc-439958b8d553)





## Result
The program successfully displays the characters T and a on separate lines on the screen.

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
```
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
```

## Output
<img width="886" height="341" alt="Screenshot 2025-10-14 200706" src="https://github.com/user-attachments/assets/bf733195-c66f-4de9-b9f8-e41b3de42398" />


## Result
Enter the real part: 2
Enter the imaginary part: 3
Complex Number: (2+3j)
Real Part: 2.0
Imaginary Part: 3.0

# Datatypes-Read and Print a String in Python

## 🎯 Aim
To write a Python program to read a string from the user and then print it.

## 🧠 Algorithm
1. Assign a variable named `men_stepped_on_the_moon`.
2. Use `input()` to read a string from the user and store it in the variable.
3. Print the value stored in the variable.

## 🧾 Program
```
men_stepped_on_the_moon = input("Enter a string: ")
print(men_stepped_on_the_moon)
```


## Output
<img width="657" height="147" alt="image" src="https://github.com/user-attachments/assets/2ea4742f-0917-4caf-a139-a238ef7097b0" />



## Result
The program successfully reads a string entered by the user and displays the same string as output.

