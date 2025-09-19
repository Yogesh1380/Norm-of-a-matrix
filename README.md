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
# Register No:212224040371
# Developed By: YOGESH D 

# 1-Norm of a Matrix
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,1)
print(result)

# 2-Norm of a Matrix
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,2)
print(f"{result:.2f}")

# Infinity Norm of a Matrix
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,np.inf)
print(f"{result:.2f}")
```

## Output:

### 1-Norm of a Matrix

<img width="1431" height="955" alt="image" src="https://github.com/user-attachments/assets/9d7c8a4c-53dc-4ae9-9bbd-cdddd8acded6" />


### 2-Norm of a Matrix

<img width="1442" height="978" alt="image" src="https://github.com/user-attachments/assets/6eef9db3-75a5-4d59-9047-dc14f04646d3" />


### Infinity Norm of a Matrix

<img width="1443" height="932" alt="image" src="https://github.com/user-attachments/assets/8221ef4a-0aca-49c2-a97f-492ce99dfe9e" />

  
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
