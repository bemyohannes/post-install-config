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

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents (employees)
- Configure Users (customers)
- Configure Service Level Agreements (SLAs)
- Configure to allow anyone to create tickets
- Configure Roles

<h2>Configuration Steps</h2>

<h3>Configure Roles</h3>

Roles are the permissions granted to Agents (employees) for the Departments they have access to. 


Login to osTicket and make sure it says Agent Panel (located in the top right corner – if you see Agent Panel that means you are in Admin Panel and if you see Admin Panel it means you are in Agent Panel). You will need to complete the below steps from Admin Panel, so make sure you see Agent Panel.

-	From within Admin Panel click Agents tab >
-	Click Roles >
-	Click Add New Role

You can create and assign an unlimited number of roles to Agents with access to various departments and also set permissions for the roles

<p>
<img src="https://i.imgur.com/v8SThbB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h3>Configure Departments</h3>

-	From within Admin Panel click Agents tab >
-	Click Departments >
-	Click Add New Department

Because tickets are routed through the various Departments in the help desk, there are many settings that can be set for each Department

<p>
<img src="https://i.imgur.com/hU98eFk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h3>Configure Teams</h3>

Teams are groups of agents from different departments that handle particular issues or users

-	From within Admin Panel click Agents tab >
-	Click Teams >
-	Click Add New Team

You can fill out the appropriate information and add agents from various departments as team members 

<p>
<img src="https://i.imgur.com/Ys4rbRT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h3>Configure Agents (employees)</h3>

Agents are the employees that respond to and resolve tickets

-	From within Admin Panel click Agents tab >
-	Click Agents >
-	Click Add New Agent

You will need to assign your agents to a Primary Department and give them Primary Roles for the tickets/tasks routed to that department 

<p>
<img src="https://i.imgur.com/RrtJnQ8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h3>Configure Users (customers)</h3>

Users are the creators of the tickets in the help desk. Users are associated with their email address, which serves as their unique identifier when creating a ticket, in the User Directory of the help desk. 

-	From within Agent Panel (remember to make sure you see Admin Panel, which means you are in Agent Panel) click Users tab >
-	Click Add User

<p>
<img src="https://i.imgur.com/ynTfg4E.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h3>Configure Service Level Agreements (SLAs)</h3>

SLAs are used to define the timeline that agents have to complete and close open tickets.

-	From within Admin Panel (make sure you see Agent Panel) click Manage tab >
-	Click SLA >
-	Click Add New SLA Plan

<p>
<img src="https://i.imgur.com/Wq3xXjn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h3>Configure Help Topics</h3>

Help Topics will allow users to identify the kinds of issues associated with their tickets and they will also determine to which Department the tickets will be sent.

-	From within Admin Panel click Manage tab >
-	Click Help Topics >
-	Click Add New Help Topic

<p>
<img src="https://i.imgur.com/vWCz5q3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>


<p>
<img src="https://i.imgur.com/Wq3xXjn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<h3>Configure to allow anyone to create tickets</h3>

-	From within Admin Panel click Settings tab >
-	Click Users >
-	Within Users Settings, under Authentication Settings, make sure Registration Required is unchecked

<p>
<img src="https://i.imgur.com/vOAJ151.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/RrtJnQ8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
