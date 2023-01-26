# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open Jupyterlab and a plain text file and save the file.

### Step 2:
Create python notebook.

### Step 3:
Open the plain text file and save it with .txt

### Step 4:
Enter some words in .txt file.

### Step 5:
Enter the code with file name as excatly given in .txt extension.

Step 6:
Run the code to find out the number of words in the .txt file

## PROGRAM:
##student name:sivaram R
<br>
##reference no:22008680
```
fname=input('enter file name:')
num_words=0
with open(fname,'r')as f:
    for line in f:
        words=line.split()
        num_words+=len(words)
print("Number of words:",num_words)
```
### OUTPUT:
![image](https://user-images.githubusercontent.com/121165794/214765953-5ec8aeaa-34b1-4883-97af-c305f80fb12c.png)
![image](https://user-images.githubusercontent.com/121165794/214765786-3eb4f74a-e3ff-492c-b01c-09dd2302ba51.png)
## RESULT:
Thus the program is written to find the word count from a text.
