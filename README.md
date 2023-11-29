# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
start the program
### Step 2: 
get the input from the user eval(input())
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
using concatenation operation display the entire rotated list

### Step 6: 
stop the program
## Program:
#Program to circulate N values.
#Developed by: VINNUSH KUMAR L S 
#RegisterNumber: 23012349
def circulate():
    lst1=eval(input())
    n=int(input())
    lst2=lst1[n:]+lst1[:n]
    print("After circulating the values are:",lst2)

## Output:
![1 b circulate n variables](https://github.com/vinnush147/Circulate-the-values-of-N-variables/assets/147139234/78357b7b-e13f-4857-a238-5c0baa37e7de)


## Result:
Thus the circulating of n variables are successfully executed
