# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```
list1 = [10, 20, 30, 40]
try:
    print("Accessing index 5...")
    value = list1[5] 
    print("Value at index 5:", value)

except IndexError:
    print("You're out of list range")
print("Program continues after handling the error.")
```
## Output
![Screenshot 2025-05-01 205039](https://github.com/user-attachments/assets/93507326-2431-4411-acba-2af905ef6b96)

## Result
Thus,the python program Code Execution Successful
