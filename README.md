# command-line-arguments-to-count-word

## AIM:

To write a python program for getting the word count from the contents of a file using command line arguments.

## EQUIPEMENT'S REQUIRED: 

PC
Anaconda - Python 3.7

## ALGORITHM: 
### Step 1:
Import sys

### Step 2:
Initially make count = 0

### Step 3:
Open the content file using command line arguments.

### Step 4:
By using for loop name the function as "line"

### Step 5:
Split the line using .split

### Step 6:
Count the length of the word and print it

## PROGRAM:

```
#Developed by : Shriram S
#ROLL NO : 22008494
import sys
count=0
with open(sys.argv[1],'r') as f:
        for line in f:
            word=line.split()
            count+=len(word)
print("Word Count in File=",count)
```

### OUTPUT:

#### Text file 

![ram 5b data](https://user-images.githubusercontent.com/117991122/214808697-7332b19f-2065-45b1-a7d0-74fefa768897.png)


#### Code FIle

![SHRI 5A code](https://user-images.githubusercontent.com/117991122/214808356-b67dbc59-f631-407d-897f-b80096a0c179.png)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
