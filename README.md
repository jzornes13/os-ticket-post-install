# os-ticket-post-install
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

- create and configure roles
- create and configure departments 
- create and configure teams
- create and configure agents and users
- configure SLA
- configure help desk topics

<h2>Configuration Steps</h2>

-  Configure Roles
-  Admin Panel -> Agents -> Roles
-  Supreme Admin


<p>
<img src="https://imgur.com/ETrEen3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
roles

-  Configure Departments
-  Admin Panel -> Agents -> Departments
-  System Administrators

</p>
<br />

<p>
<img src="https://imgur.com/w9pAPHi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
departments

-  Configure Teams
-  Admin Panel -> Agents -> Teams
-  Level I Support
-  Level II Support
-  Allow anyone to create tickets
-  Admin Panel -> Settings -> User Settings
-  Registration Required: Require registration and login to create tickets 


</p>
<br />

<p>
<img src="https://imgur.com/eeO8zeF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
teams

-  Configure Agents (workers)
-  Admin Panel -> Agents -> Add New
-  Jane
-  John

</p>
<br />

<p>
<img src="https://imgur.com/B9jE1t8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
agent
</p>
<br />

<p>
<img src="https://imgur.com/Tu2VvQd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
agents

-  Configure Users (customers)
-  Agent Panel -> Users -> Add New
-  Karen
-  Ken

</p>
<br />

<p>
<img src="https://imgur.com/KRhFvRv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
users

-  Configure SLA
-  Admin Panel -> Manage -> SLA
-  Sev-A (1 hour, 24/7)
-  Sev-B (4 hours, 24/7)
-  Sev-C (8 hours, business hours)

</p>
<br />

<p>
<img src="https://imgur.com/Mfi51ik.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Sla
</p>
<br />

<p>
<img src="https://imgur.com/RiLyieb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Slas

-  Configure Help Topics
-  Admin Panel -> Manage -> Help Topics
-  Business Critical Outage
-  Personal Computer Issues
-  Equipment Request
-  Password Reset

</p>
<br />

<p>
<img src="https://imgur.com/96eADGP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
help topics
</p>
<br />
