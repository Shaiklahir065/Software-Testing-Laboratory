# Ex.No: 2   Matrix Multiplication 

### DATE: 10/04/2025
### NAME: SHAIK LAHIR
### REGISTER NUMBER : 212224240148

### AIM: 
Write a python program for matrix multiplication and inspect for failures.
 
### Algorithm:

Algorithm:
1. Start the program.
2. Create empty list formatrix1, matrix2 and result.
3. Get the rows and columns count from the user.
4. Get the values of two matrix.
5. Perform matrix multiplication and store the answer in result.
6. Stop the program.
### Program:
    r1,c1=input("enter row and column count in matrix 1: ").split()
    r2,c2=input("enter row and column count in matrix 2: ").split()
    matrix1=[ ]
    matrix2=[ ]
    result=[ ]
    if(r1.isnumeric() and c1.isnumeric() and r2.isnumeric() and c2.isnumeric()):
    r1=int(r1)
    r2=int(r2)
    c1=int(c1)
    c2=int(c2)
    if(c1!=r2):
    print("Matrix multiplication not possible")
    elif (max(r1,c1,r2,c2)>20 or min(r1,c1,r2,c2)==0):
    print("Matrix multiplication not possible")
    else:
    for i in range(r1):
    a=[]
    for j in range(c1):
    a.append(int(input("<-")))
    matrix1.append(a)
    for i in range(r2): a=[]
    for j in range(c2):
    a.append(int(input("<-")))
    matrix2.append(a)
    for i in range(r1):
    inter=[]
    for j in range(c2):
    sum=0
    for k in range(r2):
    sum += matrix1[i][k] * matrix2[k][j]
    inter.append(sum)
    result.append(inter)
    for i in range(r1):
    for j in range(c2):
    print(result[i][j],end=" ")
    print()
    else:
    print("enter a valid number")


### Output:
1)
                Enter row and column count in matrix 1: 220 550
                Enter row and column count in matrix 2: 100 111
                Matrix multiplication not possible

reason to fail:​Matrix multiplication requires that the number of columns in the first matrix equals the number of rows in the second. In your case, the first matrix has 550 columns, while the second has 100 rows, so multiplication is not possible


2) 
                   Enter row and column count in matrix 1: p q
                   Enter row and column count in matrix 2: r s
                   Enter a valid number

reason to fail:​Matrix multiplication requires the number of columns in the first matrix to equal the number of rows in the second; here, non-numeric inputs ('p', 'q', 'r', 's') prevent this verification. 

3)
                Enter row and column count in matrix 1: 2 5
                Enter row and column count in matrix 2: 5 3
                Enter elements for Matrix 1:
                Element [1][1]:

not failed :


4)
               Enter row and column count in matrix 1: 50 20
               Enter row and column count in matrix 2: 30 70
               Matrix multiplication not possible

reason to fail:Matrix multiplication requires that the number of columns in the first matrix equals the number of rows in the second. Here, Matrix 1 has 20 columns, and Matrix 2 has 30 rows, so multiplication is not possible. 


 5)
           Enter row and column count in matrix 1: 480 350
           Enter row and column count in matrix 2: 220 500
           Matrix multiplication not possible

reason to fail:​Matrix multiplication requires that the number of columns in the first matrix equals the number of rows in the second matrix. Here, Matrix 1 has 350 columns, and Matrix 2 has 220 rows, so multiplication is not possible.


### Result:
Thus, the python program for matrix multiplication is implemented and the causes for its failure is introspected successfully.

