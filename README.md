# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Assume the keyword to run the program
### Step 2: 
Use the circulate command 
### Step 3: 
Assign the value of the first variable
### Step 4: 
Assign the value of the second variable
### Step 5: 
Using the slicing concept rotate the list with the denote of the first variable
### Step 6: 
Print the values of first variable

## Program:
```
#program to circulate N values.
#Developed by:IYYANAR S
#RegisterNumber:22009120
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
```
## Output:
![OUTPUT](./Circulate%20N%20Variable.png)

## Result:
Thus the circulating of N variable is successfully executed