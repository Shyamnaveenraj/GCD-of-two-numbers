# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
```
/*
Program to find the gcd of two number using function.
Developed by:Shyam Naveen Raj.M 
RegisterNumber:21005660 
*/def hcf(a, b):
    if(b == 0):
        return a
    else:
        return hcf(b, a % b)
  
a = int(input())
b = int(input())

print("GCD of two numbers is: ", hcf(a,b))
```

## Output:
![gcd of two number](gcd.PNG)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
