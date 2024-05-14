# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Define the function as copy with arguments as existing file name and new file name

### Step 2: 
Open the existing file to read.
### Step 3: 
Open the new file to write.
### Step 4:  
Copy the contents from existing file to new file.
### Step 5: 
Get the inputs from the user for existing file and new file.Call the function
### Step 6: 
End the program.
## PROGRAM:
```
Developed by: NITHIYANANDAN N
Reg No: 212222230099
with open("text1.txt","r") as fp:
    msg1=fp.read()
with open ("copytxt","w") as fp1:
    fp1.write(msg1)
```
## OUTPUT:
![Screenshot 2024-05-14 101030](https://github.com/NITHIYANANDAN278/Copy-File/assets/121784636/5fd4bd9a-01e5-411a-b8ab-cbbe00a073ca)
![Screenshot 2024-05-14 101106](https://github.com/NITHIYANANDAN278/Copy-File/assets/121784636/e8ef3489-bc38-41f4-8a51-41cbb384ad46)
![Screenshot 2024-05-14 101148](https://github.com/NITHIYANANDAN278/Copy-File/assets/121784636/e18b0b07-52e4-4e0b-9385-056315951109)




## RESULT:
Thus the program is written to copy the contents from one file to another file.
