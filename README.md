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
#Program to find the square root for the given number(newton's method) using function.
#Developed by: R.Sabarinath
#RegisterNumber:  212223100048
def newton_method(number,num_iters=100):
    a = float(number)
    for i in range(num_iters):
        number = 0.5 * (number + a/number)
    return number
a = int(input())
print("Square root of the number:",newton_method(a))
```

## Output:
<img width="619" alt="EXP 05" src="https://github.com/Sabari-2005/Square-root-of-a-number/assets/139338709/573ace9e-eeff-4b8e-b7dd-5b094796e35a">

## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
