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
Developed by: ARVIND S
RegisterNumber: 212222240012

def max_marks(marks):
    marks.sort()
    max = marks[-1]
    return max
```

ii)	# To find the maximum marks using the list method max().
```Python
Program to find the maximum marks using the list method max().
Developed by: ARVIND S
RegisterNumber: 212222240012

def max_marks(marks):
    maximum = max(marks)
    return maximum
```

iii) # To find the maximum marks without using builtin functions.
```Python
Program to the maximum marks without using builtin functions.
Developed by: ARVIND S
RegisterNumber: 212222240012

def max_marks(marks):
    max = 0
    for i in marks:
        if i > max:
            max = i
    return max
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
To find the maximum of marks using the list method sort.
![Screenshot 2023-11-09 161828](https://github.com/S-ARVIND01/FindMaximum/assets/118707337/3aae92d5-6ba7-49d3-88f8-b28c18a4fcaa)

To find the maximum marks using the list method max().
![Screenshot 2023-11-09 161846](https://github.com/S-ARVIND01/FindMaximum/assets/118707337/6ea66826-6981-4bd4-be7b-3128b2640fa2)

To find the maximum marks without using builtin functions.
![Screenshot 2023-11-09 161859](https://github.com/S-ARVIND01/FindMaximum/assets/118707337/e36921ac-b5cc-4a71-b663-9dd894d1d37d)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
