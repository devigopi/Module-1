## Experiment No: 1d – Conditional Statements- Checking the year is leap year or not

## AIM  
To Write a python program to compute whether a given year is leap year or not.
## ALGORITHM  
1. Begin the program.  
2.Read the year from the user.
3.Check the following conditions:
    If the year is divisible by 400, it is a leap year.
    Else if the year is divisible by 100, it is not a leap year.
    Else if the year is divisible by 4, it is a leap year.
    Otherwise, it is not a leap year.
4.Display whether the year is a leap year or not.
5.End the program.

## PROGRAM
```python
# Reg.No-212223020028
# Name-Tharani devi.G
# Write your code here
year=int(input())
if((year%4==0)and(year%100!=0)or(year%400==0)):
    print("Given year {} is a leap year".format(year))
    
else:
    print("Given year {} is not a leap year".format(year))
```
## OUTPUT
<img width="1132" height="222" alt="image" src="https://github.com/user-attachments/assets/beef0427-6658-47d1-854f-49b3e7a26c3c" />



## RESULT
This program to check whether the given year is vowel or not using if..else statement is successfully executed.
