# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import os
### Step 2: 
Open file using open().
### Step 3: 
Use for loop
### Step 4:  
Use len to count number of words.
### Step 5: 
Give print.
### Step 6: 
End of the program
## PROGRAM:
```python
#Developed by:MOHAMED FAREED.F
#Reference number:22001617
import sys
count= 0
with open(sys.argv[1],'r') as f1:
    for line in f1:
        word= line.split()
        count += len(word)
print("word count in file = ",count)
```
### OUTPUT:
![Screenshot from 2023-01-26 10-25-10](https://user-images.githubusercontent.com/121412904/214801126-871a87c1-15bc-4b72-ae0a-b0cca816006b.png)
## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
