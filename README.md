# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No: 212223230226
# Developed By: T.Thrinesh Royal
# 1-Norm of a Matrix

import numpy as np
value = eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))

# 2-Norm of a Matrix

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))

# Infinity Norm of a Matrix

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))
```
## Output:
### 1-Norm of a Matrix
![Screenshot 2023-12-25 132706](https://github.com/Thrineshroyal/Norm-of-a-matrix/assets/145741928/034da1dc-18dc-4d8a-a764-b6c86b99b54b)

### 2-Norm of a Matrix
![Screenshot 2023-12-25 132720](https://github.com/Thrineshroyal/Norm-of-a-matrix/assets/145741928/42386851-7ad2-4d47-909c-0629d9c323b3)

### Infinity Norm of a Matrix
![Screenshot 2023-12-25 132730](https://github.com/Thrineshroyal/Norm-of-a-matrix/assets/145741928/cf0cc75a-4538-426a-af7b-75dc372b318c)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
