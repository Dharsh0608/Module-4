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
dict1 = {"a": 1, "b": 2, "c": 3}
dict2 = {"b": 20, "d": 4}

def merge(d1, d2):
    return {**d1, **d2}

result = merge(dict1, dict2)
print(result)
```

## Output:
<img width="512" height="165" alt="image" src="https://github.com/user-attachments/assets/aebfaa2e-9c34-47b1-a192-01da73e512ab" />


## Result
The given program was executed successfully.
