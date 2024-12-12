# Gaussian Elimination

## AIM:
To write a program to find the solution of a matrix using Gaussian Elimination.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Input mtrix dimension and initialize augmented matrix and solution vector.
2. Populate the augmented matrix with the user inputs.
3. Perform Gaussian Elimination to reduce the matrix to upper triangle form, ensuring no division by zero.
4. Back Substitute to compute solution values for the variables
5. Print the solution vector formatted to two decimal places.

## Program:

## Program to find the solution of a matrix using Gaussian Elimination.
## Developed by: VASANTH N 
## RegisterNumber: 24000697

        import numpy as np
        
        import sys
        
        n=int(input())
        
        anp.zeros((n,n+1))
        
        x= np.zeros(n)
        
        for i in range(n):
            for j in range(n+1):
                a[i][j] = float(input())
        for i in range(n):
            if a[1][1] =0.0:
                sys.exit('Divide by zero detected')
            for j in range(i+1,n):
                ratio a[j][1]/a[1][1]
                fork in range(n+1):
                    a[j][k] a[j][k]-ratio*a[i][k]
        x[n-1] = a[n-1][n]/a[n-1][n-1]
        for i in range(n-2,-1,-1):
            x[1]=a[i][n]
            for j in range(i+1,n):
                x[1]=x[1]-a[1][j]*x[j]
            X[i] = x[i]-a[i][j]*x[j]
        for i in range(n):
            print("X34 38.2f "%(1,x[1]), end")



## Output:
![Screenshot 2024-12-12 172056](https://github.com/user-attachments/assets/8efb5d1a-2bf8-438f-ba3b-74ff4b887e6f)


## Result:
Thus the program to find the solution of a matrix using Gaussian Elimination is written and verified using python programming.

