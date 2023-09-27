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

- Create an Admin role
- Create a Department
- Create a Team
- Add Agents (employees)
- Add Users (customers)
- Create SLAs
- Add Help Topics

<h2>Configuration Steps</h2>

<p>
<img width="1026" alt="Screen Shot 2023-09-26 at 2 24 07 PM" src="https://github.com/ChMacedo/post-install-config/assets/103891128/d4e04805-95c8-4e13-a40d-6ab87c4e27a9">

</p>
<p>
Remote desktop into the virtual machine, made in osTicket - Prerequisites and Installation. Then login from the help desk login page  <br />
http://localhost/osTicket/scp/login.php
</p>
<br />

<p>
<img width="718" alt="Screen Shot 2023-09-26 at 4 03 19 PM" src="https://github.com/ChMacedo/post-install-config/assets/103891128/9d4b667a-e774-4721-a183-396c0875ed01">

</p>
<p>
Create an admin role  <br />
From the Admin Panel, add a Supreme Admin role, and under the permissions tab allow every permission.
</p>
<br />

<p>
<img width="961" alt="Screen Shot 2023-09-26 at 2 39 24 PM" src="https://github.com/ChMacedo/post-install-config/assets/103891128/d322eb56-f668-4ef9-a0b1-fbfa5a1c7f8c">

</p>
<p>
Create Departments  <br />
Create the department System Administrator.
</p>
<br />

<p>
<img width="968" alt="Screen Shot 2023-09-26 at 2 34 09 PM" src="https://github.com/ChMacedo/post-install-config/assets/103891128/b2094de2-e002-47cc-a7c9-721d2e98b609">
</p>
<p>
Create Teams  <br />
Create a Level II Support team, Level I is created by default.
</p>
<br />

<p>
<img width="961" alt="Screen Shot 2023-09-26 at 2 38 18 PM" src="https://github.com/ChMacedo/post-install-config/assets/103891128/d421444e-6d86-4c15-acaf-5bb2e672d4a6">
<img width="944" alt="Screen Shot 2023-09-26 at 2 50 04 PM" src="https://github.com/ChMacedo/post-install-config/assets/103891128/9626542e-799c-4cd6-90df-329a71eb9eb4">

</p>
<p>
Add Agents (workers)  <br />
Create 2 agents, Jane Doe and John Doe. <br />
Jane Doe  <br />
- supreme admin (role)  <br />
- System Administrator (department)  <br />
- Level II Support (team)  <br />
John Doe  <br />
- support (role)  <br />
- view only  <br />
</p>
<br />

<p>
<img width="944" alt="Screen Shot 2023-09-26 at 2 54 35 PM" src="https://github.com/ChMacedo/post-install-config/assets/103891128/16e8b7c3-3935-4e27-ba34-90ad4248e35d">
<img width="944" alt="Screen Shot 2023-09-26 at 2 59 38 PM" src="https://github.com/ChMacedo/post-install-config/assets/103891128/a8532a11-8928-419b-aeb2-499702d9a583">
</p>
<p>
Add Users  <br />
Switch to the Agent Panel and add Karen and Ken as users.
</p>
<br />

<p>
<img width="944" alt="Screen Shot 2023-09-26 at 3 01 39 PM" src="https://github.com/ChMacedo/post-install-config/assets/103891128/2e50548e-a9fa-44af-a9ea-58c421b9d2ca">
<img width="944" alt="Screen Shot 2023-09-26 at 3 01 39 PM" src="https://github.com/ChMacedo/post-install-config/assets/103891128/ad78eab3-335c-455f-b49e-5f52113dd2fe">
<img width="944" alt="Screen Shot 2023-09-26 at 3 01 39 PM" src="https://github.com/ChMacedo/post-install-config/assets/103891128/caebaf68-612a-4377-9652-70778227b650">
</p>
<p>
Create SLA  <br />
Switch back to the Admin Panel and create 3 SLAs <br />
1. SEV-A (1 hour, 24/7)  <br />
2. SEV-B (4 hours, 24/7)  <br />
3. SEV-C (8 hours, business hours)
</p>
<br />

<p>
<img width="954" alt="Screen Shot 2023-09-26 at 3 08 10 PM" src="https://github.com/ChMacedo/post-install-config/assets/103891128/9df433d1-c626-456e-9eca-b1bdfade0961">
</p>
<p>
Add Help Topics  <br />
Add the following Help Topics, osTicket has some help topics by default.  <br />
1. Business Critical Outage  <br />
2. Personal Computer Issues  <br />
3. Equipment Request  <br />
4. Password Reset  <br />
 <br />
Post configuration is complete! Now you have everything you need to start making ticktes.

</p>
<br />
