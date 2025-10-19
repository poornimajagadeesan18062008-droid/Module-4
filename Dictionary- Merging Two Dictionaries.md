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
a={1:"a",2:"b",3:"c"}
b={2:"d",3:"e"}
def merge(a,b):
   print({**a,**b})
merge(a,b)
```

## Output
<img width="1532" height="102" alt="image" src="https://github.com/user-attachments/assets/3234ec76-e89e-41d8-8d54-b446b783db58" />

## Result
Thus,to write a Python program that merges two dictionaries and combines their key-value pairs is executed successfully.
