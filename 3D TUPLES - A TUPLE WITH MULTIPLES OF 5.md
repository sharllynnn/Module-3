# Exp.No:3d  
## TUPLES - A TUPLE WITH MULTIPLES OF 5
---
### AIM  
To write a Python program to create a tuple containing all multiples of 5 up to a given number N.

---
### ALGORITHM
1. Begin the program.  
2. Accept an integer `N` from the user.  
3. Use a generator expression inside the `tuple()` function to create a tuple `multiples_of_5` with values starting from `5` up to `N - 1`, stepping by `5`.  
4. Print the resulting tuple.  
5. Terminate the program.

---
### PROGRAM
```python
# Reg.No- 212222060100
# Name- Jothivadan T
N = int(input())
multiples_of_5 = tuple(i for i in range(5, N, 5))
print(multiples_of_5)
```

### OUTPUT
<img width="778" height="197" alt="image" src="https://github.com/user-attachments/assets/9f77b019-967c-46c0-9653-bede10cadcac" />


### RESULT
Thus, the Python program to create a tuple containing all multiples of 5 up to a given number N has been successfully executed and the output is verified.
