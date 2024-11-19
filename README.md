## DATE:
# EX.NO.11 Copy File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a file.
### Step 2: 
Write some Sentences in that file.
### Step 3: 
Create a python file.
### Step 4:  
Write a code to copy the content of the file to a new file.
### Step 5: 
Run the program.
### Step 6: 
Display the output.
## PROGRAM:
```
#Copy contents of a file 
#Developed by: HARSSHITHA LAKSHMANAN
#Register Number:212223230075

with open("file.txt","r") as fp:
    msg1=fp.read()
with open("copytxt","w") as fp1:
    fp1.write(msg1)
```
### OUTPUT:
![image](https://github.com/user-attachments/assets/781fe734-1f3d-4ddc-b92a-8c5765649a73)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
