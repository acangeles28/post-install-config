<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines post-installation and a few system administration tasks of the open-source help desk ticketing system osTicket. <br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10 
<h2>List of Prerequisites</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Installation Steps</h2>

<p>Configure Roles (for grouping permissions)
  
  - In this tutorial, we will add a "Supreme Admin" role to provide full access. Note this is not recommended in real-world scenarios, as roles should be configured to grant specific permissions to all users.
</p>

![add new role](https://github.com/user-attachments/assets/c509ceec-7e9b-497c-9f81-3c6f89fdffcb)
![configure roles](https://github.com/user-attachments/assets/d713feef-1cb8-4557-821b-e80d56e01f7e)

<p>Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking</p>

  - Each agent is assigned to a specific department based on their role within the helpdesk. In this tutorial,  "System Administrators" department will be created, where the Supreme Admins will be assigned.

![configure departments](https://github.com/user-attachments/assets/7d4a71d8-9241-4f3a-a178-6ac5ebdac008)

<p>Configure Teams</p>

  - This section allows you to organize teams for specific issues that may arise

![configure teams](https://github.com/user-attachments/assets/92d94d40-dad6-44fe-8ac9-0552897397a0)

<p>Configure Agents (employees) </p>

  - Agents are employees of the helpdesk responsible for resolving tickets submitted by users. They are assigned to a primary department and given specific roles for tickets.
  - They can also be granted access to other departments and roles, depending on the permissions.

<img width="952" alt="Configure agents" src="https://github.com/user-attachments/assets/e41b82ba-73ff-42a9-b1f6-277283b35222" />

![agent jane doe](https://github.com/user-attachments/assets/99177a7d-5a25-4d08-b0eb-79634d368a48)

<p>Configure Users (customers)</p>

  - Users are customers who create tickets when issues arise. Users are usually identifed by email addresses.

![create user](https://github.com/user-attachments/assets/b2654a0f-d5ad-4b91-adcc-26c0f9e8ca23)

<p>Configure SLA (Service Level Agreement) </p>

  - SLA's are the expected time frame within which helpdesk agents should resolve a ticket.
  - Each SLA plan is created ahead of time and associated with a schedule and grace period.
  - All tickets are assigned a specific SLA depending on severity of the issue.   

<img width="952" alt="SLA" src="https://github.com/user-attachments/assets/37e86237-3b26-46b7-ae10-f674d0075485" />

<p>Configure Help Topics (For when users create a ticket)<p/>

  - Help topics direct end users to categoize the type of issue they have. 

<img width="960" alt="Help topic 1" src="https://github.com/user-attachments/assets/d7833639-a4f3-451c-a082-758cb547d8b6" />
<img width="953" alt="Help topic 2" src="https://github.com/user-attachments/assets/7e73427a-0521-4f48-a4af-9f424201bc1a" />



