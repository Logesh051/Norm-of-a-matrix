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
# Register No:23012242
# Developed By:Logesh.N.A
# 1-Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))

# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix
import numpy as np 
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```
## Output:
### 1-Norm of 
![Screenshot 2023-12-21 222049](https://github.com/Logesh051/Norm-of-a-matrix/assets/144979188/19bcbedf-0e9a-438b-b8c6-03f800038cdd)
a Matrix
<br>
<br>
<br>

### 2-Norm of a Matrix
<br>![Screenshot 2023-12-21 222103](https://github.com/Logesh051/Norm-of-a-matrix/assets/144979188/b0fd2f12-2b48-4e4e-97a9-9a9c549a3e39)

<br>
<br>

### Infinity Norm of a Matrix
<br>![Screenshot 2023-12-21 222112](https://github.com/Logesh051/Norm-of-a-matrix/assets/144979188/ec820701-3753-454c-a884-e7045f16495f)

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
