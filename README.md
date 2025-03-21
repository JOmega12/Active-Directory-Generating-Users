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
-  Log into client 1 as jane admin and turn on remote desktop for domain users. This will allow the generated users to enter client-1

<h3>Open Powershell_ise as admin</h3>



<h3>Create a new File and paste the contents of the script</h3>

-  within the admin, open Powershell_ise then copy and paste this <a href="https://github.com/joshmadakor1/AD_PS/blob/master/Generate-Names-Create-Users.ps1">Script</a> to generate random users and save it
-  Then run the script

<h3>When finished open ADUC and observe the accounts in the appropriate Organizational Unit</h3>

<h3>Attempt to log into Client-1 with one of the accounts</h3>

- NOTE: Password is on top of the script 
<br />
<h2>Conclusion</h2>

<p>Success! You've created your first user for Active Directory. The next step will involve using the random user for different Active Directory Scenarios</p>
- Click on the next project: <a href="https://github.com/JOmega12/Active-Directory-Practical-Uses">Next Project</a>

<br />
