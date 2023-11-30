# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
```
''' 
Program to mark the maximum of marks using the list method sort
Developed by: VIJAY R
RegisterNumber: 23013759
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```
''' 
Program to find the maximum marks using the list method max().
Developed by: VIJAY R
RegisterNumber: 23013759
'''
def max_marks(marks):
    large=max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by: VIJAY R
RegisterNumber: 23013759
'''
def max_marks(list1):
    max=list1[0]
    for number in list1:
        if(number>max):
            max=number
    return max    



```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
1.![Screenshot 2023-12-01 005405](https://github.com/vijayr21/FindMaximum/assets/149347607/f8d78023-fd93-4966-bf92-6bb1266271dd)
2.![Screenshot 2023-12-01 005648](https://github.com/vijayr21/FindMaximum/assets/149347607/d49af7b0-303d-47e4-b3a4-ef3926a4a37e)
3.![Screenshot 2023-12-01 005704](https://github.com/vijayr21/FindMaximum/assets/149347607/9c02a491-16bf-488e-a858-bb0de03168b1)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
