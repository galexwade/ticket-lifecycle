<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<!--- Step 1 -->
<p>
In this section we're going to create some tickets as if we were the end user (Ken or Karen) and then we're going to recieve the tickets as the Help Desk Professional and then set ticket properties to these tickets.
</p>

<p>
Open a new tab in Microsoft Edge, and use this link: http://localhost/osTicket/. Now use the information for the first user you create (I'm using Karen's) and then select Business Critical Outage as the help topic. Then give a generic issue title/summary and then create the ticket. We're going to do the same thing for the other user (I'm using Ken) and then select Personal Computer Issues, and then give a generic issue title/summary.
</p>

<p>
<img src="https://i.imgur.com/3wZhjSt.png" height="80%" width="80%" alt=""/>
</p>
<br />

<!--- Step 2 -->
<p>
Next, we're going to login to osTicket as the Help Desk Professional. Use this link to access the portal and log in as Jane Doe: http://localhost/osTicket/scp/login.php
</p>

<p>
Now we're going to observe these tickets. Click on the mobile banking ticket by karen. Here we can see the different ticket properties that are available to change. We're going to specifically focus on "Priority" and "Assigned To" properties of this ticket. In a real scenario, based on the SLAs of your business, you may assign this ticket as Emergency considering the entire banking application is down. Since this could be business impacting and critical, we might want to set the SLA to SEV-A.
</p>

<p>
<img src="https://i.imgur.com/gmaxDMW.png" height="80%" width="80%" alt=""/>
</p>
<br />

<!--- Step 3 -->
<p>
Agents are able to see live tickets in the agent panel. Managers will assign tickets to agents and assign priority levels of tickets depending on the SLAs of the business.
</p>
<p>
<img src="https://i.imgur.com/GmGBGJs.png" height="80%" width="80%" alt=""/>
</p>
<br />

