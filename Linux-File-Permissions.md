Linux File Permission $ access Control 
Objective
understand hoe Linux file permission can be used to restrict access to sensitive information.

What I did:
Create a file named customer-data.txt
checked its default permission using ls -l.
Changed the permission using chmod 600.
Created a separate viewer user.
logged in as viewer and attempted to access the file.
The access attempt was denied.

Security Concept:
Least privilege / Access Control-users should only have the permission required for their tasks.

Result:
The file owner could read and modify the file, while the viewer user was prevented from accessing the file.

Tools:
Ubuntu(WSL),Linux Terminal

Evidence:
Screenshots showing the original permissions, changed permissions, and the permission-denied test
