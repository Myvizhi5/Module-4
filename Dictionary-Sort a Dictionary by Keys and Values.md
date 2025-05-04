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
data = {'banana': 'yellow', 'apple': 'red', 'cherry': 'dark red', 'mango': 'orange'}

sorted_by_keys = dict(sorted(data.items()))
sorted_by_values = dict(sorted(data.items(), key=lambda item: item[1]))

print("Sorted by keys:", sorted_by_keys)
print("Sorted by values:", sorted_by_values)
```

## Sample Output
```
Sorted by keys: {'apple': 'red', 'banana': 'yellow', 'cherry': 'dark red', 'mango': 'orange'}
Sorted by values: {'cherry': 'dark red', 'mango': 'orange', 'apple': 'red', 'banana': 'yellow'}
```
## Result
The program successfully sorts a dictionary's keys in alphabetical order and values in alphabetical order, then prints both sorted versions.
