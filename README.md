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
Developed by: jagadeeshreddy
RegisterNumber: 22001910
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: jagadeeshreddy
RegisterNumber: 22001910
'''
def max_marks(marks):
    large=max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: jagadeeshreddy
RegisterNumber: 22001910
'''
def max_marks(list1):
    max1=list1[0]
    for i in list1:
        if i>=max1:
            max1=i
    return max1
```
## Sample Input and Output

## output
![Screenshot (17)](https://user-images.githubusercontent.com/120623104/214880892-afea7b00-7b12-44d2-969e-671b0a7549ec.png)
![Screenshot (18)](https://user-images.githubusercontent.com/120623104/214881276-288d939c-9691-4361-baa3-d60d0c8dd203.png)
![Screenshot (19)](https://user-images.githubusercontent.com/120623104/214881433-6da28aa4-d9dc-4cb2-a513-d881eba03c7b.png)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
