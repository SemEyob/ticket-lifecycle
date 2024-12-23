

<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
In this home lab, I will demonstrate the Ticket and Ticket Life Cycle in osTicket by simulating a series of made-up scenarios as both an end-user and a help desk agent, working through tickets from intake to resolution.<br />

<h2>Key Skills and Career-Relevant Takeaways</h2>

<ul>
  <li><strong>Proficiency in IT Service Management:</strong> Acquired hands-on experience with a ticketing system, which are commonly used all throughout the IT world, mastering the end-to-end ticket lifecycle from intake to resolution.</li>
  <li><strong>Streamlining Support Processes:</strong> Configured ticket properties (e.g., priority, SLA, and department) to optimize workflows and ensure alignment with organizational goals.</li>
  <li><strong>Problem-Solving Expertise:</strong> Demonstrated the ability to systematically troubleshoot and resolve technical issues by working through real-world scenarios in a structured environment.</li>
  <li><strong>Workflow Design and Role Management:</strong> Enhanced skills in defining role-based workflows and permissions, critical for managing team operations and improving service delivery.</li>
  <li><strong>Technical Communication:</strong> Gained experience in bridging communication between end-users and IT support teams, ensuring issues are accurately documented and resolved efficiently.</li>
  <li><strong>Adaptability and Process Improvement:</strong> Learned to manage and configure dynamic IT environments, showcasing flexibility and a continuous improvement mindset in service management practices.</li>
</ul>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used</h2>

- Windows 10 (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

Admin/Analyst Login Page:  
[http://localhost/osTicket/scp/login.php](http://localhost/osTicket/scp/login.php)

End Users osTicket URL:  
[http://localhost/osTicket](http://localhost/osTicket)

### 1. Creating and Managing Tickets

In this lab, we will create tickets as end users, observe their properties, and respond as help desk agents.

#### Task 1: Change Department Settings
- Change the SysAdmins Department to a Top Level Department.
- DELETE the Maintenance Department (not archive).

#### Task 2: End-User Ticket Creation
As an end-user, create the following ticket:
- **Issue**: Entire mobile/online banking system is down  
![image](https://github.com/user-attachments/assets/47710e23-7bd7-4a9e-994e-bc04e24e093a)

#### Task 3: Help Desk Agent View
As a Help Desk Agent (John), observe the ticket’s properties:
- Priority
- Department
- SLA
- Assigned To  
![image](https://github.com/user-attachments/assets/6e803834-c5e5-4f7c-94fe-8848aea8119e)

#### Task 4: Set Ticket Properties
- Set the ticket properties:
  - **Priority**: Sev-A (1 hour, 24/7)
  - **Department**: Online Banking  
![image](https://github.com/user-attachments/assets/de7d3578-53d2-41b7-ac3e-6d3804b0a9c5)

#### Task 5: Ticket Observations
Attempt to observe the ticket again as "John". Can you view or change the ticket?

#### Task 6: Work the Ticket
Work the ticket to completion as Jane:  
![image](https://github.com/user-attachments/assets/5d0f379d-d90a-4420-958d-f9df5b66ac9c)

---

### 2. Creating and Managing Additional Tickets

#### Task 1: End-User Ticket Creation
As an end-user, create the following ticket:
- **Issue**: Accounting department needs Adobe upgrade, broken

#### Task 2: Help Desk Agent View
As a Help Desk Agent (John), observe the ticket’s properties:
- Priority
- Department
- SLA
- Assigned To

#### Task 3: Set Ticket Properties
- Set the ticket properties:
  - **Priority**: Sev-B (4 hours, 24/7)
  - **Department**: Support  
![image](https://github.com/user-attachments/assets/c526e756-a485-43ca-9119-ce7e28a9679e)

#### Task 4: Work the Ticket
Work the ticket to completion as John:  
![image](https://github.com/user-attachments/assets/a7d69049-4242-45c5-acf7-1c3254961521)

---

### 3. Additional Ticket Management

#### Task 1: End-User Ticket Creation
As an end-user, create the following ticket:
- **Issue**: CFO’s laptop will no longer turn on

#### Task 2: Help Desk Agent View
As a Help Desk Agent (John), observe the ticket’s properties:
- Priority
- Department
- SLA
- Assigned To

#### Task 3: Set Ticket Properties
- Set the ticket properties:
  - **Priority**: Sev-B (4 hours, 24/7)
  - **Department**: Support

#### Task 4: Work the Ticket
Work the ticket to completion as John:  
![image](https://github.com/user-attachments/assets/a7d69049-4242-45c5-acf7-1c3254961521)

---




<h2 align="center"> Tickets have now been created, worked, and resolved in osTicket 🏆 </h2>
