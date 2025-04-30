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
Add Code Here
```
import math
rows = int(input("Enter the number of rows: "))
for n in range(rows):
    print(" " * (rows - n - 1), end="")  # Printing leading spaces for formatting
    for k in range(n + 1):
        value = math.comb(n, k)  # Using math.comb for binomial coefficient calculation
        print(value, end=" ")  # Print the value with a space between them
    print()
```
## Sample Output
![Screenshot 2025-04-30 114245](https://github.com/user-attachments/assets/00c4c557-94b8-49db-8192-e671482ca5d9)
## Result
The code executed successfully.

