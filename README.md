# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:
define a function csalled circulate()
### Step 2: 
 get the list from user
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
print the output which gives a list after circulate the n variables
### Step 6: 
end the program
## Program:
def circulate():
     a=eval(input())
     n=int(input())
     c=a[n:]+a[:n]
     print("After circulating the values are:",c)
     
## Output: 


## Result:
