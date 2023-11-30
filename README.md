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

def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large



```

ii)	# To find the maximum marks using the list method max().
```Python

def max_marks(marks):
    large=max(marks)
    return large
    # write your code here



```

iii) # To find the maximum marks without using builtin functions.
```Python

ef max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max




```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:

![image](https://github.com/feryjfgkuyfgewjfgew/FindMaximum/assets/150319377/7b0ab894-1e28-4017-82c1-b1d22c3eaec9)

![image](https://github.com/feryjfgkuyfgewjfgew/FindMaximum/assets/150319377/8a84f2ea-5e20-4957-929f-123562ce2cbf)

![image](https://github.com/feryjfgkuyfgewjfgew/FindMaximum/assets/150319377/67f5ff9b-e434-4157-b7ba-dc4e1f02d8b6)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
