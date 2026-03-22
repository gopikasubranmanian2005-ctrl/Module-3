# Exp.No:3e
## SEB - STRING SLICING

---

### AIM  
To write a Python function that accepts a string and forms a new string by reversing the characters from the **4th position to the 10th position** with **alternate characters**, and then prints the new string.

---

### ALGORITHM

1. Begin the program.  
2. Accept a string as input.  
3. Take a slice of the input string from index **2** to **10** (Python uses 0-based indexing, so index 2 refers to the 3rd character, i.e., the 4th character in natural terms).  
4. Reverse the sliced substring.  
5. Extract every second character from the reversed substring using slicing (`[::2]`).  
6. Print the final processed string.  
7. Terminate the program.

---

### PROGRAM

```
def slice(input_str):
    substring = input_str[2:10]
    reversed_substring = substring[::-1][::2]
    print(f"The reversed string is '{reversed_substring}'")
```

### OUTPUT
![image](https://github.com/user-attachments/assets/3b66285f-d48c-439c-86f2-e1869aade232)

### RESULT
Thus the Python function that accepts a string and forms a new string by reversing the characters from the **4th position to the 10th position** with **alternate characters**, and then prints the new string is successfully implemented and executed.
