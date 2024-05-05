# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
Developed by: Stephen raj.Y

Register No:212223230217

## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.

## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.

%userprofile%\Desktop\MyLab

![image](https://github.com/23002248/Windows-basic-commands-batchscript/assets/151701774/cf7d9249-a7b6-4907-b44a-f86ebd056075)



## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.

%userprofile%\Desktop\MyLab

![image](https://github.com/23002248/Windows-basic-commands-batchscript/assets/151701774/f31d07f5-5e24-42f5-96fd-24a6028d2e9e)
![image](https://github.com/23002248/Windows-basic-commands-batchscript/assets/151701774/6dc0a3b7-7c81-44c1-830f-dd893be1d621)



## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

%userprofile%\Desktop\MyLab

![image](https://github.com/23002248/Windows-basic-commands-batchscript/assets/151701774/f2d52925-90d6-4ed3-a50b-640be10f7a8a)


## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.mkdir %userprofile%\Desktop\Backup mkdir

 %userprofile%\Desktop\Backup 

 ![image](https://github.com/23002248/Windows-basic-commands-batchscript/assets/151701774/46cf31e9-e480-4a3f-8158-95c33f71b48b)
![image](https://github.com/23002248/Windows-basic-commands-batchscript/assets/151701774/15ab37be-4ee8-4818-8af3-9377225f7abd)



## COMMAND AND OUTPUT

mv Myfile.txt %userprofile%\Documents

![image](https://github.com/23002248/Windows-basic-commands-batchscript/assets/151701774/d067f401-8d66-44ed-a6fd-5c07a9987212)



## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx %userprofile%\Desktop\DocBackup echo Backup completed successfully!







## OUTPUT
![image](https://github.com/23002248/Windows-basic-commands-batchscript/assets/151701774/b83c36cc-b090-4583-99df-cdd0fe625314)






# RESULT:
The commands/batch files are executed successfully.

