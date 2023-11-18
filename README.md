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
using read() and split(), split the lines in the file into a sequence of words

### Step 5: 
using len() count the number of words in the text file.

### Step 6:
In command prompt, initiate python followed by program name and text file name to get the output.

## PROGRAM:
```
'''
python program for getting the word count from the contents of a file using command line arguments.
Develpoed By: Sundaramurthy M
RegisterNumber:23010238
'''
import sys
fp=open(sys.argv[1])
data=fp.read()
words=data.split()
print("no of words",len(words))
``` 
### OUTPUT:

<img width="746" alt="Screenshot 2023-11-18 at 10 17 41 AM" src="https://github.com/Murthy46/command-line-arguments-to-count-word/assets/145112768/f1a2725c-cd6f-446e-bd80-d0402a75a37c">


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
