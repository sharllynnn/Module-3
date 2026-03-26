# Exp.No:3a
## STRING - PALINDROME CHECK
---
### AIM  
To write a Python program to check whether an entered string is a palindrome or not without using built-in functions.

---
### ALGORITHM
1. Begin the program.  
2. Input the string `s` from the user.  
3. Find the length of the string using `len()`.  
4. Compare characters from the beginning and end of the string moving towards the center.  
5. If all corresponding characters match, print `"The entered string is palindrome"`.  
6. Otherwise, print `"The entered string is not palindrome"`.  
7. Terminate the program.

---
### PROGRAM
```python
# Reg.No- 212222060100
# Name- Jothivanan T
s = input()
n = len(s)
is_palindrome = True
for i in range(n // 2):
    if s[i] != s[n - 1 - i]:
        is_palindrome = False
        break
if is_palindrome:
    print("The entered string is palindrome")
else:
    print("The entered string is not palindrome")
```

### OUTPUT
<img width="856" height="200" alt="image" src="https://github.com/user-attachments/assets/ba8441e3-4b2d-46a6-a2ef-4341fc784623" />


### RESULT
Thus, the Python program to check whether an entered string is a palindrome or not without using built-in functions has been successfully executed and the output is verified.
