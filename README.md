# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Import def circulate
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Add coding to input value
### Step 6: 
Print the coding to gat answer 

## Program:
```
#Program to circulate N values.
#Developed by: Aakashraj M
#RegisterNumber:22008579

def circulate():
     l=eval(input())
     n=int(input())
     l=l[n:]+l[:n]
     print("After circulating the values are:",l)
```

## Output:
![Circulate the value Output (1)](https://user-images.githubusercontent.com/121117266/209361377-d02bdd7b-d384-47c1-aabc-e9d48138f783.png)
![Circulate the value Output (2)](https://user-images.githubusercontent.com/121117266/209361490-b24fe2cd-6a4b-4cb3-9d1f-debe0982051a.png)

## Result:
Thus the python program to circulate the n variables using function concept is obtained.
