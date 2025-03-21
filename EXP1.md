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

![Screenshot 2025-03-21 195425](https://github.com/user-attachments/assets/67cc50a8-2624-4df6-95ae-35e664d89b45)

![Screenshot 2025-03-21 195420](https://github.com/user-attachments/assets/fbae12ca-d5e5-4b55-96c9-01f51c459d6c)

![Screenshot 2025-03-21 195413](https://github.com/user-attachments/assets/259e3842-3088-4ff9-9bed-cbe6ce55bca0)


![Screenshot 2025-03-21 195407](https://github.com/user-attachments/assets/8ab96d5b-ee1c-4f6a-acd6-e7ecb2448382)

![Screenshot 2025-03-21 195400](https://github.com/user-attachments/assets/3d393815-fff9-4dfc-af95-3ca4a8ceaaf3)


**while...do

![image](https://github.com/user-attachments/assets/eb01e69a-55db-43b6-8272-ee50cd17ac2c)


![Screenshot 2025-03-21 195649](https://github.com/user-attachments/assets/3ea6dbd3-b94c-45cc-905f-e0fcb6cc837b)


![Screenshot 2025-03-21 195643](https://github.com/user-attachments/assets/af04e218-4913-47d3-9ca9-1c94ce9e0ae0)

![Screenshot 2025-03-21 195638](https://github.com/user-attachments/assets/f2c5e7f0-dffe-4156-884f-1cf13ae1ed5a)

![Screenshot 2025-03-21 195631](https://github.com/user-attachments/assets/263c7131-277c-4728-b3b4-5af5d149fe00)


![Screenshot 2025-03-21 195626](https://github.com/user-attachments/assets/4c297152-a514-4445-8d9b-a8c36381a687)


**switch

![image](https://github.com/user-attachments/assets/428d6eb6-512f-422e-8b4d-bb5e1f6262e6)

![Screenshot 2025-03-21 195843](https://github.com/user-attachments/assets/04be84af-7a16-4f6c-9d6a-a711dd7e2e55)

![Screenshot 2025-03-21 195839](https://github.com/user-attachments/assets/9e8b4351-d041-4c22-bcfa-35c6b08ca86c)

![Screenshot 2025-03-21 200044](https://github.com/user-attachments/assets/c4d3a1cf-a51d-4190-b734-b844c4cb2713)

![Screenshot 2025-03-21 195835](https://github.com/user-attachments/assets/30bb663f-7255-49d0-997b-208624ddc501)


**for

![image](https://github.com/user-attachments/assets/9ddb4cbf-a015-40dc-b7e8-d2734f042b3a)

![Screenshot 2025-03-21 200150](https://github.com/user-attachments/assets/0f834f6f-17c8-4284-84b9-2c05754420e8)

![Screenshot 2025-03-21 200146](https://github.com/user-attachments/assets/8ec10069-ef87-490c-8f76-db5d21ae206d)

![Screenshot 2025-03-21 200142](https://github.com/user-attachments/assets/6053cd3a-ad06-4e33-8499-cad7474692cb)

![Screenshot 2025-03-21 200137](https://github.com/user-attachments/assets/21e81967-de08-49a0-8f7a-f6274b9aa491)



**if else

![image](https://github.com/user-attachments/assets/53c5c961-7246-465f-bae0-0e0457ce3e9c)

![Screenshot 2025-03-21 200318](https://github.com/user-attachments/assets/7d5ff227-4cbd-4cbe-920b-1fa183c45e6c)

![Screenshot 2025-03-21 200313](https://github.com/user-attachments/assets/f9548ecd-3702-4f75-af12-87d31e8c16c8)

![Screenshot 2025-03-21 200309](https://github.com/user-attachments/assets/8bbd9689-9346-4593-923d-22dfcb77b450)

![Screenshot 2025-03-21 200304](https://github.com/user-attachments/assets/c30be2fc-cc0c-4b83-9653-848999da2025)


### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


