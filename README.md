# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a new text file
### Step 2: 
 Add some sentence to the file
### Step 3: 
 Now in the main.py file using split function,split the words in the .txtfile
### Step 4:  
Count the splitted Words
### Step 5: 
Add the counted number in the variable
### Step 6: 
 Run the program and display the results
## PROGRAM:
```
Developed by Harshini Y
Reg no:212223240050
num_words =0
with open('text.txt','r') as file1:
for i in file1:
word =i.split()
num_words += len(word)
print("Number of words={}".format(num_words))
```
### OUTPUT:

![image](https://github.com/harshiniyu/Word-Count/assets/144979786/b8c29f5d-46ba-47c4-8564-9b2c617dfd56)


## RESULT:
Thus the program is written to find the word count from a text.
