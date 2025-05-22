## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

# 🎯 Aim: Merge two dictionaries and combine their key-value pairs
```
dict1 = {'a': 1, 'b': 2, 'c': 3}
dict2 = {'b': 20, 'd': 4}

def merge(d1, d2):
    # Step 3: Use unpacking to merge
    merged_dict = {**d1, **d2}
    return merged_dict

result = merge(dict1, dict2)
print("Merged Dictionary:", result)


## Output
Merged Dictionary: {'a': 1, 'b': 20, 'c': 3, 'd': 4}
```
## Result
Thus Merged two dictionaries and combine their key-value pairs.
