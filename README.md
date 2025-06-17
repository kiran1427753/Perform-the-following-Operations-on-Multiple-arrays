# Perform-the-following-Operations-on-Multiple-arrays

a))Stack two arrays vertically

import numpy as np

arr1 = np.array([[1, 2, 3], [4, 5, 6]])

arr2 = np.array([[7, 8, 9], [10, 11, 12]])

print("stack two arrays vertically:\n",np.vstack((arr1,arr2)))

O/P:

stack two arrays vertically:

[[ 1 2 3]

[ 4 5 6]

[ 7 8 9]

[10 11 12]]

b.Stack two arrays horizontally

import numpy as np

arr1 = np.array([[1, 2, 3], [4, 5, 6]])

arr2 = np.array([[7, 8, 9], [10, 11, 12]])

print("stack two arrays horizontally:\n",np.hstack((arr1,arr2)))

O/P:

stack two arrays horizontally:

[[ 1 2 3 7 8 9]

[ 4 5 6 10 11 12]]

c))Get the common items between two python numpy arrays

import numpy as np

arr1 = np.array([1, 2, 3, 4, 5])

arr2 = np.array([4, 5, 6, 1, 3])

print("common elements:\n",np.intersect1d(arr1, arr2))

O/P:

common elements:

[1 3 4 5]

d))Remove from one array those items that exist in another

arr1 = [1, 2, 3, 4, 5,6]

arr2 = [2, 4,1]

print([item for item in arr1 if item not in arr2])

O/P:

[3, 5, 6]
