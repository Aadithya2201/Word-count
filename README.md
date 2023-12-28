# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open a exsiting text file

### Step 2:
Read the file and store in the variable

### Step 3:
count=0

### Step 4:
using for loop split the word

### Step 5:
using count+=1

### Step 6:
print the count

### Step 7:
End the program 

## PROGRAM:
```
"""
To write a python program for getting the word count from a text.
Developed by: AADITHYA R
Reference no: 23006361
"""
with open("myfile.txt","r") as f:
    b=f.read()
    count=0
    for i in b.split():
        count+=1
    print(count)
```

## OUTPUT:
![Screenshot 2023-12-28 141342](https://github.com/Aadithya2201/Word-count/assets/145917810/2d8cb8a9-2322-45e9-b2c3-610ffa11c728)
![Screenshot 2023-12-28 141410](https://github.com/Aadithya2201/Word-count/assets/145917810/b787f66d-f6ff-4ec0-b456-ac35f54992e9)

### TEXT FILE
![Screenshot 2023-12-28 141436](https://github.com/Aadithya2201/Word-count/assets/145917810/4c562064-deb2-4efa-8476-a95bb6db7db2)



## RESULT:
Thus the program is written to find the word count from a text.
