# Burp-Suite-pro-2023
A Bash and PowerShell script for acquiring the most recent edition of Burp Suite Professional 2023 without charge.

#Burp Suite Professional Installation Steps for Windows
--> Copy the downloaded files to C:\Burp.
	Make a new directory "Burp" in C Drive for faster access.
--> Open Powershell and execute the below command to set the Script Execution Policy.
	Set-ExecutionPolicy -ExecutionPolicy bypass -Scope process
--> Now Execute the Windows_Setup.ps1 file in Powershell to Complete the Installation.
	./Windows_Setup.ps1
--> Change the icon of **Burp-Suite-Pro.vbs** to the given icon 
	Create a shortcut to Desktop. Right-click over **Burp-Suite-Pro.vbs** Go to the Shortcut tab, and below there is **Change Icon** tab.
	Click here and choose the burp-suite.ico from C:\Burp\ 
	![image](https://user-images.githubusercontent.com/29830064/230825172-16c9cfba-4bca-46a4-86df-b352a4330b12.png)

--> For Start Menu Entry, copy **Burp-Suite-Pro.vbs** file to 
	C:\ProgramData\Microsoft\Windows\Start Menu\Programs\
