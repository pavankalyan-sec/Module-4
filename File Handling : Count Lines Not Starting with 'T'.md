# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
~~~
def count_non_T_lines(filename):
    count = 0
    with open(filename, 'r') as file:
        for line in file:
            if not line.lstrip().startswith('T'):
                count += 1
    print(f"Number of lines not starting with 'T': {count}")

count_non_T_lines('story.txt')
~~~

## Output
<img width="464" height="106" alt="image" src="https://github.com/user-attachments/assets/eb94b697-182b-4beb-bb70-955b1b20bcab" />

## Result
Thus, the program has been executed successfully.
