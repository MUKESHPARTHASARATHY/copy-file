# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Use open function to open the file in which we want to copy from and access it in read mode
### Step 2: 
 Read the file and store in a variable.
### Step 3: 
Now create a new file in which we want to paste the content using write access mode.

### Step 4:  
Use write function to copy the read file that has been stored in the variable.

### Step 5: 
The content in the original file will be copied in the new file.

### Step 6: 
End the program.
## PROGRAM:
```
with open("sample1.txt", "r") as firstfile:
      with open("sample2.txt", "a") as secondfile:
           for line in firstfile:
                secondfile.write(line)
```

### OUTPUT:

![image](https://user-images.githubusercontent.com/119393818/215309712-948057c2-c752-4237-9d97-57d1c83836b0.png)

![image](https://user-images.githubusercontent.com/119393818/215309734-cdfed98b-7d43-4f12-afd8-7b0e4af7a3a5.png)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
