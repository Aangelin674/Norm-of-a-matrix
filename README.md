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

# 1-Norm of a Matrix
'''
Developed by : ANGELIN GRACY.R
Registration Number : 25007261
'''
import numpy as np
matrix = eval(input())
arr = np.array(matrix)
norm1 = np.linalg.norm(arr,1)
print("{:.2f}".format(norm1))



# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: R.ANGELIN GRACY
RegisterNumber: 25007261
'''
import numpy as np
matrix = eval(input())
arr = np.array(matrix)
result = np.linalg.norm(arr,2)
print("{:.2f}".format(result))



# Infinity Norm of a Matrix

'''
Developed by :ANGELIN GRACY.R
Register Number : 25007261
'''
import numpy as np
matrix = eval(input())
arr = np.array(matrix)
result = np.linalg.norm(arr,np.inf)
print("{:.2f}".format(result))



```
## Output:
### 1-Norm of a Matrix

<img width="1215" height="777" alt="Screenshot 2025-09-30 214806" src="https://github.com/user-attachments/assets/25a1099c-3ac5-4742-8ef5-6bd9645ed446" />


### 2-Norm of a Matrix

<img width="1158" height="775" alt="Screenshot 2025-09-30 214858" src="https://github.com/user-attachments/assets/630624c7-e9c1-4860-844a-ca96d13e4c5d" />


### Infinity Norm of a Matrix


<img width="1222" height="775" alt="Screenshot 2025-09-30 214923" src="https://github.com/user-attachments/assets/f8251dbc-07d9-40a6-a334-84970669ad28" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
