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
```Python
''' 
Program to mark the maximum of marks using the list method sort
Developed by: MOHAMED FAROOK S
RegisterNumber: 23014058
'''
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: MOHAMED FAROOK S
RegisterNumber: 23014058
'''
def max_marks(marks):
    large = max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: MOHAMED FAROOK S
RegisterNumber: 23014058
'''
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i>max:
            max = i
    return max


```


## Output:
![image](https://github.com/MOHAMEDFAROOK2005/FindMaximum/assets/150319482/9333fcca-3388-44b1-8e17-2a976e68362a)

![image](https://github.com/MOHAMEDFAROOK2005/FindMaximum/assets/150319482/0f5d4752-aaad-4711-9060-9125f11e23d9)


![image](https://github.com/MOHAMEDFAROOK2005/FindMaximum/assets/150319482/611c723d-22e4-4bc1-8116-c947240d27e1)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
