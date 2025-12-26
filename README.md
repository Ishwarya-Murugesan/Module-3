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
# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
```
def remove(str):
    n = int(input("Enter the index to remove: "))
    a = ""
    for j in range(len(str)):
        if j != n:
            a += str[j]
    return a

str1 = input("Enter a string: ")
print("Modified string:", remove(str1))
```

## Output
<img width="1920" height="1080" alt="Screenshot (123)" src="https://github.com/user-attachments/assets/02c54741-529f-4015-98a5-993f357932a6" />

## Result
Thus, the program is executed successfully.
# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program

```
str='google'
rev=str[::-1]
if str==rev:
    print("The given string is a palindrome")
else:
    print("The given string is not a palindrome")
```

## Output
<img width="1920" height="1080" alt="Screenshot (124)" src="https://github.com/user-attachments/assets/601ae709-5f62-42bc-bc30-c233b639284b" />

## Result
Thus, the program is executed successfully.
