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

Program to mark the maximum of marks using the list method sort
Developed by: Anbu Vinotha.S
RegisterNumber:23013363

def max_marks(marks):
    marks.sort()
    max=marks[-1]
    return max
max_marks([88, 67, 77, 93, 95, 11, 67, 89, 56, 89])


```

ii)	# To find the maximum marks using the list method max().
```Python
Program to find the maximum marks using the list method max().
Developed by: Anbu Vinotha.S
RegisterNumber:23013363 

def max_marks(list):
    max = list[0]
    for i in list:
        if i>max:
            max=i
    return max
max_marks([88, 67, 77, 93, 95, 11, 67, 89, 56, 89])

```

iii) # To find the maximum marks without using builtin functions.
```Python
Program to the maximum marks without using builtin functions.
Developed by: Anbu Vinotha.S
RegisterNumber: 23013363

def max_marks(list1):
    max1 = list1[0]
    for i in list1:
        if i>max1:
            max1=i
    return max1
max_marks([88, 67, 77, 93, 95, 11, 67, 89, 56, 89])





```
## Sample Input and Output
![output](<max ss1.png>)
![output](<max ss2.png>)
![output](<max ss3.png>)





## Output:

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.