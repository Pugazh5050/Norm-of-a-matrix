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
# Register No:212224100047
# Developed By:Pugazhalenthi V

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
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix

<img width="1440" alt="Screenshot 2025-05-13 at 12 50 25 PM" src="https://github.com/user-attachments/assets/98181800-5a7c-4afa-a66b-08e8744ab52f" />


### 2-Norm of a Matrix

![image](https://github.com/user-attachments/assets/3402c0a7-d575-499b-90ea-76f4625f9eb8)


### Infinity Norm of a Matrix

![image](https://github.com/user-attachments/assets/341002f9-8054-43b3-98cb-54231666fffc)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
