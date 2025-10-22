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
rows = int(input("Number of rows:"))
a = 1

for i in range(1, rows+1):
    for space in range(1, rows-i+1):
        print(" ",end="")
    for j in range(0, i):
        if j==0 or i==0:
            a=1
        else:
            a= a* (i - j)//j
        print(a, end = " ")
    print()
```

## Sample Output
<img width="622" height="472" alt="502879767-b249058d-2cf3-49a1-868b-3b26fa7c73ad" src="https://github.com/user-attachments/assets/47f61e67-48e3-4d6e-a791-28059482f107" />

## Result
Thus the above program executed successfully
