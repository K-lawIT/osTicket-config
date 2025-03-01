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

- Configure Roles, Departments, and Teams
- Configure Agents 
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

![osTicketlab13](https://github.com/user-attachments/assets/fa9f8e6c-bc0f-4754-971b-223c3b64a491)


<p>
<img src="" height="80%" width="80%" alt="Department configuration"/>
</p>
<p>
To create a new Department, visit the Admin Panel -> Agents -> Departments. Once there, click "create new Department".
</p>
<br />

![osTicketlab14](https://github.com/user-attachments/assets/6e6bdf46-fc26-4320-b754-90ab4748efd6)


<p>
<img src="" height="80%" width="80%" alt="Creating an Agent"/>
</p>
<p>
Creating an agent in osTicket is simple. To create a new agent (employee), open the Admin Panel -> Agents -> Add New.
</p>
<br />

![osTicketlab18](https://github.com/user-attachments/assets/96934bf1-37c2-4c9b-b550-0117dd57eb29)


<p>
<img src="" height="80%" width="80%" alt="Configure SLA"/>
</p>
<p>
Navigate from the Admin panel -> Manage -> SLA.
  Standard SLA is typically: 
  SEV-A (Grace Period: 1 hour, Schedule: 24/7)
  SEV-B (Grace Period: 4 hours, Schedule: 24/7)
  SEV-C (Grace Period: 8 hours, Business Hours)
</p>
<br />
