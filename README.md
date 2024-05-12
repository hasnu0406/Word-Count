# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create new text file
### Step 2: 
Add some sentence to the file 
### Step 3: 
Now in the main.py file using split function, split the words int .txt file
### Step 4:  
Count the splitted words 
### Step 5: 
Add the counted number in the variable
### Step 6: 
Run the program and display the results.
## PROGRAM:
```Python
Developed by: HASNA MUBARAK AZEEM
Reg No: 212223240052
num=0
with open("text.txt","r") as f1:
    for i in f1:
        word=i.split()
        num+=len(Word)
print("The number of words in the file is: ",num)
```
### OUTPUT:
![alt text](<exp 9.png>)

## RESULT:
Thus the program is written to find the word count from a text.
