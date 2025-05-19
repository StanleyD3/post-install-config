<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket and its components

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

-	set up roles & permissions
- Create departments & teams
- Add and configure agents & users
- Establish Help Topics & SLA (Service Level Agreements) policies

<h2>Configuration Steps</h2>

![ADMINnENDUSERS](https://github.com/user-attachments/assets/148e286d-e2a9-4393-89ed-732ad0f5e99e)

- These 2 pages displayed is the general end user's ticket submission page and on the right is for actual help desk agents to manage, create, and/or resolve tickets
- osTicket provides two main interfaces:
  - User Panel: Where customers (end-users) submit and track tickets.
  - Agent/Admin Panel: Where help desk staff manage tickets and system settings.
- Admins control system-wide settings, while agents primarily resolve tickets.

**ROLES**
![ROLE](https://github.com/user-attachments/assets/b2949d29-a1d9-44bd-9f6d-c09e74265f88)
![ROLE CUSTOM](https://github.com/user-attachments/assets/c4d4db0b-ed89-4026-9c1b-743c80c1638c)

- Roles define what agents are allowed to do within osTicket, assigns levels of access, roles is meant to group permissions
- Default access types include: View, Limited, Expanded, and Full.
- You can also create custom roles with granular permissions.
- Default and custome roles can be toggled on/off without deleting.

**DEPARTMENTS**
![DEPARTMENT](https://github.com/user-attachments/assets/ec2b95b9-8102-4c88-897d-3358839ca45a)
![DEPARTMENT2](https://github.com/user-attachments/assets/713488c2-d865-4019-8517-778e74e846ee)

- Departments can be located under agents as well but in its own tab
- Departments are used to organize tickets based on business divisions.
- You can restrict ticket visibility per department, helping define data access boundaries.
- Example: IT Support, HR Helpdesk, Billing — each with its own ticket queue.

**TEAMS**
![TEAMS](https://github.com/user-attachments/assets/957cedb8-40ad-4ef6-bc2d-4c00e97ced50)
![TEAM2](https://github.com/user-attachments/assets/02d4e626-87c4-4af6-8137-fff064005e3c)

- Teams is another tab within agents
- Teams allow you to build cross-functional groups of agents.
- Typically used when different departments need to collaborate.
- Can be set up to manage specific ticket types or complex request

**AGENT CONFIGURATION**
![USER SETTINGS](https://github.com/user-attachments/assets/3d17f943-dd11-4b3a-9fd5-834653ec3ed6)

- User settings is where mass adjustments are made and/or dictate how users interact with osTicket

![NEW AGENT](https://github.com/user-attachments/assets/78717b6b-64be-4c58-9b21-3c74332b65ce)
![NEW AGENT ACCESS](https://github.com/user-attachments/assets/bc5aa61d-9003-4d4d-a780-b90111db39fa)
![NEW AGENT PERMISSION](https://github.com/user-attachments/assets/e5c4d2ec-0b66-485e-b420-36e8420dbfe7)
![NEW AGENT TEAMS](https://github.com/user-attachments/assets/eb35479b-18a5-47f8-8a9e-320f311e8edd)

- Adding users is under the agents tab of agents
- Here is where user information is filled to be created, granted access, permissions, and assigned a team
- personal and generic info is stored to create pr adjust accounts
- Allows you to build a controlled agent environment with proper scope of access.

**USER MANAGEMENT**
![image](https://github.com/user-attachments/assets/549411e1-5a59-4378-bcbb-c6c054a47051)

- going into the agent panel, a look from a help desk agents perspective is displayed in the image above
- Users can be created from their users tab by clicking "add user", or when submitting a ticket
**SLA**
![SLA](https://github.com/user-attachments/assets/7b741e85-49ed-4740-9dcc-982d4fdb8094)
![SLA2](https://github.com/user-attachments/assets/dc86f22a-66be-4262-9f46-7ea7f8b37eb6)

- SLA's or Service Level Agreements identify what the expected levels of service are (performance, responsibilities, and consequences)
- Defining response and resolution expectations, multiple SLA plans can be created and different SLA's can be applied to different help topics or departments

**HELP TOPICS**
![HELP TOPICS](https://github.com/user-attachments/assets/4ad95630-e312-4f44-bb0a-e09997d7cdc4)

- Help Topics let users categorize their issue when submitting a ticket.
- Example topics: "Password Reset," "Network Issue," "Equipment Request."
- Helps with automatic routing and setting expectations from the start.
- Used to get users to the right person

**DONE**
This configuration ensures osTicket is not just installed, but optimized for real-world use. 
- You now have:
  - A structured team system
  - Clear responsibilities
  - Helpdesk logic mapped to real business needs
This setup simulates a production-ready environment reflecting modern IT support workflows.
