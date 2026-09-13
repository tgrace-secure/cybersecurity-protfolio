LINUX GROUP-BASED ACCESS CONTROL
Objective:
Understand how Linux groups can be used to control access to sensitive information.

What I did:
Created a cloudteam group.
added my Linux user(Taiwo) to the group.
Created a file called cloud-data.txt.
Assigned cloudteam as the file's group.
Set the file permission to allow the owner and group to read and write.
Tested access using a separate viewer user.
The viewer user received permission denied.

Security concept:
Group-Based Access Control/ least privilege- access can be given to a specific group instead of giving access to everyone.

Result:
The Cloudteam group was given access to the file, while the viewer user, who was not a member of the group, was denied access.

Tools:
ubuntu(WSL), Linux Terminal
