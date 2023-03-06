# <p align="center">
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

-Configure Roles

-Configure Deparetment

-Configure Teams

-Configure Agents(workers)

-Configure Users (customers)

-Configure SLA

-Configure Help Topics

<h2>Configuration Steps</h2>

<p> Configur Roles would be our first step and here are the steps to follow.

In our Admin panel, 
The steps are Select Agents tab = Roles = Add New Roles
- Name would be :Supreme Admin

- Select the right permission tab and then check every box under the "Ticket", "Tasks" and then "Knowledgebase" Section.
- Select Add Role


<a href="https://imgur.com/Wd8dXPM"><img src="https://i.imgur.com/Wd8dXPM.png" title="source: imgur.com" /></a>
</p>
<p> 
<h2>Configure Departments</h2>
 
- In the Admin Panel

The steps to follow are Select the Agents tab = Department = Add New Department, The name should be System Administrators.

- Then select create Department.

</p>
<br />
<img src=<a href="https://imgur.com/U3s8ObK"><img src="https://i.imgur.com/U3s8ObK.png" title="source: imgur.com" /></a>
<img src=<a href="https://imgur.com/H2GW9kH"><img src="https://i.imgur.com/H2GW9kH.png" title="source: imgur.com" /></a>
<p>
<h2>Configure Teams</h2>
In Admin Panel, The step would be Select Agents tab = Teams = Add New Teams
- Name would be: Level 11 Support.
- Go to the members tab and then select yourself in "Select Agent" dropdown meanu.
- Then lastly Select create team.
<img src=<a href="https://imgur.com/3awCTVn"><img src="https://i.imgur.com/3awCTVn.png" title="source: imgur.com" /></a>
<img src=<a href="https://imgur.com/1KUMqJp"><img src="https://i.imgur.com/1KUMqJp.png" title="source: imgur.com" /></a>
</p>
<p>
<h2>Open the Permissions to Allow Anyone to Create a Tickets</h2>
In the Admin Panel
- Select the settings = User Settigs.
- Make sure box the "Registration Required" It reguired that registration and login is created and the tickets is unchecked.
</p>
<br />
<img src=<a href="https://imgur.com/PKRc9Si"><img src="https://i.imgur.com/PKRc9Si.png" title="source: imgur.com" /></a>
<p>
 <h2>Configure Agents</h2>
In the admin panel
Select the Agents tab = Add New Agents

Name: Jane Doe

Email : jane.doe@osticket.com

Username: jane.doe

Click set password and uncheck box that says "send the agent a password reset email

Set your password

uncheck "require password change at next login" box
set
<a href="https://imgur.com/wlCvWax"><img src="https://i.imgur.com/wlCvWax.png" title="source: imgur.com" /></a>
<a href="https://imgur.com/xbM3Pqw"><img src="https://i.imgur.com/xbM3Pqw.png" title="source: imgur.com" /></a>
</p>
<p>
Select Access tab

 Under Primary Department

 -Select department dropdown menu -> System Administrators

 -Select Role dropdown menu -> Supreme Admin

 Extended Accesss

-Select Department -> Support -> Add -> Supreme Admin

 Select Teams tab

 -Select team dropdown menu -> Level II Support

 -Select Add

 Select Create
</p>
<img src=<a href="https://imgur.com/OMMn9br"><img src="https://i.imgur.com/OMMn9br.png" title="source: imgur.com" /></a>
<img src=<a href="https://imgur.com/BztqGod"><img src="https://i.imgur.com/BztqGod.png" title="source: imgur.com" /></a>
We can then Create another agent named john and repeat the process again.

Follow same steps as above with some changes to Primary Department

-Select department dropdown menu = Support

-Select Role dropdown menu = View only

Extended Accesss

-Select Department = Support = Save Changes
<a href="https://imgur.com/IFIc7ub"><img src="https://i.imgur.com/IFIc7ub.png" title="source: imgur.com" /></a>
<a href="https://imgur.com/xbM3Pqw"><img src="https://i.imgur.com/xbM3Pqw.png" title="source: imgur.com" /></a>
<h2>Configure Users</h2>

In the Agent panel

Select Users tab to create user

-Email Address: Karen@osticket.com

-Full Name - Karen Karen

-Select Add User
<a href="https://imgur.com/ZqGYyCl"><img src="https://i.imgur.com/ZqGYyCl.png" title="source: imgur.com" /></a>

Select user tab again to create another user

-Email Address: Ken@osticket.com

-Full Name - Ken Ken

-Select Add User
<a href="https://imgur.com/dt4921m"><img src="https://i.imgur.com/dt4921m.png" title="source: imgur.com" /></a>
<h2> Configure Service Level Agreements</h2>
Select Manage tab -> SLA -> Add New SLA Plan

-Name: SEV-A

-Grace Period: 1

-Schedule dropdown menu: 24/7

-Select Add Plan
<a href="https://imgur.com/4VsMbNi"><img src="https://i.imgur.com/4VsMbNi.png" title="source: imgur.com" /></a>
<a href="https://imgur.com/uLvPOqd"><img src="https://i.imgur.com/uLvPOqd.png" title="source: imgur.com" /></a>

Name: SEV-B

-Grace Period: 4

-Schedule dropdown menu: 24/7

-Select Add Plan
<a href="https://imgur.com/KduxY8s"><img src="https://i.imgur.com/KduxY8s.png" title="source: imgur.com" /></a>

Name: SEV-C

-Grace Period: 8

-Schedule dropdown menu: Monday - Friday 8AM - 5PM with U.S Holidays

-Select Add Plan
<a href="https://imgur.com/OuzYOdI"><img src="https://i.imgur.com/OuzYOdI.png" title="source: imgur.com" /></a>

<h2> Configure Help Topics</h2>

In the admin panel

Select Manage tab = Help Topics = Add New Help Topic

-Business Critical Outage

-Personal Computer Issues

-Equipment Request

-Password Reset

Select Add Topic for each topic
<a href="https://imgur.com/SPnuzkz"><img src="https://i.imgur.com/SPnuzkz.png" title="source: imgur.com" /></a>
<a href="https://imgur.com/NLlHpK6"><img src="https://i.imgur.com/NLlHpK6.png" title="source: imgur.com" /></a>

<br />
