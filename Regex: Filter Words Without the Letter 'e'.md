# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
```
import re
items=['goal','new','user','sit','eat','dinner']
filter=[item for item in items if re.match(r'^((?!e).)*$',item)]
print(filter)
```
## Output
<img width="1920" height="1080" alt="Screenshot (122)" src="https://github.com/user-attachments/assets/8fbdf35f-bb08-48db-8049-113eae4d6d82" />

## Result
Thus, the program is executed successfully.
