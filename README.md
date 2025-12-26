# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program

```
num=[1,2,3,4,5,6,7,8,9,10]
total=sum(num)
print("The sum of the numbers in the list is:", total)
```

## Output
<img width="1920" height="1080" alt="Screenshot (121)" src="https://github.com/user-attachments/assets/537ef0d8-0833-4de7-b7ae-606791ecad29" />

## Result
Thus, the program is executed successfully.
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
