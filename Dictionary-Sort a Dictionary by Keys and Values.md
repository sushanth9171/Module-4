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
a={2:56,1:2,5:12,4:24,6:18,3:323}
b=sorted(a.items(),key=lambda x:x[1])
print(f"Keys and Values sorted in alphabetical order by the value\n{b}")
~~~
## Sample Output
<img width="1456" height="207" alt="530283353-56ff8b3f-a8eb-4e5e-80bc-b5cd1234e2bd" src="https://github.com/user-attachments/assets/b6cde0df-5814-4c37-aee5-4cd252c0f240" />

## Result
Thus,the program has been executed successfully.


