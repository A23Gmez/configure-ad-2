# # Configuring-AD Part 2

<h1>Creating Users w/ PowerShell</h1>

![image](https://github.com/user-attachments/assets/3b32e7e9-8b18-4233-8a94-dde8afc44543)

Part 2


<h2>Setup Remote Desktop for non-administrative users on Client-1</h2>

![image](https://github.com/user-attachments/assets/4092476a-cead-4899-84c7-3fedc6e91a82)

- Log into Client-1 as mydomain.com\jane_admin
- Open system properties
- Click “Remote Desktop”
- Allow “domain users” access to remote desktop

<h2>Create a bunch of additional users and attempt to log into client-1 with one of the users</h2>

![image](https://github.com/user-attachments/assets/7531f289-607b-49e1-bb52-080f9f127cbc)

- Login to DC-1 as jane_admin
- Open PowerShell_ise as an administrator
- Create a new File and paste the contents of the script into it
- Run the script and observe the accounts being created

![image](https://github.com/user-attachments/assets/775b9a3f-795f-489a-9ac4-8d5f0a3b6048)

- Once finished, open ADUC and observe the accounts in the appropriate OU　(_EMPLOYEES)

![image](https://github.com/user-attachments/assets/90ab8834-d803-4970-80d1-b111114d69bf)

- Attempt to log into Client-1 with one of the new accounts


