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

- Create and configure roles
- Create and configure departments 
- Create and configure teams
- Create and configure agents and users
- Configure SLA
- Configure help desk topics

<h2>Configuration Steps</h2>

-  Sign into osTicket system as an admin https://localhost/osTicket/scp/login.php
-  In the top left there is a "agent panel" and a "admin panel" tabs to switch back and forth. (it will say Agent when you are in the Admin panel you will click Agent to switch)
-  Configure Roles from Admin panel
-  Admin Panel -> Agents -> Roles -> add
-  Name new agent Supreme Admin -> click all boxes
-  click permissions tab -> click everything -> add role -> save


<p>
<img src="https://imgur.com/ETrEen3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
roles

-  Configure Departments
-  Admin Panel -> Agents -> Departments -> add department
-  Name new department System Administrators -> keep default settings for now -> create department

</p>
<br />

<p>
<img src="https://imgur.com/w9pAPHi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
departments

-  Configure Teams
-  Admin Panel -> Agents -> Teams
-  Name first team Level I Support -> We won't add any users just create team
-  Name second team Level II Support -> We won't add any users just create team
-  Allow anyone to create tickets
-  Admin Panel -> Settings -> User Settings -> make sure registration required is UNchecked
  


</p>
<br />

<p>
<img src="https://imgur.com/eeO8zeF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
teams

-  Configure Agents (workers)
-  Admin Panel -> Agents -> Add New
-  Name first agent Jane Doe
-  Create credentials for both and save then for future use
-  Click set set password button after username  
-  On set agent password UNcheck "send the agent a password reset email" -> UNcheck "require password change at next login" -> click set
-  Under the access tab -> primary department is system admin, supreme admin -> under Teams select level II agent -> create.
-  Name the second John Doe -> same settings as Jane


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
-  Switch to Agent Panel -> Users -> Add New
-  Karen Doe -> make up email Karen@osTicket.com for example
-  Ken Doe

</p>
<br />

<p>
<img src="https://imgur.com/KRhFvRv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
users

-  Configure SLA
-  Switch back to Admin Panel -> Manage -> SLA
-  Name the first one Sev-A -> grace period set for 1 hour-> schedule 24/7 -> add plan
-  Name the second on Sev-B -> grace period 4 hours -> schedule 24/7
-  Name the third Sev-C grace period 8 hours -> Monday-Friday 8am-5pm with US holidays

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
-  Admin Panel -> Manage -> Help Topics -> add new 
-  Name the first one Business Critical Outage -> make all the "parent topic" top-level topic (default setting) -> Add topic -> save changes
-  Name the second Personal Computer Issues
-  Name the third Equipment Request
-  Name the fourth Password Reset

</p>
<br />

<p>
<img src="https://imgur.com/96eADGP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
help topics
</p>
<br />
