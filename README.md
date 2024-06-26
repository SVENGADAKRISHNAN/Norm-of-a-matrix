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
```
# Register No:212223110061
# Developed By:S.VENGADA KRISHNAN
# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix
import numpy as np

mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)


# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/SVENGADAKRISHNAN/Norm-of-a-matrix/assets/147473084/f9818637-2c79-474e-af98-2bdc8f745738)



### 2-Norm of a Matrix

![image](https://github.com/SVENGADAKRISHNAN/Norm-of-a-matrix/assets/147473084/a4ba2f06-96ac-478d-9d0f-ca813ab13ed0)


### Infinity Norm of a Matrix
![image](https://github.com/SVENGADAKRISHNAN/Norm-of-a-matrix/assets/147473084/679f77ab-a085-4217-a89a-861d9c901fdd)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
