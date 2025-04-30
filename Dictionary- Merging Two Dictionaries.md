## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

Add code here
```
def merge_dicts(dict1, dict2):
    """Merge two dictionaries, overwriting values from dict1 with dict2 if keys overlap."""
    merged_dict = dict1.copy()
    merged_dict.update(dict2)
    return merged_dict

dict1 = {'Ten': 10, 'Twenty': 20, 'Thirty': 30}
dict2 = {'Thirty': 30, 'Fourty': 40, 'Fifty': 50}

merged_dict = merge_dicts(dict1, dict2)

input1 = eval(input())
input2 = eval(input())
merged_input = merge_dicts(input1, input2)
print( merged_input)


```

## Output
![image](https://github.com/user-attachments/assets/cd20ad66-2ff2-4f31-af22-3febb9f4d3cc)

## Result
The expected output is achieved.
