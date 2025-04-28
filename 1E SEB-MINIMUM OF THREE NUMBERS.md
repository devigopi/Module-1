# Experiment No: 1e – SEB-Minimum of Three Numbers

## AIM  
To write a Python program to find the minimum between three integer numbers using a conditional expression (Ternary operator).

## ALGORITHM  
1. Begin the program.  
2. Read the three numbers: `num1`, `num2`, and `num3` from the user.  
3. Compare `num1`, `num2`, and `num3` to find the smallest number:  
   - If `num1` is less than or equal to both `num2` and `num3`, then `num1` is the minimum.  
   - Else, if `num2` is less than or equal to both `num1` and `num3`, then `num2` is the minimum.  
   - Otherwise, `num3` is the minimum.  
4. Print the minimum value along with the input numbers in the format:  
   `"The minimum of num1, num2, num3 is min_num."`  
5. Terminate the program.

## PROGRAM
```python
# Reg.No-212223020028
# Name-Tharani devi.G
# Write your code here
a=int(input())
b=int(input())
c=int(input())
if b>a and a<c:
    print(f"The minimum of {a}, {b}, {c} is {a}")
elif a>b and b<c:
     print(f"The minimum of {a}, {b}, {c} is {b}")
else:
     print(f"The minimum of {a}, {b}, {c} is {c}")
```
## OUTPUT
![MODULE IE](https://github.com/user-attachments/assets/8eda279a-a3e8-4c32-a3e4-2fdcba143f07)

## RESULT
This program for minimum between three integer numbers using a conditional expression (Ternary operator) is successfully executed.
