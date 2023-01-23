<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle Examples</h1>
In this final osTicket tutorial, we will be going over the lifecycle of a ticket.
<br />


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

<h3>Intake</h3>

First, you must open the default [osTicket](http://localhost/osTicket/) link.

<img src="https://i.imgur.com/PQkmfif.png" height="70%" width="70%" alt="Creating a Ticket"/>
<p>
Now we will be creating a ticket
	
- Click "Open a New Ticket" and create a ticket with the following fields:
	- Email: karen@osticket.com
	- Full Name: Karen Karen
	- Equipment Request
	- Help Topic: Business Critical Outage
      - Issue Summary: Mobile Banking System Is Down
      - Details: Customers are reporting that they are getting a 404 error when browsing to online banking.
- After entering those details, click on the "Create Ticket" button
</p>

<h3>Assignment and Communication</h3>

<img src="https://i.imgur.com/jzhgEhu.png" height="70%" width="70%" alt="Assigning a Ticket"/>
<p>

Now, sign into the agent [osTicket](http://localhost/osTicket/scp/login.php) link as jane.doe
	
- From the Tickets tab, we will see the "Mobile Banking System is Down" ticket. Click on it and modify the following fieds: 
	- Priority: Emergency
  - Department: System Administrators
	- Assigned To: Jane Doe
	- SLA Plan: SEV-A
	- Example Response: "Coordinating with Sys Admin Team to bring mobile banking online."
- After entering those details, click on the "Post Reply" button
</p>

<h3>Working the Issue</h3>

Once the issue has been assigned, the various departments and/or agents will work on resolving the issue. In this case, Jane and the System Administrator team will work together to resolve the issue.

<h3>Resolution</h3>

<img src="https://i.imgur.com/Ae7HtWC.png" height="70%" width="70%" alt="Resolving the Ticket"/>
<p>

Once the issue is resolved, we will need to resolve the ticket and update the end user.
	
- From the Tickets tab, select the "Mobile Banking System is Down" ticket. From there update the following fields: 
	- Example Response: "Jerry from System Engineering found and corrected a failed load balancer. Mobile banking should be back up."
  - Ticket Status: Resolved
- After entering those details, click on the "Post Reply" button
- This ticket will no longer be viewable with other open tickets as it has been resolved
</p>
