# Exp.No:3a
## STRING - FIND AND REPLACE

---

### AIM  
To write a Python function to accept a string, identify a word to be replaced, and replace it with a new word provided by the user.

---

### ALGORITHM

1. Begin the program.  
2. Input the original string `str1` and the word to be replaced `replace_str`.  
3. Ask the user to input the new replacement word `str2`.  
4. Use the `replace()` method in Python to replace all occurrences of `replace_str` in `str1` with `str2`.  
5. Store the modified string in `str3`.  
6. Display the original string (`str1`) and the modified string (`str3`).  
7. Terminate the program.

---

### PROGRAM

```
str=input()
c=input()
count=0
for i in str:
    if c==i:
        count+=1
print("Character {} in the {} is {} times".format(c,str,count))        
```

### OUTPUT
![image](https://github.com/user-attachments/assets/63282305-fd68-4947-8d4a-32988a8d6b45)

### RESULT
Thus the Python function to accept a string, identify a word to be replaced, and replace it with a new word provided by the use is successfully implemented and executed.
