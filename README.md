<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lets start by opening up azure and opening up the virtual machine. 
Click on the virtual machine named osTicket, look for the public ip address.
We need the public ip address in order to use the rdp protocol to remote login into the virtual machine.
For windows pc use remote desktop app , and for macs download microsoft remote desktop.
login using public ip address, a prompt will show up to type in username and password for credentials.
  
</p>
<br />


![image](https://github.com/IT-chris-k/post-install-config/assets/150845863/ca404d8c-3462-4820-ae40-05f901b85554)



<p>
Since we are still setting things up, lets use the osTicket login website
  http://localhost/osTicket/login.php
  make sure to click "i'm an agent, sign in here" 
  this will ensure you login as an agent to configure things as an admin.
  
</p>
![image](https://github.com/IT-chris-k/post-install-config/assets/150845863/0f833d0a-fc45-48b4-b534-21f01ee75ea4)

<br />



![image](https://github.com/IT-chris-k/post-install-config/assets/150845863/d7b6c50d-c4bf-4c54-855d-c9bde883e048)


<p>
Once youre logged in click on the Admin panel to start configuring things.
  you can define custom roles for somebody. we will be creating a custom admin role
  Admin Panel -> Agents -> Roles -> Add a new role
  Define a role by giving it a name and set the permissions on what this role is able to do.
  In this example we will create a supreme admin role that has access to all permissions.
  For security purposes it is better to follow the least privilege access concept, having an account that has every permission is not safe.

  
</p>

<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
