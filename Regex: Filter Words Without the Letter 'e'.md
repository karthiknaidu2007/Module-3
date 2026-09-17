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
items=['goal', 'new', 'user', 'sit', 'eat', 'dinner']
result=[a for a in items if 'e' not in a]
print(result)
```
## Output
<img width="852" height="173" alt="image" src="https://github.com/user-attachments/assets/55bab81b-5ae5-4415-81db-bdb2232d17f0" />


## Result
The Python program was successfully executed to filter words from a list that do not contain the letter 'e' using regular expressions.
