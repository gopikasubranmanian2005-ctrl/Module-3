# Exp.No:3b  
## REGEX - PATTERN MATCHING USING REGEX

---

### AIM  
To write a Python program that matches a string containing an `'a'` followed by **two to three `'b'` characters** using regular expressions.

---

### ALGORITHM

1. Begin the program.  
2. Accept a string `str1` from the user.  
3. Define the regular expression pattern as `r"[a]+b{2,3}"`.  
4. Use the `re.match()` function to check if the string `str1` matches the pattern.  
5. If a match is found, print `"Found a match!"`.  
6. If no match is found, print `"Not matched!"`.  
7. Terminate the program.

---

### PROGRAM

```
import re
def text_match(text):
    patterns = 'ab{2,3}?'
    if re.search(patterns,text):
        print("Found a match!")
    else:
        print("Not matched!")
x=input()  
text_match(x)

```
### OUTPUT
![image](https://github.com/user-attachments/assets/5be04416-70fa-47b8-a066-89fe76bcb425)

### RESULT
Thus the Python program that matches a string containing an `'a'` followed by **two to three `'b'` characters** using regular expressions is successfully implemented and executed.
