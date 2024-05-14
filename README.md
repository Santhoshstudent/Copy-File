# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1:
Load the CSV into a DataFrame.

Step 2:
Print the number of contents to be displayed using df.head().

Step 3:
The number of rows returned is defined in Pandas option settings.

Step 4:
Check your system's maximum column with the pd.options.display.max_column statement.

Step 5:
Increase the maximum number of rows to display the entire DataFrame

Step 6:
End the program.

## PROGRAM:

#To write a python program for reading content from a CSV file.
#Developed by: santhosh kumar b
#Register Number: 212223230193
def copy(fname,newfile):
    with open(fname) as fp:
        with open(newfile,'w') as fp1:
            data=fp.read()
            fp1.write(data)
copy("file1.txt","kml.txt")            

### OUTPUT:
![image](https://github.com/Santhoshstudent/Copy-File/assets/145446853/8c089f9b-ddea-4c2f-ad48-d9ff813de5b6)

![image](https://github.com/Santhoshstudent/Copy-File/assets/145446853/e6fbe21f-1328-4340-8fbb-729c61df7217)





## RESULT:
Thus the program is written to copy the contents from one file to another file.
