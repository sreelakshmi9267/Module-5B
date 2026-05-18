# 🧪 Pandas Program: Join Two DataFrames Along Rows

## 🎯 AIM

To write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.

---

## 🧠 ALGORITHM

1. **Import Libraries**: Import the `pandas` library.
2. **Create First DataFrame**: Use a dictionary to create `student_data1`.
3. **Create Second DataFrame**: Use another dictionary to create `student_data2`.
4. **Concatenate DataFrames**: Use `pd.concat()` with `axis=0` to concatenate both DataFrames row-wise.
5. **Display Result**: Print the new combined DataFrame.

---

## 💻 Program
```
import pandas as pd 
d1 = pd.DataFrame(eval(input()))
d2 = pd.DataFrame(eval(input()))
print("Original DataFrames:")
print(d1)
print("-------------------------------------")
print(d2)
print("\nJoin the said two dataframes along columns:")
result = pd.concat([d1,d2],axis=1)
print(result)
```
## Output
<img width="1417" height="747" alt="Screenshot 2026-05-18 191253" src="https://github.com/user-attachments/assets/f17df1b0-dd7e-4553-87e0-9d4d79a4a022" />

## Result
Thus, the program has been executed successfully.

