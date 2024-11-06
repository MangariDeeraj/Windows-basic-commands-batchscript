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
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.

![383070830-f8f35e3e-256c-4e87-a4a3-d986a3a999a8](https://github.com/user-attachments/assets/49573228-7ae3-4456-97be-16b4a08a664d)


## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.

![383070688-7772ec41-df9c-413f-8bbd-2b8687553d13](https://github.com/user-attachments/assets/5cdb700d-9dd0-455c-a061-09689fe02407)


## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

![383070552-55532b80-746c-4b60-9b51-f85f58892dba](https://github.com/user-attachments/assets/5e372c45-7023-42ac-9b37-4c227887a7d7)

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.

![383070291-8510aa6b-0b31-4415-8a64-fef2e8fcb015](https://github.com/user-attachments/assets/374d618e-6bbd-4dbf-a2d5-156540e708f3)


## COMMAND AND OUTPUT

![383070413-346a1cd7-6dd2-4635-9018-bdc6a67c9a1e](https://github.com/user-attachments/assets/7516cc59-6068-4e6f-9c4e-b7afbbfa3c96)


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

```
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\DocBackup\*.docx
echo Backup and deletion completed successfully!

```


## OUTPUT

![383071423-50e4ff0e-115a-4d0d-bf2d-bc6a853b1136](https://github.com/user-attachments/assets/8e0cd268-896b-483c-a63a-d12467b46cab)


# RESULT:
The commands/batch files are executed successfully.

