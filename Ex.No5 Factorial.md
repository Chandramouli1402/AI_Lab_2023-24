# Ex.No: 5   Logic Programming – Factorial of number   
### DATE:                                                                
### REGISTER NUMBER : 212222040028
### AIM: 
To  write  a logic program for finding the factorial of given number using SWI-PROLOG. 
### Algorithm:
1. STEP 1: Start the program
2. STEP 2:  Write a rules for finding factorial of given program in SWI-PROLOG.
3.   a)	factorial of 0 is 1 => written as factorial(0,1).
4.   b)	factorial of number greater than 0 obtained by recursively calling the factorial    function.
5. STEP 3: Run the program  to find answer of  query.
6. STEP 4: Stop the program.

### Program:
~~~
fact(N,RES):-  
           N > 0, 
           N1 is N-1,
           fact(N1,RES1),
           RES is N*RES1.
fact(0,1).
fact(1,1).
~~~


### Output:
![Screenshot 2025-03-21 154719](https://github.com/user-attachments/assets/b2debdb0-90bf-4ee1-9ce7-6ec2d8bf34a8)




### Result:
Thus the factorial of given number was found by logic programming. 
