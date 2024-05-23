# Selection sort and Insertion sort
## Aim:
To write a program to perform selection sort and insertion sort using python programming.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Selection Sort Algorithm:
1.	Set the first unsorted element as the minimum
2.	For each of the unsorted elements, check if the element < current minimum.
3.	If yes, set the element as the new minimum.
4.	Swap minimum with first unsorted position.
5.	Repeat the steps 2 and 3 for all the elements in the array.
## Insertion Sort Algorithm:
1.	Set the first element as sorted element j.
2.	For each unsorted element X, check if current sorted element j >X.
3.	If yes, move sorted element to the right by 1.
4.	Break the loop and insert X.
5.	Repeat the steps 2 to 4 for sorting all the elements in the array.
## Program:
i)	#Selection Sort
```
'''name:veslin anish .A
   register no:212223240175'''
num=eval(input())
for i in range(len(num)):
    low=i
    for j in range(i+1,len(num)):
        if num[j]<num[low]:
            low=j
    num[i],num[low]=num[low],num[i]
print(num)





```
ii)	#Insertion Sort
```
'''name:veslin anish.A
register no:212223240175'''
num=eval(input())
for i in range(1,len(num)):
    insert=num[i]
    j=i-1
    while j>=0 and num[j]>=insert:
        num[j+1]=num[j]
        j=j-1
    num[j+1]=insert
print(num)






```

## Output:
![Screenshot 2024-05-23 153611](https://github.com/veslin23000303/Sorting-Algorithms/assets/151148539/363806db-3ad5-410a-804c-6d1d1c04207b)

![Screenshot 2024-05-23 153624](https://github.com/veslin23000303/Sorting-Algorithms/assets/151148539/1021936f-9ad2-41b4-b61e-38aa5726b037)


## Result:
Thus the program is written to perform selection sort and insertion sort using python programming.
