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
# Register No:
# Developed By:
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



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
norm="{:.2f}".format(ans)
print(norm)




```
## Output:
### 1-Norm of a Matrix

![Screenshot (194)](https://github.com/user-attachments/assets/62e4e4eb-d2d7-409d-ac2c-0e03c943c505)

### 2-Norm of a Matrix

![Screenshot (193)](https://github.com/user-attachments/assets/a8449c07-942b-45c5-9ea2-94d654cbcb6f)

### Infinity Norm of a Matrix
![Screenshot (194)](https://github.com/user-attachments/assets/72f6f0a8-8872-4b95-9046-b28a16aa50b4)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
