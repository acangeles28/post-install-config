<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
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

![add new role](https://github.com/user-attachments/assets/05dbab60-cef5-44f4-bd8a-2c1d7f3fe631)
![configure roles](https://github.com/user-attachments/assets/1a8e1f61-dc58-47ea-a53f-b1bc3f312c67)

<p>Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking</p>

  - Each agent is assigned to a specific department based on their role within the helpdesk. In this tutorial,  "System Administrators" department will be created, where the Supreme Admins will be assigned.

![configure departments](https://github.com/user-attachments/assets/a50dabf7-d5fa-48cf-8bd8-bad3083e6c4b)

<p>Configure Teams</p>

  - This section allows you to organize teams for specific issues that may arise

![configure teams](https://github.com/user-attachments/assets/48dfdd41-37be-4603-9581-21ade3120420)

<p>Configure Agents (employees) </p>

  - Agents are employees of the helpdesk responsibvle for resolving tickets submitted by users. They are assigned to a primary department and given specific roles for tickets.
  - They can also be granted access to other departments and roles, depending on the permissions.

<img width="952" alt="Configure agents" src="https://github.com/user-attachments/assets/c383c796-a653-4be7-abc2-7bc1fef9256d" />

<p>Configure Users (customers)</p>

  - Users are customers who create tickets when issues arise. Users are usually identifed by email addresses.

![create user](https://github.com/user-attachments/assets/f437ed4a-8081-495f-aa96-acfea0b162e6)

<p>Configure SLA (Service Level Agreement) </p>

  - SLA's are the expected time frame within which helpdesk agents should resolve a ticket. Each SLA plan is associated with a schedule and grace period depending on severity of the issue. 
