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
End the program

## PROGRAM:
```
# Python program for getting the word count from a text
# developed by : Hariharan A
# Reg no : 212223110013

num_words=0
with open("file1.txt","r") as f1:
    for i in f1:
        word=i.split()
        num_words+=len(word)
print("Number of words in the file = {}".format(num_words))
```

### OUTPUT:
![image](https://github.com/hariharana59/Word-count/assets/144980130/786288af-a9e3-4971-838d-5872780fcfed)
![image](https://github.com/hariharana59/Word-count/assets/144980130/8bc58a25-53a5-441e-bc9b-d0742a9acab6)

## Result :
The program to find the word count is successfully completed


## RESULT:
Thus the program is written to find the word count from a text.
