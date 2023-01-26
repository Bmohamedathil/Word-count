# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
First take input from the user

### Step 2: 
 using open function to open

### Step 3: 
and use for loop

### Step 4:  
The length of the split list should be equal to the number of words in the text file.


### Step 5: 
now, print()

### Step 6: 
End the program
## PROGRAM:
```
fname = input('Enter file name:')
num_words = 0
with open(fname, 'r') as f:
    for line in f:
        words = line.split()
        num_words += len(words)
print('Numbr of words: ', num_words)
```
## OUTPUT:
![output](/Screenshot%20from%202023-01-26%2020-56-11.png)

## RESULT:
Thus the program is written to find the word count from a text.
