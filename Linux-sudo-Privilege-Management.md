# Linux Sudo & Privilege Management 
**Objective**
Understand how Linux controls administrator Privilege and applies the principle of least privilege.

**What I did:**
- Tested the 'viewer' user to check whether it could use 'sudo'.
- The 'viewer' user was denied sudo access.
- Returned to the 'Taiwo' administrator account.
- Used 'sudo wwhoami' to verify administrator privilege.
- The command returned 'root'.

** Security Concept:**
**Least Privilege** _ users should only have the Level of access required to perform their tasks.
**Results:**
The 'viewer' account had limited privileges, while the 'Taiwo' account was able to use administrator privilege through 'sudo'.

**Tools:**
Ubuntu (WSL), Linux terminal 

**Evidence:**
'Linux_Sdo_Privilege_Test.png'
