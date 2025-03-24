# Ex.No: 5   Logic Programming – Factorial of number   
### DATE: 24/03/2025                                                                         
### REGISTER NUMBER : 212223060248
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
```
likes(steve,X):-
     easycourse(X).
hard(sciencecourse).
easycourse(X):-
          course(X,dept(havefun)).
course(bk301,dept(havefun)).
```
### Output:

![Image](https://github.com/user-attachments/assets/5150b6ef-85df-4b0d-8b2a-44778d2bb75f)


### Result:
Thus the factorial of given number was found by logic programming. 
