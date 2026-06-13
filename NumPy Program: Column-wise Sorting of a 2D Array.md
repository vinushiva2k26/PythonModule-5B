# NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾Program

```python
import numpy as np

arr = np.array([[9, 3, 5],
                [4, 8, 1],
                [7, 2, 6]])

sorted_arr = np.sort(arr, axis=0)

print("Original Array:")
print(arr)

print("Column-wise Sorted Array:")
print(sorted_arr)
```

## Output

```text
Original Array:
[[9 3 5]
 [4 8 1]
 [7 2 6]]

Column-wise Sorted Array:
[[4 2 1]
 [7 3 5]
 [9 8 6]]
```

## Result

Thus, the NumPy program was successfully executed to sort the elements of a 2D array column-wise in ascending order.
