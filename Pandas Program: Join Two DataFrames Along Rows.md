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

student_data1 = pd.DataFrame({
    'student_id': ['S1', 'S2', 'S3'],
    'name': ['Alice', 'Bob', 'Charlie'],
    'marks': [85, 92, 78]
})

student_data2 = pd.DataFrame({
    'student_id': ['S4', 'S5', 'S6'],
    'name': ['David', 'Eve', 'Frank'],
    'marks': [88, 76, 95]
})

combined_data = pd.concat([student_data1, student_data2], axis=0)

print("Combined DataFrame:")
print(combined_data)
```


## Output
<img width="442" height="213" alt="568930083-e4ea0f6a-01ba-4fff-b989-45a7f48d3d9b" src="https://github.com/user-attachments/assets/b5497595-3ed5-4fb7-8a48-86c1564769f9" />

## Result
Thus,the program has been executed successfully.

