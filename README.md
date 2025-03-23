<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>


<h1>Active Directory Generating Users</h1>
This tutorial outlines for creating random users to practice for Active Directory concepts
<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Powershell

<h2> Objectives</h2>

- Create a bunch of additional users and attempt to log into client-1 with one of the created users

<h2> Configuration </h2>

<h3>Login to DC-1 as jane_admin</h3>

-  Use mydomain.com\jane_admin as username

<h3>Open Powershell_ise as admin</h3>

![copyPastScript](https://github.com/user-attachments/assets/c2428546-c5eb-4e35-9296-9730e9f0a48f)



<h3>Create a new File and paste the contents of the script</h3>

-  within the admin, open Powershell_ise then copy and paste this <a href="https://github.com/joshmadakor1/AD_PS/blob/master/Generate-Names-Create-Users.ps1">Script</a> to generate random users and save it
-  Then run the script
![RunScript](https://github.com/user-attachments/assets/c201d506-205a-4eb7-88c2-4bcfa805061a)



<h3>When finished open ADUC and observe the accounts in the appropriate Organizational Unit</h3>

![ObserveGenUsers](https://github.com/user-attachments/assets/590923f3-2296-427d-aecb-4d9845bf6c63)

<h3>Attempt to log into Client-1 with one of the accounts</h3>

- NOTE: Password is on top of the script
![putCredentials](https://github.com/user-attachments/assets/3c61a490-a0c0-4b64-927e-45cf128021e9)

<br />
<h2>Conclusion</h2>

<p>Success! You've created your first user for Active Directory. The next step will involve using the random user for different Active Directory Scenarios</p>
- Click on the next project: <a href="https://github.com/JOmega12/Active-Directory-Practical-Uses">Next Project</a>

<br />
