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
~~~
data = {
    'apple': 3,
    'zebra': 1,
    'banana': 5,
    'cat': 2
}

sorted_by_keys_list = sorted(data.items())
sorted_by_keys_dict = dict(sorted_by_keys_list)

sorted_by_values_list = sorted(data.items(), key=lambda item: item[1])
sorted_by_values_dict = dict(sorted_by_values_list)

print(f"1. Original Dictionary: {data}")

print("\n2. Sorted by Keys (Alphabetical Order):")
print(f"   {sorted_by_keys_dict}")

print("\n3. Sorted by Values (Numerical Order):")
print(f"   {sorted_by_values_dict}")
~~~

## Sample Output
<img width="757" height="467" alt="image" src="https://github.com/user-attachments/assets/fd664d5f-5eae-407f-b785-3b0cbf6dbd41" />

## Result
Thus , the program has been executed successfully.
