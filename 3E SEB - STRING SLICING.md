# Exp.No:3e
## SEB - JOIN TUPLES WITH SIMILAR INITIAL ELEMENT
---
### AIM  
To write a Python program to join tuples if they have a similar initial element.

---
### ALGORITHM
1. Begin the program.  
2. Accept a tuple of tuples as input using `eval()`.  
3. Create an empty dictionary to group tuples by their first element.  
4. Iterate through each tuple in the input:  
   - If the first element already exists as a key, extend its value with the remaining elements.  
   - Otherwise, create a new key with the first element and store the remaining elements.  
5. Convert the dictionary back into a tuple of tuples.  
6. Print the original tuple and the joined tuple.  
7. Terminate the program.

---
### PROGRAM
```python
# Reg.No- 212222060100
# Name- Jothivanan T
t = eval(input())
print("Initially the tuple is :", t)
d = {}
for item in t:
    if item[0] in d:
        d[item[0]] += item[1:]
    else:
        d[item[0]] = list(item)
result = tuple(tuple(v) for v in d.values())
print("Joined tuple :", result)
```

### OUTPUT
<img width="1340" height="157" alt="image" src="https://github.com/user-attachments/assets/75ec18ec-1a7a-4790-8b19-1a62ae2b6c74" />


### RESULT
Thus, the Python program to join tuples with similar initial elements has been successfully executed and the output is verified.
