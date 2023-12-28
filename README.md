# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Declare number of words is 0
### Step 2: 
open it with file1.txt file

### Step 3: 
Give range for i

### Step 4:  
Then next split the words

### Step 5: 
count the number of words

### Step 6: 
Giving print statement for getting output

## PROGRAM:
'''
To write a python program for getting the word count from a text.
Developed by: TAMIZHSELVAN B
RegisterNumber:23013460
'''
num=0
with open("C:/Users/BSS/Documents/words.txt","r") as f1:
   for i in f1:
     word=i.split()
     num += len(word)
print("The number of words are in the file is ",num)

## words.txt:
![COUNT](https://github.com/tamizhselvan23013460/Word-count/assets/150231370/3aba0fbb-debf-44a3-8616-eed46e542025)

### OUTPUT:
![COUNT OUTPUT](https://github.com/tamizhselvan23013460/Word-count/assets/150231370/7accd578-46fb-4b08-b7d9-e1db60b77804)

## RESULT:
Thus the program is written to find the word count from a text.
