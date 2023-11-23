# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
 Initialize variables
### Step 2: 
Store variables in a list
### Step 3: 
Rotate the list to the right (circular shift)
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
 Print the updated variables
### Step 6: 
 Repeat steps 3-5 as needed
## Program:
```
#Program to circulate N values.
#Developed by: Tirupathi Jayadeep
#RegisterNumber:23004426
def circulate():
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result)
```
## Output:
![Screenshot 2023-11-23 145943](https://github.com/23004426/Circulate-the-values-of-N-variables/assets/144979327/b86bc0d5-472c-44e4-a643-13ee9214b425)

## Result:
Thus a python program to Circulate the n variables using function concept is executed
