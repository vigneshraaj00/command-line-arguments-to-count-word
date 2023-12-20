# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text file in a specific loaction of interest.
### Step 2: 
 On the same location as the text file, create a python program file.
### Step 3: 
In python Program, import sys and open a text file with argument "sys.argv[1]"
### Step 4:  
using read() and split(), split the lines in the file into a sequence of words.
### Step 5: 
using len() count the number of words in the text file.
### Step 6: 
In command prompt, initiate python followed by program name and text file name to get the output.
## PROGRAM:
```
python program for getting the word count from the contents of a file using command line arguments.
Develpoed By: TAMILARASAN K S.
RegisterNumbe: 23000080
import sys
fp=open(sys.argv[1])
data=fp.read()
words=data.split()
print("no of words",len(words))
```
### OUTPUT:

![image](https://github.com/Lokhnath10/command-line-arguments-to-count-word/assets/138969918/b54ac44b-7491-46b0-896d-896f909de990)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
