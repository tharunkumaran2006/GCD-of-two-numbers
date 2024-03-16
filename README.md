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
//Program to find the gcd of two number using function.
def gcd():
    x=int(input())
    y=int(input())
    if(x<y):
        smaller=x
    else:
        smaller=y
    for i in range(1,smaller+1):
        if(x%i==0 and y%i==0):
            hcf=i
    print("GCD of two numbers is:",hcf)
//Developed by: Tharun V K
//RegisterNumber:212223230231  
```

## Output:
![Screenshot 2024-03-16 105155](https://github.com/tharunkumaran2006/GCD-of-two-numbers/assets/151625188/09a766a9-09d6-4342-933c-de53c59fbdb6)



## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
