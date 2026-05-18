# NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾 Program
```
import numpy as np
l= eval(input())
print("Given array")
a=np.array(l)
print('',a)
print()
a=np.sort(a)
print(a)
```
## Output
<img width="639" height="469" alt="Screenshot 2026-05-18 190554" src="https://github.com/user-attachments/assets/dba6b2c0-8530-407a-a401-9d413970c3c8" />

## Result
Thus, the program has been executed successfully.


