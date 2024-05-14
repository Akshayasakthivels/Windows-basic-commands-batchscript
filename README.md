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
```
NAME:AKSHAYA S
REG.NO:212223220006
```
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
%userprofile%\Desktop\MyLab
![image](https://github.com/Akshayasakthivels/Windows-basic-commands-batchscript/assets/144870561/fb1cb5ab-d96a-4a98-a169-796faa2df159)

## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
%userprofile%\Desktop\MyLab
![image](https://github.com/Akshayasakthivels/Windows-basic-commands-batchscript/assets/144870561/d7a0d521-aa77-4536-8689-a276a1a8b07a)


## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
%userprofile%\Desktop\MyLab
![image](https://github.com/Akshayasakthivels/Windows-basic-commands-batchscript/assets/144870561/a22810fe-4dec-431a-84c5-39e4ffb21c3e)

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
mkdir %userprofile%\Desktop\Backup mkdir %userprofile%\Desktop\Backup
![image](https://github.com/Akshayasakthivels/Windows-basic-commands-batchscript/assets/144870561/5a0567c2-52a4-4d47-8daf-7fd8f6ce3d5b)


## COMMAND AND OUTPUT
mv Myfile.txt %userprofile%\Documents

![image](https://github.com/Akshayasakthivels/Windows-basic-commands-batchscript/assets/144870561/7d1d5f9d-91d3-46ba-8df4-abe9badd7984)


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.
@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx %userprofile%\Desktop\DocBackup echo Backup completed successfully!






## OUTPUT

![image](https://github.com/Akshayasakthivels/Windows-basic-commands-batchscript/assets/144870561/9d3cc0f3-ee40-41bc-8cdf-1f6a380c2a55)




# RESULT:
The commands/batch files are executed successfully.

