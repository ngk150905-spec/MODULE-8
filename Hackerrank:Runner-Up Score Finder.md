# 🎓 Hackerrank:Runner-Up Score Finder
## 🎯 Aim
To write a Python program to find the runner-up score (second highest) from a given list of scores.

## 🧠 Algorithm
1. Start the program.
2. Read an integer n (number of scores).
3. Read the list of n integers separated by space.
4. Find the maximum score from the list.
5. Remove all occurrences of the maximum score from the list.
6. Find the maximum score from the remaining list → this will be the runner-up score.
7. Print the runner-up score.
8. Stop.

## 💻  Program
```
n=int(input())
arr=list(map(int, input().split()))
max_score=max(arr)
arr=[x for x in arr if x != max_score]
runner_up=max(arr)
print(runner_up)
```

## Output

<img width="1182" height="231" alt="image" src="https://github.com/user-attachments/assets/fa7129a3-bc02-49ef-98c5-e9bc66c95a89" />


## Result

Thus, the python program was successfully exceuted.
