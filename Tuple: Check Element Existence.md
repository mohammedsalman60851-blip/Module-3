# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
my_tuple = ('a', 'n', 5, 8, 10)

if 'n' in my_tuple:
    print("'n' is present")
else:
    print("'n' is not present")

if 8 in my_tuple:
    print("8 is present")
else:
    print("8 is not present")

## Output
'n' is present
8 is present

## Result
Thus, the Python program successfully checks whether the elements 'n' and 8 exist in the given tuple.
