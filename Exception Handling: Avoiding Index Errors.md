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
list1 = [10, 20, 30]

try:
    print(list1[5])
    print("Index access successful")
except IndexError:
    print("You're out of list range")

```

## Output
<img width="424" height="157" alt="image" src="https://github.com/user-attachments/assets/8f18ed5b-c9ac-41c1-8fb7-92ce85978e78" />

## Result
The given program was executed successfully.
