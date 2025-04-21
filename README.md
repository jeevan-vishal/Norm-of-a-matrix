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
# Register No:212224240062
# Developed By:jeevan ishal
# 1-Norm of a Matrix
```
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

```


# 2-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```

# Infinity Norm of a Matrix

```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))
```

## Output:
### 1-Norm of a Matrix
![Screenshot 2025-04-21 135555](https://github.com/user-attachments/assets/c83ec43a-25cc-4cb5-8ddc-823c1521821c)

### 2-Norm of a Matrix
![Screenshot 2025-04-21 135626](https://github.com/user-attachments/assets/d683055d-c163-4a10-b88c-4de274d74b65)


### Infinity Norm of a Matrix
![Screenshot 2025-04-21 135646](https://github.com/user-attachments/assets/69eb10ec-eb8c-462b-ab8f-4017f510eb47)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
