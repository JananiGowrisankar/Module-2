# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program
```
a=16
print(bin(a))
```

## Output

![image](https://github.com/user-attachments/assets/71ff9c85-c395-4d74-8b26-974892843dd7)


## Result
Thus a Python program to convert the number **16** into its **binary representation** using built-in Python functions is successfully verified.
# Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program
```
def result(a,b):
    c=a%b
    print(c)
a=int(input("Enter a number"))
b=int(input("Enter a number"))
result(a,b)
```

## Output

![image](https://github.com/user-attachments/assets/644fd69e-b6b9-40dd-aa66-a217dbb22bf6)

## Result
Thus a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator is successfully verified.

# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
```
a = int(input("Enter the first number: "))
b = int(input("Enter the second number: "))

f = lambda x, y: x + y

result = f(a, b)
print("The sum is:", result)

```

## Output

![image](https://github.com/user-attachments/assets/95ef836f-f630-44a3-86f9-0e3a0e29c9bf)


## Result
Thus a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum is successfully verified.

# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
```
import math
rows = int(input("Enter the number of rows: "))
for n in range(rows):
    print(" " * (rows - n), end="")
    for k in range(n + 1):
        value = math.comb(n, k)
        print(f"{value} ", end="")
    print()

```

## Sample Output

![image](https://github.com/user-attachments/assets/e343b8fc-2bfa-46e6-a8b5-636815e24152)


## Result
Thus a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user is successfully verified.

## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
```

num = int(input("Enter a number: "))
temp = num
rev = 0
while temp > 0:
    rev = (10 * rev) + (temp % 10)
    temp = temp // 10

if rev == num:
    print("The number is a palindrome.")
else:
    print("The number is not a palindrome.")

```
## Output

![image](https://github.com/user-attachments/assets/a8c43714-6df2-40eb-ba14-9f5b02ca587a)

![image](https://github.com/user-attachments/assets/13f1fbbd-e47a-4e6c-ab72-83234e08a4d0)


## Result
Thus a Python program that checks whether a given number is a **palindrome** using loops is successfully verified.
