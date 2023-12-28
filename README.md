# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: 

Open the file in read mode and handle it in test mood.

### Step 2: 

Read the text using read() function.
 
### Step 3: 

Split the text using space separator.We assume that words in a sentance are separted by a space character.

### Step 4: 

The length of the split list should equal the numbers of words in the test file.

### Step 5: 

You can refine the count by cleaning the string prior to splitting or validating the words after splitting.

### Step 6: 

End the program.

## PROGRAM:
```
Developed by : M.Hashwatha
RegisterNumber : 23012398

num_words =0
with open('Untitled.ipynb','r') as file1:
    for i in file1:
        word =i.split()
        num_words += len(word)
print("Number of words={}".format(num_words))

```
### OUTPUT:

![image](https://github.com/Hashwatha/Word-count/assets/150231431/5f6b119c-6b7f-46cf-af11-b48c2938487a)

## RESULT:
Thus the program is written to find the word count from a text.
