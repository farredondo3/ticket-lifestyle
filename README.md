<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" height="75%" width="100%"alt="osTicket logo"/>
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

<h3 align="center">Intake</h3>
<br />
<p>
  User Ken creates a ticket:
</p>
<p>
  <img src="createTicket.png: height="75%" width="100%" alt="Open a Ticket"/>
</p>
<br />
<br />
<h3 align="center">Ticket assignment</h3>
<br />
<p>
  Support agent Jon Doe logs in.
</p>
<p>
  <img src="loginAsSupportJane.png" height="75%" width="100%" alt="Support agent login"/>
</p>
<br />
<br />
<h3 align="center">Communication</h3>
<br />
<p>
  Agent Jane sees this is Sev-A emergency ticket and has to reassign ticket to a System Administrator.
</p>
<p>
  She makes sure to leave a proper message:
</p>
<p>
  <img src="transferTicketToSysAdmin.png" height="75%" width="100%" alt="Communication"/>
</p>
<br />
<br />
<h3 align="center">Working the issue</h3>
<br />
<p>
  System Administrator agent Jon Doe logs in:
</p>
<p>
  <img src="loginAsAgent.png" height="75%" width="100%" alt="Sys admin agent login"/>
</p>
<p>
  Agent Jon works the issue and communicates back to agent Jane.
</p>
<p>
  He also makes sure to switch the status of the issue from open to resolved:
</p>
<p>
  <img src="ticketResolvedByJon.png" height="75%" width="100%" alt="Working the issue"/>
</p>
<br />
<br />
<h3 align="center">Resolution</h3>
<br />
<p>
  Support agent Jane sees in her portal that System Administrator agent Jon has left her a message and that the ticket is now closed:>
</p>
<p>
  <img src="commThreadJonJane.png" height="75%" width="100%" alt="Working the issue"/>
</p>
<br />
<br />
<p>
  This was a very simplistic scenario of the creation of a ticket by a user, how the ticket is assigned and displays the communication of a ticket between agents; subsequently resulting in a resolution.
</p>
<p>
  There are additional scenarios that can also happen while a ticket is being assessed. A ticket can either be reassigned to a different department, escalated in severeity level, or needs to be both reassigned to a more qualified agent/department to handle the issue, depending on business impacts.
</p>
<p>
  I hope this tutorial helps you understand and have a better general overview of a life-cycle of a ticket. Help desk agents can expect to regularly deal with anywere between 10 to 100 tickets during their day depeneding on the company size.
</p>
