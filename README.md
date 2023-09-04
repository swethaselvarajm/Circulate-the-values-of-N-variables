# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 

### Step 1: 
Define the function to circulate variables.

### Step 2: 
Assign the given values in a list.

### Step 3: 
Get the value from the user for the number of rotation.

### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
Assign a variable for the new list after slicing and print the variable.

### Step 6: 
End of the program.

## Program:
```
#Program to circulate N values.
#Developed by: SWETHA.S
#RegisterNumber: 212222230155
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
```
## Output:
![Screenshot 2023-09-05 001229](https://github.com/swethaselvarajm/Circulate-the-values-of-N-variables/assets/119525603/c60aa70e-a699-4edd-8f01-17d96f751705)

## Result:
To Circulate the value of n variables using python was executed successfully.
