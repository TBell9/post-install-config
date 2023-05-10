<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post Configuration Setup</h1>
</p>
This tutorial demonstrates the post configuration setup of the osTicket system .<br />
<p>

<p>
Now we will focus on some system administration and work on some post installation setup.
First we will configure new roles within the help desk. 
In order to do so go to Admin panel-> Agents-> Roles. Create a Supreme Admin. 
Click on "Add new role" then enter the name of the new role. You can also modify any specific roles permissions. In this case since we are creating a Supreme Admin, they will be given all permissions. Keep in mind roles are used to determine an agents permissions so not all agents will have unlimited access.

<img src="https://i.imgur.com/XHteqdt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Select the "Departments" button in the agents tab. We are going to create a new department. Each Agent is assigned to a specific department depending on their assigned role within the helpdesk. In this case we will be creating the "System Administrators" department, this is where the Supreme Admins will be designated. Other specific settings such as SLAs, managers and other email settings can be set up in the departments tab. 
</p>
<br />

<p>
<img src="https://i.imgur.com/dGK0RVM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now we will set up a new team. Teams allow you to pull agents from different departments you can have an A team that has top technicians from specific departments. To set up a team go to Agents->Teams. A Level I support team has been created by default, in this example we will create a Level II Support Team. 
</p>
<br />

<p>
<img src="https://i.imgur.com/cYzWBD2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next we'll create a new setting that will allow anyone to create tickets. Admin Panel->Settings->User Settings.
</p>
<br />

<img src="https://i.imgur.com/H1q2Fdh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
Here we are going to create Agents. Agents are the employees of the helpdesk that actually work on solving tickets. Agents are assigned primary departments and given a primary role for tickets sent to their department. Agents can be given access to other departments other than their own, they can also have different roles depending on which department they are in. Permissions, Access, and Teams are be assigned in the Agents tab. 
</p>
<br />
<img src="https://i.imgur.com/8WTOSre.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<p>
After the agents we'll create users. Users are customers that create tickets when they are having issues. To create a user follow this path Agent Panel->Users->User Directory->Add new. 
</p>
<br />
<img src="https://i.imgur.com/xOprA9f.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<p>
SLA Plans provide a length of time in which the help desk is expected to take in order to solve a specific ticket. To create a SLA Plans go to Admin Panel->Manage->SLA Plans. Each SLA has a schedule and within that schedule there is a grace period. In this example SEV-A has a 24/7 and a one hour grace period. 
</p>
<br />

<img src="https://i.imgur.com/LpjCaLd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
Help topics help users categorize their tickets. In the example below we have made a help topic for "Business Critical Outage" this can be if customers cannot access mobile banking. 
</p>
<br />

<img src="https://i.imgur.com/kB7rts2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
