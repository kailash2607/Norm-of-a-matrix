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
# Register No: KAILASH PRABHU S
# Developed By: KILASH PRABHU S
# 1-Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
OneNorm=np.linalg.norm(InputArray,1)
print(OneNorm)

# 2-Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
TwoNorm=np.linalg.norm(InputArray,2)
print(f"{TwoNorm:.2f}")


# Infinity Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
InfinityNorm=np.linalg.norm(InputArray,np.inf)
print(InfinityNorm)


```
## Output:
### 1-Norm of a Matrix
<img width="1467" height="972" alt="image" src="https://github.com/user-attachments/assets/9f7e4f38-1db4-4667-8424-b112360347bf" />


### 2-Norm of a Matrix
<img width="1498" height="942" alt="image" src="https://github.com/user-attachments/assets/1a12fb71-7664-4672-9447-7d15b3d5fd75" />


### Infinity Norm of a Matrix
<img width="1515" height="916" alt="image" src="https://github.com/user-attachments/assets/32d8049c-d96f-44b1-a3fc-e2b19c114f73" />
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
