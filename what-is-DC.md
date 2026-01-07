# Domain Controller Explained

A Domain Controller (DC) is a Windows Server
that runs the Active Directory Domain Services role.

The Domain Controller is the **heart of Active Directory**.

Its responsibilities include:
- Authenticating users
- Authorizing access
- Storing AD database
- Applying Group Policies

When a user logs in:
The computer contacts the Domain Controller,
not a local database.

Important files on DC:
- NTDS.dit → Active Directory database
- SYSVOL → Group Policies and scripts

If Domain Controllers are unavailable,
users cannot log in to the domain.
