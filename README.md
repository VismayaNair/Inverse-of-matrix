# Inverse-of-matrix

## AIM:

## ALGORITHM:
### Step 1:
Use import as np.

### Step 2:
Enter the input.

### Step 3:
Use for loop and range.

### Step 4:
Use np.linalg.inv() to find inver of a matrix.

### Step 5:
Print()

## PROGRAM:
~~~
#Register number:212221230125
#Developed by: Vismaya S
import numpy as np
l1,l2=[],[]
r,c=int(input()),int(input())
for i in range(r):
    for j in range(c):
        num=int(input())
        l1.append(num)
    l2.append(l1)
    l1=[]
print(l2)
value1=np.array(l2)
inverse=np.linalg.inv(value1)
print(inverse)
~~~
## OUTPUT:
![github](inverse.png)
## RESULT:
thus the inverse of the matrix is found.
