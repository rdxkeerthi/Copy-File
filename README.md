# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Define the function as copy with arguements as existing file name and new file name.
### Step 2: 
 Open the existing file to read.
### Step 3: 
Open the new file to write.
### Step 4:  
Copy the contents from existing file to new file.
### Step 5: 
Get the inputs from the user for existing file and new file. Call the function.
### Step 6: 
End the program.
## PROGRAM:
```
Program for copying the contents from one file to another file
Developed by: KEERTHIVASAN M
RegisterNumber: 212223100021
with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
```
### OUTPUT:

![image](https://github.com/rdxkeerthi/Copy-File/assets/147473120/6311788e-297e-4ef8-a8d5-abf401e00440)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
