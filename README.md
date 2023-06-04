# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys module.

### Step 2: 
 Open the file with sys.argv[1].
 
### Step 3: 
Use the for loop to select the content in file.

### Step 4:  
Use split function to to separate the file content into words or strings.

### Step 5: 
Count the length of the words using len.

### Step 6: 
Print the number of words.

## PROGRAM:
```
'''
Program for getting the word count from the contents of a file using command line arguments.
Programmed by: Lokesh N
Ref.No.: 212222100023
'''
import sys
fp=open(sys.argv[1],'r')
count=0
for line in fp:
    words=line.split()
    count+=len(words)
print("Number of words in a file",count)

```
### OUTPUT:
![Screenshot from 2023-06-04 11-34-04](https://github.com/lokeshnarayanan/command-line-arguments-to-count-word/assets/119393019/5fab08a1-0441-4c66-a12e-3dbf4290925b)


![Screenshot from 2023-06-04 11-19-15](https://github.com/lokeshnarayanan/command-line-arguments-to-count-word/assets/119393019/ce3855b7-2c8b-4991-aa78-86c6e8b3983c)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
