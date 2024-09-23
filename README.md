# Group-Policy-and-Managing-Accounts

Dealing with Account Lockouts
Get logged into dc-1
![image](https://github.com/user-attachments/assets/9de6f6bd-70a7-4903-b7bd-b776fc13694d)

Pick a random user account you created previously
Attempt to log in with it 10 times with a bad password

Configure Group Policy to Lockout the account after 5 attempts:

![image](https://github.com/user-attachments/assets/6bb90d12-be63-46c4-abdf-11a8b86bae2a)

Attempt to log in with it 6 times with a bad password

Observe that the account has been locked out within Active Directory
Unlock the account
Reset the password
Attempt to login with it

![image](https://github.com/user-attachments/assets/545aaf81-af06-4e2f-8500-bf99027387de)

Enabling and Disabling Accounts
Disable the same account in Active Directory
Attempt to login with it, observe the error message
Re-enable the account and attempt to login with it.

Observing Logs
Observe the logs in the Domain Controller
Observe the logs on the client Machine
Precursor to cybersecurity and security operations: joshmadakor.tech/cyber

