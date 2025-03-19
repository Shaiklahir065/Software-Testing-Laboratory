# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE:                                                                            
### REGISTER NUMBER : 

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test 
Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.
### Program:
**do...while

    start = input("Enter a positive value for START: ")
    end = input("Enter a positive value for END: ")
    if start.isnumeric() and end.isnumeric():
        start = int(start)
        end = int(end)
        if start < end:
            while start
        
**while...do

    def display():
        while True:
            start = input("Enter a positive value for START: ")
            end = input("Enter a positive value for END: ")
            if start.isnumeric() and end.isnumeric():
                start = int(start)
                end = int(end)
                if start > 0 and end > 0

**switch

    def check_parity():
        switcher = {
            0: "even",
            1: "odd"
        }
        n = input('Enter a value for N: ')
        try:
            n = int(n)
            print(switcher[n % 2])
        except ValueError:
            print("Enter a valid number.")
    check_parity()

**for

    def iterate():
        string = input("Enter a string: ")
        for i in string:
            print(ord(i), end=" ")
    iterate()

**if else

    def compare():
        a = input("Enter a value for A: ")
        b = input("Enter a value for B: ")
        try:
            a = int(a)
            b = int(b)
            if a > b:
                print("A is greater than B")
            elif a < b:
                print("B is greater than A")
            else:
                print("A is equal to B")
        except ValueError:
            print("Enter a valid number.")
    compare()






### Output:
** do...while

![image](https://github.com/user-attachments/assets/566d0cff-5383-45da-b1a7-91e8dc2fb8d5)

**while...do

![image](https://github.com/user-attachments/assets/eb01e69a-55db-43b6-8272-ee50cd17ac2c)

**switch

![image](https://github.com/user-attachments/assets/428d6eb6-512f-422e-8b4d-bb5e1f6262e6)

**for

![image](https://github.com/user-attachments/assets/9ddb4cbf-a015-40dc-b7e8-d2734f042b3a)

**if else

![image](https://github.com/user-attachments/assets/53c5c961-7246-465f-bae0-0e0457ce3e9c)





### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


