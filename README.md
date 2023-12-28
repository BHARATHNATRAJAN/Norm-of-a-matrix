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
## Programimport numpy as np

    
Python
# Register No:23003413
# Developed By:N.bharath
# 1-Norm of a Matrix
```
import numpy as np
def calculate_1norm(matrix):
    norm1=np.linalg.norm(matrix,ord=1)
    return round(norm1,2)
matrix=eval(input())
result=calculate_1norm(matrix)
print(f"{result:.2f}")

```
    






# 2-Norm of a Matrix
```
import numpy as np
matrix=eval(input())
norm2=np.linalg.norm(matrix,ord=2)
print(f"{norm2:.2f}")

```



# Infinity Norm of a Matrix
```
import numpy as np
a=eval(input())
norm=np.linalg.norm(a,ord=np.inf)
print(f"{norm:.2f}")

```
## Output:
### 1-Norm of a Matrix:

![output](![Screenshot 2023-12-28 102155](https://github.com/BHARATHNATRAJAN/Norm-of-a-matrix/assets/147473529/664a3d7e-9a9d-415c-a3a7-44bd68ecf146)
)

### 2-Norm of a Matrix:

![output](![Screenshot 2023-12-28 102938](https://github.com/BHARATHNATRAJAN/Norm-of-a-matrix/assets/147473529/55de33b8-9bde-45ee-b8ff-be7bfc56b3bd)
)

### Infinity Norm of a Matrix:

![output](![Screenshot 2023-12-28 103102](https://github.com/BHARATHNATRAJAN/Norm-of-a-matrix/assets/147473529/13e98349-cf21-4960-9f35-3a3931d1b102)
)
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
