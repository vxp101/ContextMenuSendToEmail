# ContextMenuSendToEmail

To start off copy the file path you plan to use and replace *FILE PATH GOES HERE* with said file path inside of .bat

Use PyInstaller to turn script into a .exe 

Put File path of .exe into the .bat file accordingly and insert the .bat into %appdata%/Microsoft/Windows/SendTo.

To Set Up Google Api. 

Click this link : : https://console.cloud.google.com/getting-started?pli=1

If a pop up appears asking to agree to the terms of service click agree and do the rest of what it asks.

Click the 3 vertical lines in the top left.

Click API and Services

Click Create Project

Put In Project name and Organization if you have one. Then click create.

The new project should already be the next screen if its not click the down arrow at the top and select your project.

Click ENABLE API AND SERVICES

In the search bar type "gmail" and press enter

Click Gmail API

Click Enable

After the next page loads click Credentials on the left nav bar

Click Configure Consent Screen

Select External

Click Create

Input the required information

Click Save and Continue

--- I Wanted To Do This Tutorial Step By Step But An Error Is Occurs When I Click Save and Continue. Will Update When Fixed. ---

In scopes and https://mail.google.com/ as one of the scopes.

Make yourself a test user after all this is Done

Goto Credentials Create Credentials and select OAuth Credentials

Then after all thats done in Credentials go down to the newly created OAuth Credential and click download

Put the download into the same path as the .exe

Select a files and right click then goto Send To and select the .bat file

It will ask you to authenticate and you'll only have to do this once

All the selected files will be sent to your email

**CREATE CONTEXT MENU OPTION**
https://answers.microsoft.com/en-us/windows/forum/all/how-to-add-an-option-in-windows-11-main-context/a6c6ba72-e17b-44d5-b957-46af79b47b60 
