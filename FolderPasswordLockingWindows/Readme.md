## Let's see to Configure this Folder Lock...

##### Step 1: Create a New Folder which you want to lock.
	Right Click on the blank page 
	Go to "New"
	Click on "Folder" and Name It.
###### There is another way for Creating a Folder.
	Press "Shift + Ctrl + N"

##### Step 2: Create a new "Text Document".
Text Document Named as : :  `FolderLock.txt`
##### Step 2: Copy and Paste the above Code given in `MainFile.txt` to your file `FolderLock.txt`.
##### Step 3. Find `YOUR-PASSWORD` written in `FolderLock.txt`.
```bash
if NOT %pass%== YOUR-PASSWORD goto FAIL
```
It will be on Line 21, Maybe....
##### Step 4: Replace `YOUR-PASSWORD` with any PASSWORD you want.

> :warning: **Don't Delete any Space While changing Password**. Be very careful here!

##### Step 5: Save your file as `FileName.bat` in the same Folder.
##### Step 6: Double Click on the `FileName.bat`.
	It will Create a new folder with name "Private".
##### Step 7: Drag all the containt you want to lock to the "Private" Folder.
	You can delete the `FolderLock.txt` File containt with your data, if you want.
##### Step 8 : Again Double Click on `FileName.bat`.
	It will open "Command Prompt" and ask to say Yes or No.
	If you want to lock Press "Y" and if not Press "N".
> Your Folder Name Private Will be hidden until you enter the password to make visble.

## Let's see how to UNLOCK the Folder...

##### Step 1: Double Click on `FileName.bat`
	It will ask for "PASSWORD"
##### Step 2: Insert the Password and Press Enter.
	It will close the "Command Prompt".
	And it will show the "Private" Folder that contain all your data.

> [!CAUTION]
> Never Delete the Main Folder Which you have created at first
> `It may cause deleating all our data.`
