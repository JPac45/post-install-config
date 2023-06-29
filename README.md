<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />




<h2>Environments and Technologies Used</h2>

- osTicket (Help Desk Ticketing System)
- PHP

<h2>Operating Systems Used </h2>

- Windows 10</b>

<h2>Configuration Steps</h2>

<b>Configure Roles in Admin panel</b>

- Open osTicket via help desk login page: http://localhost/osTicket/scp/login.php
- Admin Panel > Agents > Roles > Add New Role > Type "Supreme Admin" in Name: field > Permissions > Check all boxes under Tabs: Tickets, Tasks, Knowledgebase > Save Changes
- NOTE: To switch between the admin and agent panel look at the top of the page. If it reads Admin panel it means you are in the Agent panel. If it reads Agent panel then you are in the Admin panel.
  
<p>
<img src="https://i.imgur.com/Y1d5VRy.gif"/>
</p>
<p>
</p>
<br />

<b>Configure Departments</b>

- Admin Panel > Agents > Departments > Add New Department > Type "System Administrators" in Name: field > Create Dept
  
<p>
<img src="https://i.imgur.com/qeLFdJG.gif"/>
</p>
<p>
</p>
<br />

<b>Configure Teams</b>

- Admin Panel > Agents > Teams > Add Teams (create Level II Support)  > Type "Level II Support" in Name: field > Members > Select an Agent on the drop down menu > Create Team
  
<p>
<img src="https://i.imgur.com/Unm0Rz9.gif"/>
</p>
<p>
</p>
<br />

<b>Allow anyone to create tickets</b>

- Admin Panel > Settings > Users > Check Require registration and login to create tickets > Save Changes

  
<p>
<img src="https://i.imgur.com/ysXHga0.png"/>
</p>
<p>
</p>
<br />

<b>Configure Agents(workers)</b>

- Admin Panel > Agents > Add New Agents  > Fill out Name:, Email Address:, Username: fields > Set Password > Uncheck Send the agent a password reset email > Create new password and confirm > Uncheck Require password change at next login > Set
- Access tab > Select Department, Select Role, Extended Access Department from drop down menus > Teams tab > Select Team from drop down menu > Add > Create

  
<p>
<img src="https://i.imgur.com/GIChHwM.gif"/>
</p>
<p>
</p>
<br />

<b>Configure Users(customers)</b>

- Agent Panel > Users > Add Users  > Fill out Email Address: and Full Name: fields > Add User
- Create another user i.e. "Ken" using same  steps above
  
<p>
<img src="https://i.imgur.com/ZanFET3.gif"/>
</p>
<p>
</p>
<br />

<b>Configure SLA</b>

- Admin Panel > Manage > SLA
  1. Sev-A (1 hour, 24/7)
  2. Sev-B (4 hours, 24/7)
  3. Sev-C (8 hours, business hours)

  
<p>
<img src=""/>
</p>
<p>
</p>
<br />

<b>Configure Help Topics</b>

- Admin Panel > Agents > Teams > Add Teams (create Level II Support)  > Type "Level II Support" in Name: field > Members > Select an Agent on the drop down menu > Create Team
  
<p>
<img src=""/>
</p>
<p>
</p>
