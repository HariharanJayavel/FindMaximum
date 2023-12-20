# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Step1:
Get the list of marks as input
## Step2:
Use the sort() function or max() function or use the for loop to find the maximum mark.
## Step3:
Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
# Program to mark the maximum of marks using the list method sort
# Developed by: HARIHARAN J
# RegisterNumber: 23011967
```
def max_marks(marks):
    marks.sort()
    return marks[-1]
```

ii)	# To find the maximum marks using the list method max().
# Program to find the maximum marks using the list method max().
# Developed by:HARIHARAN J 
# RegisterNumber: 23011967
```
def max_marks(marks):
    return max(marks)
```
iii) # To find the maximum marks without using builtin functions.
# Program to the maximum marks without using builtin functions
# Developed by:HARIHARAN J 
# RegisterNumber: 23011967
```
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
```
## Output:

Program to mark the maximum of marks using the list method sort

![Screenshot 2023-12-20 203943](https://github.com/HariharanJayavel/FindMaximum/assets/144870546/1f8d6a53-7383-4bc3-98f6-9c834c7fa7ed)

Program to find the maximum marks using the list method max()

![Screenshot 2023-12-20 204041](https://github.com/HariharanJayavel/FindMaximum/assets/144870546/06c8e1e4-f75d-4fb6-aa30-4caa90f38d03)

Program to the maximum marks without using builtin functions

![Screenshot 2023-12-20 204101](https://github.com/HariharanJayavel/FindMaximum/assets/144870546/996a6c54-479e-4ab9-a351-d809728de465)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
