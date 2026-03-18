# 🔄 Hackerrank : # Star Pattern Printer
## 🎯 Aim

To write a Python program to construct a star pattern in an increasing and then decreasing order based on the given number n.

## 🧠 Algorithm
1.Start the program.
2.Read an integer n from the user (number of rows for the upper half).
3.Use a for loop from 1 to n:
   Print * repeated i times.
4.Use another for loop from n-1 down to 1:
   Print * repeated i times.
5.End the program.

## 🧪 Program
```
n=int(input())
for i in range(1, n+1):
    print('* ' * i)
for i in range(n-1, 0, -1):
    print('* ' * i)
```
 
## Sample Output

<img width="1187" height="395" alt="image" src="https://github.com/user-attachments/assets/566fa0fb-575e-4613-af22-3eab0f819070" />


## Result
Thus, the python program was successfully executed.
