# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
#Program to find the solution for the given linear equations.

#Developed by: Adam 

#RegisterNumber:212225230005

a1 = 1

b1 = 3

c1 = 5

a2 = 2

b2 = 5

c2 = -3

D = a1*b2 - a2*b1

Dx = c1*b2 - c2*b1

Dy = a1*c2 - a2*c1

x = Dx / D

y = Dy / D

print(f"[{x:.0f}.  {y:.0f}.]")

## Output:
<img width="1920" height="1080" alt="Screenshot 2026-05-09 233133" src="https://github.com/user-attachments/assets/10ccc628-16bd-42fb-8629-9b3f6dad16d4" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

