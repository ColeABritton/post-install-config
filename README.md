<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial will focus on administering roles, departments, and permissions to newly created agents. Also, creating and configuring SLAs and Help Topics.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure
- Remote Desktop
- osTicket
<h2>Operating Systems Used </h2>

- Windows 10 Pro</b>

<h2>Configuration Steps</h2>

<p>
Open osTicket and access the Admin Panel by clicking the header located at the top right of the webpage.
<img src="https://i.imgur.com/nyZ7iqM.png" height="80%" width="80%" alt="osTicket Admin Panel"/>
<br />
<br />
Add a new role by navigating to Agents -> Roles -> Add New Role. For this example we will name it Supreme Admin and enable all permissions under Tickets, Tasks, and Knowledgebase.
<img src="https://i.imgur.com/soiZlyn.png" height="80%" width="80%" alt="Create New Role"/>
<br />
<br />
Add a new department by navigating to Agents -> Departments -> Add New Department. For this example we will name it System Administrators, and leave the remaining settings at default.
<img src="https://i.imgur.com/98Z0v7E.png" height="80%" width="80%" alt="Create New Department"/>
<br />
<br />
Add a new team by navigating to Agents -> Teams -> Add New Team. For this example we will name it Online Banking, and leave the remaining settings at default.
<img src="https://i.imgur.com/7p6VuhK.png" height="80%" width="80%" alt="Create New Team"/>
<br />
<br />
Now navigate to Settings -> Users -> Authentication Settings. Now, make sure to uncheck 'Require registration and login to create tickets.' This will ensure end-users can create new tickets without creating and logging into an account.
  
<img src="https://i.imgur.com/U8CXBuw.png" height="80%" width="80%" alt="Allow Ticket Creation Without Login"/>
<br />
<br />
Add a new agent by navigating to Agents -> Agents -> Create New Agent. Fill in the necesarry credentials name, email address, and username.
<img src="https://i.imgur.com/Vccv5qF.png" height="80%" width="80%" alt="Create Agent Jane"/>
<br />
<br />
Under Authentication click 'Set Password' and type the password twice. Now, uncheck both 'Send the agent a password reset email' and 'Require password chage at next login' then Set.
<img src="https://i.imgur.com/1LuNJdn.png" height="80%" width="80%" alt="Set Jane Password"/>
<br />
<br />
Navigate to the new agents Access panel, select System Admins department, and Supreme Admin role.
<img src="https://i.imgur.com/OUIlCO7.png" height="80%" width="80%" alt="Edit Jane Department"/>
<br />
<br />
Navigate to the new agents Teams panel, and select Online Banking team then Create.
<img src="https://i.imgur.com/1wTowJT.png" height="80%" width="80%" alt="Edit Jane Team"/>
<br />
<br />
Create a second agent filling in the credentials and following the previous 'Set Password' step. Now navigate to the agents Access panel and select the Support department then Create.
<img src="https://i.imgur.com/e5mYLMz.png" height="80%" width="80%" alt="Create Agent John"/>
<img src="https://i.imgur.com/9NAXbUG.png" height="80%" width="80%" alt="Edit John Department "/>
<br />
<br />
Observe the newly created agents and their departments within the Agents tab.
<img src="https://i.imgur.com/TOZBXBn.png" height="80%" width="80%" alt="Observe Newly Created Agents"/>
<br />
<br />
Now, access the Agents panel by clicking the header at the top right of the webpage. Navigate to Users -> Add User.
<img src="https://i.imgur.com/Z8JtISN.png" height="80%" width="80%" alt="Open Agent Panel"/>
<br />
<br />
We will create two end-users filling in the required fields Email Address and Full Name, then observe them within the User Directory.

<img src="https://i.imgur.com/aVbwbkw.png" height="80%" width="80%" alt="Create End-User Karen and Ken"/>
<img src="https://i.imgur.com/vU6vw5I.png" height="80%" width="80%" alt="Observe Nely Created End-Users"/>
<br />
<br />
Navigate to the Admin Panel -> Manage -> SLA -> Add New SLA Plan. We will create three SLAs with varying severities, then observe them within our Service Level Agreements.
<img src="https://i.imgur.com/mHB5J7W.png" height="80%" width="80%" alt="Create SLA Sev-A"/>
<img src="https://i.imgur.com/G1sQ2BL.png" height="80%" width="80%" alt="Create SLA Sev-B"/>
<img src="https://i.imgur.com/v2h1ECY.png" height="80%" width="80%" alt="Create SLA Sev-C"/>
<img src="https://i.imgur.com/Z4Gr3hJ.png" height="80%" width="80%" alt="Observe Newly Created SLA Agreements"/>
<br />
<br />
Navigate to Manage -> Help Topics -> Add New Help Topic. We will create four Help Topics to simulate possible day-to-day issues, then observe them within our Help Topics.
<img src="https://i.imgur.com/mYz1i3y.png" height="80%" width="80%" alt="Create New Help Topics"/>
<img src="https://i.imgur.com/NMPMfJt.png" height="80%" width="80%" alt="Observe Newly Created Help Topics"/>
<br />
<br />
<h2>osTicket Setup Complete!</h2>
With osTicket fully setup we can now simulate multiple mock tickets, and work them to completion to gain a better understanding of the systems osTicket has to offer.
<br />
