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
<img src="https://i.imgur.com/sjn2xr2.png" height="80%" width="80%" alt="Resolving the Second Ticket"/>
</p>
<p>
Now that the first ticket has been resolved lets head over to our next ticket. Click any of the tickets that you have left available and
start working the tickey by reviewing the priority, SLA Plan and department. In our example we changed the priority from normal to high due
to the issue being department wide and we changed the SLA from default to SEV-B. We kept the department the same because the issue seems like
something the support team can handle. For this particular ticket try assigning it to a different agent. In our example we ended up assigning 
it from Jane to John and then sent the user a message that their ticket was being assigned to John. After you reassign the ticket and message 
the user you will then need to login under the agent that you reassigned the ticket to, to ultimately resolve and close the ticket.
</p>

___

<p>
<img src="https://i.imgur.com/3ishGDe.png" height="80%" width="80%" alt="Resolving the Second Ticket Part 2"/>
</p>
<p>
Because we reassigned the ticket to John, we are now logged in under John's account so that we can finish up our second ticket.
When you open up the ticket again you can notice all of the updates Jane Doe made prior to the ticket being transferred. Because 
the priority level and SLA was already updated by Jane, the only thing left for John to do is to resolve the issue. In our example 
to resolve the issue, John decided to rollback the version of adobe reader to allow the accounting to use the software again. You
can of course come up with your own unique resolution for the assigned agent. Once you enter your reply to the user, change the
status to resolved and post reply and you will be officially done working your second ticket.
</p>

___

<p>
<img src="https://i.imgur.com/x7ejbXJ.png" height="80%" width="80%" alt="Resolving the Third Ticket"/>
</p>
<p>
So now that our second ticket has been resolved we can head to our third and final ticket. Once in the ticket repeat the same general
process that was used in the prior two tickets by reviewing the priority level, department and SLA Plan. In our example the user is just
asking a question about a hardware refresh and so we changed the priority from Normal to Low and the SLA Plan from default to SEV-C. 
We assigned the ticket to John because we are already logined into his agent account. For a simple ticket like this, we were able to
resolve it very quickly by simply answering the customer's question and hitting "post reply" with a resolved ticket status.
</p>

___

<p>
<img src="https://i.imgur.com/SKl9cPC.png" height="80%" width="80%" alt="Tutorial Completed"/>
</p>
<p>
Congratulations, we have now finished working all of our tickets! We went through each step of the ticket lifecycle process from intake 
(ticket creation by the user), assignment and communication ( when we are logged in as the agent and are assigning the ticket to ourselves 
or others and sending the initial response to the user), working the issue( when we do behind the scenes research to solve the issue that 
they are facing) and resolution (when we send them a message telling them how we briefly resolved their problem and let them know everything
is fixed). After going through all three tutorials I hope that you have a better understanding of how osTicket works and how you can potentially
use it in your organization.
</p>
