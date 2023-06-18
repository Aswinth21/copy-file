# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file f1 in read mode.
### Step 2: 
Open the file f2 in append mode. 
### Step 3: 
Copy the contents using write() with the for loop.
### Step 4:  
End the program.
## PROGRAM:
```python
#Developed by: ASWINTH T
#Reg no:212222230015

with open('f1.txt','r')as f1:
    with open('f2.txt','a')as f2:
        for line in f1:
            f2.write(line)
```
### OUTPUT:
![image](https://github.com/Aswinth21/copy-file/assets/120236638/fc63d3f5-4a38-4566-8a1d-04e3e813a82a)
## FILE 1:
![image](https://github.com/Aswinth21/copy-file/assets/120236638/1216aee1-bc3e-4b6b-8ff1-bd5d4af463fc)
## FILE 2:
![image](https://github.com/Aswinth21/copy-file/assets/120236638/92c56538-45e5-48e6-9565-fc3dc0f89ce4)
## FILE 1 COPIED IN FILE 2:
![image](https://github.com/Aswinth21/copy-file/assets/120236638/7648ea20-cf7d-4d22-8767-4f5ad2504884)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
