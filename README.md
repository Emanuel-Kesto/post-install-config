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

- Virtual Machine 
- OsTicket 

<h2>Configuration Steps</h2>

<p>
<img  src="https://github.com/user-attachments/assets/9dd71e4d-7aef-461e-b137-2003dd81dccc" alt="Permissions"/>
</p>
<p>
 After installing osTicket, the next task is to create an admin role and configure permissions. After creating the admin role you must create departments, such as networking, help desk and administrator. The next step is to create teams and agents to resolve tickets. All individuals who want access to network resources must create user accounts. Those user accounts are the ones that create tickets if they come accross issues that agents must resolve.  
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/0900eafb-6288-4ffd-9837-01c071365db3"/>
</p>
<p>
Once all the users and agents are created the next objective is to create SLA's. The first being Sev-A which has an hour grace period on a 24/7 schedule, these type of tickets tend to be high alert and must be resolved as soon as possible. The second is Sev-B which has a 4hr grace period on a 24/7 schedule. The last is Sev-C, which has a 8hr grace period and the schedule tends to be during business hours, Monday-Friday 8am-5pm. 
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/83555f69-6f53-4e55-abb4-9c0c2acd135b"/>
</p>
<p>
The last portion of the lab was to create help topics so users can categorize there issues. Good example of help topics include, password reset, business critical outage, and personal computer issues. 
</p>
<br />
