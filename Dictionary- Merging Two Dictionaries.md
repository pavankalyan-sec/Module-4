## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

dict1 = {'a': 1, 'b': 2}
dict2 = {'c': 3, 'd': 4}
merged_dict = dict1.copy() 
merged_dict.update(dict2)
print("Merged Dictionary:", merged_dict)

## Output
https://private-user-images.githubusercontent.com/203871661/442481750-aad5cc3e-2ed6-479e-8779-a37f27bac877.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NjExODE0MjEsIm5iZiI6MTc2MTE4MTEyMSwicGF0aCI6Ii8yMDM4NzE2NjEvNDQyNDgxNzUwLWFhZDVjYzNlLTJlZDYtNDc5ZS04Nzc5LWEzN2YyN2JhYzg3Ny5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUxMDIzJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MTAyM1QwMDU4NDFaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1jNzNkYWI0Njg3Y2NmOGViMTI4M2I0MGRkZWQ1YTNiN2M4NjA4Nzg3N2IyM2JkMzZlZTk1ODUxYmY3ZDRhZTZhJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.adtAoRqok0WB-MC1-zPuG-_MW0JaKyKhVTZtJ6Jk6Ag
## Result
