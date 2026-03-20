# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
```
a=input()
b=a[::-1]
if a==b:
    print("The entered string is palindrome")
else:
    print("The entered string is not palindrome")
```

## Output
<img width="948" height="157" alt="image" src="https://github.com/user-attachments/assets/9d9f5969-d245-439d-bbbc-04e3cf4ad329" />

## Result
Thus, the Python program to check whether the given string is a palindrome or not is executed successfully.
