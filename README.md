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

![image](https://github.com/IT-chris-k/post-install-config/assets/150845863/c2cf9750-7f96-4044-9cdd-132f74eb0382)

![image](https://github.com/IT-chris-k/post-install-config/assets/150845863/0849c655-b595-4365-bcf7-58210c74465a)

![image](https://github.com/IT-chris-k/post-install-config/assets/150845863/2629f624-c21b-42d0-9ef1-697afb3910b1)




<p>For configuring departments go to Admin Panel -> Agents -> Departments -> new Department
  Departments are for grouping agents based on their role in the company. 
  Teams allow you to take agents from different departments to organize them to handle specific issues by different users or ticket filter.
  In this example we will create a department for system administrators. 
</p>



![image](https://github.com/IT-chris-k/post-install-config/assets/150845863/b58a7f23-c704-4849-abf6-03b63aaa5c71)

<p>
Require users to register and login before creating tickets is helpful for indicating who had an issue, and who to contact once the issue has been resolved.

</p>
<br />


![image](https://github.com/IT-chris-k/post-install-config/assets/150845863/b8687e99-df5e-40ae-b331-cca72e6aec9f)


<p>

  Agents are reponsible for finding the answers to the tickets and resolving them in a timely manner.
  Agents are those in the help desk or tech support role responsible for creating and taking care of tickets.
  
</p>



<p>

  Users are able to create accounts and tickets.

</p>

![image](https://github.com/IT-chris-k/post-install-config/assets/150845863/617b88fd-b737-438f-8c64-9e9ad3dd5b1b)


<p>
  Under Agent Panel -> Users -> Create new user
</p>

![image](https://github.com/IT-chris-k/post-install-config/assets/150845863/ca29b17a-919f-4eae-b795-64bafdc80cca)

<p>
  SLA or service level agreements are rules set in place for how long a help desk admin expects a ticket to be closed.
  SLA have different levels allowing for prioritization.
  Configured in Admin Panel -> Manage -> SLA -> new SLA
  
</p>
























