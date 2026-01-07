# Authentication: Kerberos and NTLM

Authentication means proving identity.

Active Directory mainly uses **Kerberos**.

Kerberos works using tickets.
The user proves identity once,
then uses tickets to access services.

NTLM is an older authentication method.
It is less secure and used only when Kerberos fails.

Important note:
Kerberos depends heavily on correct system time.
Even small time mismatch can break authentication.
