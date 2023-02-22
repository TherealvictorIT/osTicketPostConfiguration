<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post Configuration Setup</h1>
</p>
This tutorial covers the post-configuration setup of the osTicket system and highlights some of the basic configurations that are available within osTicket. By following this tutorial, you will gain a better understanding of how osTicket works and how it can be customized to suit your specific needs.
<p>
<br />
First we will configure new roles within the help desk. In order to do so go to Admin panel-> Agents-> Roles. We will create a Supreme Admin.
</p>
<img src="https://i.imgur.com/NZou2dW.png" height="70%" width="60%" alt="Disk Sanitization Steps"/>
</p>
To create a new role, click "Add New Role" and enter a name such as "Supreme Admin." Modify the role's permissions as needed, but remember that roles determine an agent's access level, so not all agents will have unlimited access. Defining specific roles with varying access levels ensures security and helps agents carry out their responsibilities effectively.
</p>

<h4>Creating a New Department</h4>

<img src="https://i.imgur.com/5ZuOrug.png" height="60%" width="70%" alt="Disk Sanitization Steps"/>
</p>
<br />
In order to create a new department select the "Departments" button in the agents tab. Each Agent is assigned to a specific department depending on their assigned role within the helpdesk. In this case we will be creating the "System Administrators" department, this is where the Supreme Admins will be designated. Other specific settings such as SLAs, managers and other email settings can be set up in the departments tab. 
</p>

<h4>Creating a New Team</h4>

<p>
<img src="https://i.imgur.com/IvkD00H.png" height="60%" width="70%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now we will set up a new team. Teams allow you to pull agents from different departments you can have an A team that has top technicians from specific departments. For example you can create a help topic that correlates with a product you produce, and assign it to a team of agents that specialize in that particular product. To set up a team go to Agents->Teams. A Level I support team has been created by default, in this example we will create a Level II Support Team. 
</p>
<br />
<p>
<h4>Allow Anyone to Create Tickets</h4>
<p>
<img src="https://i.imgur.com/YFqv5Nt.png" height="60%" width="70%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now that we have created a new team, we can adjust the user settings to allow anyone to create tickets without requiring registration. To do this, you can navigate to the "Settings" section of the Admin Panel and select "User Settings." Next, you can uncheck the "Registration Required" option. This will allow anyone to submit tickets without needing to create an account or log in.
</p>
<h4>Configure Agents (Workers)</h4>
<p>
<br />
<img src="https://i.imgur.com/hZRqKjp.png" height="60%" width="70%" alt="Disk Sanitization Steps"/>
</p>
<p>
Agents are the employees of the helpdesk who work on resolving customer tickets. Each agent is assigned to a primary department and given a specific role for tickets within that department. Agents can also be granted access to other departments, and their roles may vary depending on which department they are working in.
<p>
To manage an agent's permissions, access, and team assignments, you can navigate to the "Agents" tab. For example, you could create an agent named Jane Doe and assign her to the System Administrators department with a Supreme Admin role. Additionally, you could assign her to work on Level II Support tickets within that department. This would ensure that Jane has the necessary access and role permissions to handle complex technical issues and manage the support team effectively.
<p>
<h4>Configure Users (Customers)</h4>
</p>
<br />
<img src="https://i.imgur.com/kNPm22s.png" height="60%" width="70%" alt="Disk Sanitization Steps"/>
</p>
<p>
In order for customers to report issues and create tickets, they first need to be registered as users. Users are identified by their email address, which serves as their unique identifier. To create a new user, you can navigate to the Agent Panel, select "Users," then "User Directory," and click on "Add New." For instance, you could create users named Karen and Ken. Once created, these users will be able to submit tickets for any issues they encounter.
<p>
<h4>Configure Service Legal Agreement (SLA)</h4>
</p>
<br />
<img src="https://i.imgur.com/FOlvkuJ.png" height="60%" width="70%" alt="Disk Sanitization Steps"/>
</p>
<p>
Service Level Agreement (SLA) plans specify the amount of time in which the help desk is expected to resolve a specific ticket. You can create SLA plans by going to the Admin Panel, selecting "Manage," and then "SLA Plans." Each SLA plan has a schedule, which includes a grace period. 
<br />In this example SEV-A has a 24/7 and a one hour grace period. 
<br />--SEV-B has a 24/7 and a four hour grace period
<br />--SEV-C has a Regular Schedule and a eight hour grace period
<p>
<h4>Configure Help Topics</h4>
</p>
<br />
<img src="https://i.imgur.com/SbTCW3b.png" height="60%" width="70%" alt="Disk Sanitization Steps"/>
</p>
<p>
Help topics can help users categorize their tickets and make it easier for agents to prioritize and resolve them. For example, you might create a help topic for "Business Critical Outage," which could be used when customers are unable to access mobile banking. By categorizing tickets in this way, you can ensure that critical issues are identified and resolved quickly, while non-urgent requests are handled in due course. This can improve the overall efficiency and effectiveness of your help desk, leading to greater customer satisfaction and improved outcomes. 
</p>
<p>
