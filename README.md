# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Define a function to circulate the n variables
### Step 2: 
Get the value from the user for the lists
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Print the list 
## Program:
```
#Program to circulate N values.
#Developed by: Vanitha S
#RegisterNumber: 212222100057
def circulate():
    list=eval(input())
    n=int(input())
    final_list=list[n:]+list[:n]
    print("After circulating the values are:",final_list)
```

## Output:

![swap](/swappic.png)

## Result:

Thus the python program to circulate the n variables using function concept was successfully executed