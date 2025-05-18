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

-	Roles
- Departments
- Teams
- Agents (workers)
- Users (customers)
- Help Topics
- Service Level Agreements (SLAs)

<h2>Configuration Steps</h2>

![ADMINnENDUSERS](https://github.com/user-attachments/assets/148e286d-e2a9-4393-89ed-732ad0f5e99e)

- These 2 pages displayed is the general end user's ticket submission page and on the right is for actual help desk agents to manage, create, and/or resolve tickets
- There is an admin panel and agent panel, self explanatory. agents deal with the actual tickts and admins configure the application/program
- 


![ROLE](https://github.com/user-attachments/assets/b2949d29-a1d9-44bd-9f6d-c09e74265f88)
![ROLE CUSTOM](https://github.com/user-attachments/assets/c4d4db0b-ed89-4026-9c1b-743c80c1638c)

- within roles you are assigning levels of access, roles is meant to group permissions
- the generic access is all, expanded, limited, view
- you can create your own level of access and customize how you'd like under permissions
- You can also activate and disable different roles as you may not always want to delete them

![DEPARTMENT](https://github.com/user-attachments/assets/ec2b95b9-8102-4c88-897d-3358839ca45a)
![DEPARTMENT2](https://github.com/user-attachments/assets/713488c2-d865-4019-8517-778e74e846ee)

- Departments can be located under agents as well but in its own tab
- Departments are to seperate diffent divisions of an orgaization
- Can be used to set ticket visibility and establish a network for a single division

![TEAMS](https://github.com/user-attachments/assets/957cedb8-40ad-4ef6-bc2d-4c00e97ced50)
![TEAM2](https://github.com/user-attachments/assets/02d4e626-87c4-4af6-8137-fff064005e3c)

- Teams is another tab within agents
- Teams is more used to pull from multiple departments, typicallly where you see cross-functional teams put together

![USER SETTINGS](https://github.com/user-attachments/assets/3d17f943-dd11-4b3a-9fd5-834653ec3ed6)

- User settings is where mass adjustments are made and/or dictate how users interact with osTicket
- 
![NEW AGENT](https://github.com/user-attachments/assets/78717b6b-64be-4c58-9b21-3c74332b65ce)
![NEW AGENT ACCESS](https://github.com/user-attachments/assets/bc5aa61d-9003-4d4d-a780-b90111db39fa)
![NEW AGENT PERMISSION](https://github.com/user-attachments/assets/e5c4d2ec-0b66-485e-b420-36e8420dbfe7)
![NEW AGENT TEAMS](https://github.com/user-attachments/assets/eb35479b-18a5-47f8-8a9e-320f311e8edd)

- Adding users is under the agents tab of agents
- Here is where all user information is filled to be created, granted access, permissions, and assigned a team
- personal and generic info is store to create an account, create more agents

![image](https://github.com/user-attachments/assets/549411e1-5a59-4378-bcbb-c6c054a47051)

- going into the agent panel, a look from a help desk agents perspective is displayed in the image above
- Users can be created from their users tab adnd clicking "add user"
- These users are geerally end-users, more than likely putting in the tickets
- 

![SLA](https://github.com/user-attachments/assets/7b741e85-49ed-4740-9dcc-982d4fdb8094)
![SLA2](https://github.com/user-attachments/assets/dc86f22a-66be-4262-9f46-7ea7f8b37eb6)

- SLA's or Service Level Agreements are the expected levels of service(performance, responsibilities, and consequences)
- The standards are set here and can different SLA's can be assigned to individual tckets

![HELP TOPICS](https://github.com/user-attachments/assets/4ad95630-e312-4f44-bb0a-e09997d7cdc4)

- Help topics are for when users create a ticket they can generalize their issue, typically helps with getting them to the right person
And thats pretty much the in's and out from an admin and general agent usage
