# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
```
def sort_dict_by_key(input_dict):
    sorted_items = sorted(input_dict.items())
    
    print("Keys and Values sorted in alphabetical order by the key")
    for item in sorted_items:
        print(item, end=" ")
    print()

data = {2: 56, 1: 2, 5: 12, 4: 24, 6: 18, 3: 323}
sort_dict_by_key(data)
```
## Sample Output
![image](https://github.com/user-attachments/assets/8af16d5b-a030-4457-8366-31c7d4bcf43a)

## Result
The expected output is Achieved.

