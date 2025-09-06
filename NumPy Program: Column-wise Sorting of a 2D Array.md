# NumPy Program: Column-wise Sorting of a 2D Array

## Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## Program
```
import numpy as np
arr=np.array(eval(input()))
print("Given array")
print(arr)
print()
print(np.sort(arr,axis=0))
```
## Output
<img width="610" height="439" alt="image" src="https://github.com/user-attachments/assets/0644aad9-3f74-4375-97fb-eb9c5ff33f18" />


## Result
Thus, the program to sort a 2D NumPy array column-wise was executed successfully.
