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

- Configure roles
- Configure departments
- Configure teams
- Allow anyone to create tickets
- Configure agents (workers)
- Configure users (customers)
- Configure SLA
- Configurre help topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/85Xb63U.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here I clicked on admin panel, navigated to agents, roles, then added new role to manage user roles. This process allows you to group users by their role and control the level of access and permissions for each group within the system.
</p>
<br />

<p>
<img src="https://i.imgur.com/dA3pXlh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here I clicked on admin panel, navigated to agents, departments, then under agents section, add new department to create and manage departments within the system. This configuration allows for better organization and control over who can access and manage different types of support tickets based on department specialization.
</p>
<br />

<p>
<img src="https://i.imgur.com/D6l7vTW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here I clicked on admin panel, navigated to agents, team, then add new team to create and manage teams within the system. This setup allows you to organize agents from various departments into teams for better collaboration and task management.
</p>
<br />

<p>
<img src="https://i.imgur.com/xnhejCl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here I clicked on admin panel, navigated to settings, then user settings. I left the "unregistered users can crrate tickets" unchecked. This will disable the ability for unregistered users to create tickets. Then enabled "registration required". This configuration ensures that only registered users can submit tickets, providing more control over ticket creation and user access.
</p>
<br />

<p>
<img src="https://i.imgur.com/16VDMjR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here I clicked on admin panel, navigated to agents, then selected add new agents to create new agent profiles. This process creates new agents, assigns them to the appropriate departments, and allows them to start working within the system
</p>
<br />

<p>
<img src="https://i.imgur.com/g3TxU74.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here I clicked on admin panel, navigated to users, then selected add new user. This process creates new customer accounts, allowing them to submit and track support tickets within the osTicket system. 
</p>
<br />

<p>
<img src="https://i.imgur.com/0r9Fh3M.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here I clicked on admin panel, navigated to manage, SLA , then selected add new SLA plan to configure different service levels. This configuration defines different SLAs based on severity, specifying grace periods and when they are applicable (24/7 or business hours).
</p>
<br />

<p>
<img src="https://i.imgur.com/fDhjTwk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here I clicked on admin panel, navigate to manage, then selected help topics. These help topics help categorize incoming support tickets, making it easier for agents to manage and respond to them based on the type of issue.
</p>
<br />


