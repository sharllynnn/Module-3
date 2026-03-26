# Exp.No:3b  
## REGEX - PATTERN MATCHING USING REGEX
---
### AIM  
To write a Python program that matches a string that begins with "a" followed by zero or more b's using regular expressions.

---
### ALGORITHM
1. Begin the program.  
2. Accept a string `str1` from the user.  
3. Define the regular expression pattern as `r"^ab*$"`.  
4. Use the `re.match()` function to check if the string `str1` matches the pattern.  
5. If a match is found, print `"Found a match!"`.  
6. If no match is found, print `"Not matched!"`.  
7. Terminate the program.

---
### PROGRAM
```python
# Reg.No- 212222060100
# Name- Jothivanan T
import re
str1 = input()
if re.match(r"^ab*$", str1):
    print("Found a match!")
else:
    print("Not matched!")
```

### OUTPUT
<img width="684" height="276" alt="image" src="https://github.com/user-attachments/assets/832989e4-6540-43fd-bf93-9263ceacede2" />


### RESULT
Thus, the Python program that matches a string beginning with "a" followed by zero or more b's using regular expressions has been successfully executed and the output is verified.
