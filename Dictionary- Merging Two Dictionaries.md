## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```
import math
class cse:
    def mech(self, r):
        area = math.pi * r * r
        return area
radius = float(input("Enter the radius of the circle: "))
obj = cse()
result = obj.mech(radius)

print("Area of the circle is:", result)
```

## Output

<img width="548" height="252" alt="image" src="https://github.com/user-attachments/assets/9d3003bf-9009-49d2-a8de-8f4ac4be37f9" />

## Result
If the user enters a radius, the program calculates the area using
