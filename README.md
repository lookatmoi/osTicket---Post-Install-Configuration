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

-Admin/Analyst Login Page:
http://localhost/osTicket/scp/login.php 

-End Users osTicket URL:
http://localhost/osTicket 

- Acknowledge Agent Panel vs Admin Panel

- Configure Roles (for grouping permissions)


<h2>Configuration Steps</h2>

Acknowledge Agent Panel vs Admin Panel
<img width="1855" height="937" alt="image" src="https://github.com/user-attachments/assets/751c1506-e994-4539-86fc-fab3b06d530d" />
<img width="1549" height="913" alt="image" src="https://github.com/user-attachments/assets/cb34fdb4-c149-4fd9-93f8-dfd169571ec9" />


Configure Roles (for grouping permissions)
Admin Panel -> Agents -> Roles
Supreme Admin

Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
Admin Panel -> Agents -> Departments
SysAdmins
<img width="1024" height="901" alt="image" src="https://github.com/user-attachments/assets/e51a4a54-46c1-4622-b589-1a0c4fd34225" />


Configure Teams
Admin Panel -> Agents -> Teams (Pull Agents from different Departments)
Online Banking

Allow anyone to create tickets
Admin Panel -> Settings -> User Settings (UNCHECK: unregistered users can create tickets)
Registration Required: Require registration and login to create tickets 

Configure Agents (workers)
Admin Panel -> Agents -> Add New
Jane (Dept: SysAdmins)
John (Dept: Support)
<img width="1501" height="718" alt="image" src="https://github.com/user-attachments/assets/06a501a9-1964-4bbc-b224-2b0d1e074cf3" />

Configure Users (customers)
Agent Panel -> Users -> Add New
Karen
Ken
<img width="1813" height="937" alt="image" src="https://github.com/user-attachments/assets/173dadde-ee3a-4882-af83-b6a08c61b149" />


Configure SLA
Admin Panel -> Manage -> SLA
Sev-A (Grace Period: 1 hour, Schedule: 24/7)
Sev-B (Grace Period: 4 hours, Schedule: 24/7)
Sev-C (Grace Period: 8 hours, Business Hours)
<img width="1207" height="391" alt="image" src="https://github.com/user-attachments/assets/41a582fb-b995-4dd2-94b2-fd677a11547c" />

Configure Help Topics (For when users create a ticket)
Admin Panel -> Manage -> Help Topics
Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset
Other
<img width="1204" height="646" alt="image" src="https://github.com/user-attachments/assets/9cf9771f-8856-4a08-92e0-7543039fcf6c" />











<p>
</p>
<p>

</p>
<br />

<p>

</p>
<p>

</p>
<br />

<p>

</p>
<p>

</p>
<br />
