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
# Register No: 212224230150
# Developed By: MANIKANDAN K
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_value="{:.2f}".format(ans)
print(norm_value)



# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_value="{:.2f}".format(ans)
print(norm_value)



# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_value="{:.2f}".format(ans)
print(Norm_value)

```
## Output:
### 1-Norm of a Matrix
<br>
<img width="1246" height="891" alt="image" src="https://github.com/user-attachments/assets/b6550b20-5fb8-48ce-a370-0a50f67fd5ec" />

<br>
<br>

### 2-Norm of a Matrix
<br>
<img width="1245" height="943" alt="image" src="https://github.com/user-attachments/assets/98bd83de-ab82-42c6-ade2-8b9469a7e8f3" />

<br>
<br>

### Infinity Norm of a Matrix
<br>
<img width="1258" height="907" alt="image" src="https://github.com/user-attachments/assets/41e81024-c649-443e-b2da-53cbdac61441" />

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
