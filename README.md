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

<h2>Initial Setup</h2>

<p>
✅ Changed SysAdmins to a top-level department.

✅ Deleted the Maintenance department (not archived, fully deleted).
</p>
<br />
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt=""/>
</p>
<br />

<h2>Scenario 1: Entire Mobile/Online Banking System is Down</h2>

<p>
End User Ticket Created:
"Entire mobile/online banking system is down."

Help Desk Agent (john) Observations:
  - Priority: Set to Sev-A (1 hour, 24/7)
  - Department: Online Banking
  - SLA and Assignment configured accordingly.

Attempted to re-observe the ticket as "john"—access was limited after escalation.

Help Desk Agent (jane):
Took over and worked the ticket to completion.
</p>
<br />
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt=""/>
</p>
<br />
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt=""/>
</p>
<br />

<h2>Scenario 2: Adobe Upgrade Needed in Accounting</h2>

<p>
End User Ticket Created:
"Accounting department needs Adobe upgrade, broken."

Help Desk Agent (john) Observations:
  - Priority: Set to Sev-B (4 hours, 24/7)
  - Department: Support
  - SLA and Assignment set

Ticket worked to completion by john.
</p>
<br />
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt=""/>
</p>
<br />

<h2>Scenario 3: CFO’s Laptop Won’t Power On</h2>

<p>
End User Ticket Created:
“CFO’s laptop will no longer turn on.”
  
Help Desk Agent (john) Observations:
  - Priority: Sev-B
  - Department: Support

john completed this ticket as well.
</p>
<br />
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt=""/>
</p>
<br />


<h2>📧 The Power of Email Integration</h2>

<p>
In most ticketing systems, including osTicket: every update on a ticket triggers an email notification to the requester. This two-way communication helps keep users informed and gives them a chance to respond directly to the ticket thread.
</p>
<br />
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt=""/>
</p>
<br />

<h2>🧠 Real-World Ticket Intake Explained</h2>
Ticket creation can happen in a variety of ways:

  - Web forms

  - Email

  - Phone calls

  - Chat apps

  - Even hallway conversations or impromptu desk visits

While fixing things on the fly is tempting, creating tickets for every interaction is best practice. It ensures:

  - Accountability

  - Accurate metrics

  - Transparent workflow


<p>

</p>
<br />

<h2>🏁 Conclusion</h2>

<p>
This hands-on lab helped reinforce the importance of proper ticket handling, prioritization, and role-based access. Whether you're an aspiring analyst or an experienced admin, taking time to practice and document your steps ensures growth in your tech career.
</p>
<br />
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt=""/>
</p>
<br />








