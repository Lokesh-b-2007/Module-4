## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
~~~
a=eval(input())
b=eval(input())
c=a.copy()
c.update(b)
print(c)
~~~
## Output
![445227396-5af838d3-b770-4e09-a2e2-245a0691db48](https://github.com/user-attachments/assets/bef48ccc-3fa1-4e1c-af38-772f2fef5222)

## Result
Thus the program executed successfully.
