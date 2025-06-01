## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```
dict1 = {'a': 100, 'b': 200, 'c': 300}
dict2 = {'b': 250, 'd': 400}
def merge(d1, d2):
    merged_dict = {**d1, **d2} 
    return merged_dict
result = merge(dict1, dict2)
print("Merged Dictionary:", result)
```
## Output
![Screenshot 2025-05-01 200438](https://github.com/user-attachments/assets/687ff88d-d382-4f1f-b092-b834432ce22c)

## Result
Thus,the python program Code Execution Successful
