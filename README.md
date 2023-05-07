<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to create, work, and resolves tickets within osTicket](https://www.youtube.com)

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

<p>
<img src="https://i.imgur.com/XWJnGP7.png" height="80%" width="80%" alt="Ticket Lifecycle"/>
</p>
<p>
Now that we have finished configuring osTicket from the last tutorial we will now be demonstrating the ticket lifecycle from
creation to resolution by creating new tickets through osTicket and resolving them using the agents we configured in the last 
tutorial. Right now we currently do not have any tickets open and so our first step will be to create our first three new tickets.
</p>

___

<p>
<img src="https://i.imgur.com/l6b51AG.png" height="80%" width="80%" alt="Ticket Creation"/>
</p>
<p>
In order to create your first ticket head over to http://localhost/osTicket/. Once on the page click " Open a New Ticket".
Then on the ticket creation page you will want to enter in the email address of one of the users you created in the previous 
configuration tutorial along with their name. Next choose a help topic and fill out the ticket details sections. Once you are done
hit "create ticket" and you will have created your first ticket in osTicket. Repeat these steps to create your second and third ticket
and then we will move on to the next step.
</p>

___

<p>
<img src="https://i.imgur.com/20uOML1.png" height="80%" width="80%" alt="Login as an agent"/>
</p>
<p>
Now login as one of the agents that you created in the previous tutorial using their username and password. Once logged in you should 
see your open tickets as it appears above. If you are not seeing any open tickets then you will need to logout and login as an admin 
and check your agent's permissions to make sure they were added to the Support Department. Once the agent has been added to the support 
department with full access( no restrictions) then logout of your admin account and login in under your agent profile to proceed.
</p>

___


<p>
<img src="https://i.imgur.com/MUVbaVr.png" height="80%" width="80%" alt="Ticket Assignment and Communication"/>
</p>
<p>
Let's start by addressing our first ticket. Open one of the tickets and it should look similiar to the picture shown above.
Next we will start "working" the ticket. Based on the information sent to us by the user we will first evaluate if we need to
make a change to the priority level. You can change the priority level by clicking on "Normal" next it and a window should pop up
with different priority options. 
  
In my example, given that the online banking system is down, I changed the priority from Normal to emergency given the situation. 
After updating the priority the next step would be to assign the ticket to an agent. You can do this by clicking the space next to 
"assigned to" and selecting one the agents from the list. In this example we decided to use the same  agent (Jane), that we are 
already logged in as. Next we will determine the SLA Plan, and for this example we would choosed SEV-A given the priority of this 
ticket. You can assign the SLA by clicking "Default SLA" and then choosing from the options that you created in the prior tutorial. 

After assigning the SLA we would then move on to determining which department would be best suited to handle this issue. In our 
ticket we decided that the Support department may not be best equipped and so we changed the department to System Adminstrators 
which Jane is already a member of. To change departments click on the current department and select a different option. Also be 
sure that you have agents assigned to the new department that you decide to switch the ticket to or you will have to go back to 
your admin account and add them to the new department so that they can access the ticket.

Now that we have adjusted the priority, department and SLA, we can post a reply to the user letting them know that we are working
on their ticket or if the incident was simple we can send them a message saying that the issue has been resolved and briefly
explaining what was done. In my ticket I sent a short message saying that I was coordinating with the Sys Admin Team to address
the issue. If the issue is still open then leave the ticket status as open or if you resolved your ticket then change it to resolved
to close out the ticket and then hit "post reply".
</p>

___


<p>
<img src="https://i.imgur.com/PPFz6zo.png" height="50%" width="50%" alt="Ticket Page"/>
</p>
<p>
<img src="https://i.imgur.com/5EbUfDp.png" height="50%" width="50%" alt="Resolving First Ticket"/>
</p>
<p>
If your first ticket is still open you can head back to the main ticket page as shown above and see the priority level and agent information
that has been updated next to the ticket. We do want to resolve this emergency ticket swiftly so in our example we go back into the ticket
and inform the user that the issue has been resolved by another member of our team and select resolve to close out the ticket. Once I hit
"post reply" this ticket will no longer show up on the open tickets page but still can be found via the Closed tab under Tickets.
</p>

___

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>

___

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>

___

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>

___
