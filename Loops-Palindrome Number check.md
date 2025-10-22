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
Add code Here
```
num=int(input("Enter a number:"))
temp=num
rev=0
while temp > 0:
    rev = (10 * rev) + temp % 10
    temp = temp // 10
if rev==num:
    print("Palindrome")
else:
    print("Not a Palindrome")
```
## Output

<img width="605" height="283" alt="502880158-221126d8-2e46-488e-ba53-eb7534fe32d0 (1)" src="https://github.com/user-attachments/assets/0b4007d2-8f21-4abe-995d-f5f36508300e" />

## Result
Thus the above program executed successfully.
