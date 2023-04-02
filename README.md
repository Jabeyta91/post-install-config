<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

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
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/mTXmUj5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To begin post installation as a administrator I began to define the roles for agaents per department. By giving people who have "Supreme Admin" roles permissions to create and delete tickets. This can be done by clicking Admin Panel -> Agents -> Roles. Since tickets are routed through different departments within a help desk there are many settings per department. To create a department for an assignment you can access it by clicking Admin Panel -> Agents -> Departments.
</p>
<br />

<p>
<img src="https://i.imgur.com/cqc1FNt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next step is creating teams as for instance the best technicians from each department to form a team to handle specific issues. Consisting of level 1 or level 2 for instance support agents. As a administrator I can assign each agent different departments and roles. 
</p>
<br />

<p>
<img src="https://i.imgur.com/GNAXEMJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Finally, Service Level Agreements can have a variety of meaning but for my administrative purpose I will try to keep it simple. To configure a service level agreement I went to Admin Panel -> Manage -> SLA. Ive created 3 SLA's Sev-A (1 hour, 24/7), Sev-B (4 hours, 24/7), Sev-C (8 hours, business hours) each with their own level of importance. For schedule on SEV-A I chose 24/7 with a grace period of 1 hour meaning despite if its a sunday at 10 p.m. the ticket needs to be resolved by 11 p.m. As for instance with SEV-C a schedule of Monday-Friday with a 8 hour grace period meaning if a ticket arises at 2 p.m. Friday we have 3 hours on Friday then another 5 hours on Monday. 
</p>
<br />
