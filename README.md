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
# Register No:23005024
# Developed By: thenmozhi.p
### 1-Norm of a Matrix

```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
print("{:.2f}".format(ans))
```
### 2-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
print("{:.2f}".format(ans))
```
### Infinity Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))

```
## Output:

### 1-Norm of a Matrix:

![image](https://github.com/AnnaLahari/Norm-of-a-matrix/assets/149365425/fc2368ec-8b94-43d2-adc3-79e39e1279e4)


### 2-Norm of a Matrix:

![image](https://github.com/AnnaLahari/Norm-of-a-matrix/assets/149365425/4163f0db-09ea-4b63-91b5-1b7a76b6c81e)

### 3-Infinity Norm of a Matrix:

![image](https://github.com/AnnaLahari/Norm-of-a-matrix/assets/149365425/3ebbcadc-ab1a-4772-ad0e-f60c02407d46)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.


