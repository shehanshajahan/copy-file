# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text1.txt with some content in it 
### Step 2: 
Open the text1.txt file in read mode
### Step 3: 
Create a copy.txt file using write mode
### Step 4:  
Copy the content of text1.txt to to copy.txt using write function
## PROGRAM:
#Python program to copy the contents of one file to another file
#Developed by: Shehan Shajahan
#Register Number: 23008724
def copy(fname,newfile):
    with open(fname,"r") as fp:
        with open(newfile,"w") as fp1:
            data1=fp.read()
            fp1.write(data1)
fname=input("Enter an existing file name: ")
newfile=input("Enter a name for the new file: ")
copy(fname,newfile)
### OUTPUT:
![Screenshot 2024-01-02 172132](https://github.com/shehanshajahan/copy-file/assets/139317389/9bb5e53b-6c07-47b5-932f-8beb4abad042)
![Screenshot 2024-01-02 171949](https://github.com/shehanshajahan/copy-file/assets/139317389/a69fd622-53e3-41a2-b711-94f1394bb27f)
![Screenshot 2024-01-02 171920](https://github.com/shehanshajahan/copy-file/assets/139317389/351fcf01-f642-4aa6-8470-f971c7839060)
## RESULT:
Thus the program is written to copy the contents from one file to another file.
