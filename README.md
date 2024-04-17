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
# Register No: 212223230211
# Developed By: SOWMYA BADONI
# 1-Norm of a Matrix:
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(two_matrix))

# 2-Norm of a Matrix:

import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))

# Infinity Norm of a Matrix:

import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(two_matrix))
```

## Output:
### 1-Norm of a Matrix
![image](https://github.com/sowmya-badoni/Norm-of-a-matrix/assets/152136324/1041c004-cedb-43f6-beb3-856f7fda1c0c)


### 2-Norm of a Matrix
![image](https://github.com/sowmya-badoni/Norm-of-a-matrix/assets/152136324/3748b758-f736-48ed-a80e-239e24e9e5d1)



### Infinity Norm of a Matrix:

![image](https://github.com/sowmya-badoni/Norm-of-a-matrix/assets/152136324/0bda9dda-131e-4c37-95c3-b70dc2e8f1c2)



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.

