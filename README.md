# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
```
'''to find the square root for the given number using newton's method
Developed by : Sana Fathima H
Register number: 212223240145
'''
n=int(input())
approx=0.5*n
for i in range(1,n+1):
    b=0.5*(approx+(n/approx))
    approx=b
print("Square root of the number:",b)
```

## Output:
![image](https://github.com/Sanafathima95773/Square-root-of-a-number/assets/147084627/66a5bb17-1fd1-4470-b4e7-fe7a72218f67)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
