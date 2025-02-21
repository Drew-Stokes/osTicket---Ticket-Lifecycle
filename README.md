<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<!--<h2>Video Demonstration</h2>

- ### [YouTube: How to create, work, and resolves tickets within osTicket](https://www.youtube.com)
-->
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
  # 🛠️ Managing Tickets in osTicket

This guide will walk you through creating, assigning, and managing tickets as both an **end-user** and a **help desk agent** in osTicket.

---

## **Step 1: Access the osTicket Portals**
<details>
<summary><b>Click to Expand</b></summary>

### **Login Pages**
- **Admin/Analyst Login Page**:  
http://localhost/osTicket/scp/login.php

markdown
Copy
Edit
- **End-User Portal**:  
http://localhost/osTicket


</details>

---

## **Step 2: Modify Departments**
<details>
<summary><b>Click to Expand</b></summary>

1. Change **SysAdmins** to a **Top-Level Department**.
   <p>
<img src="https://github.com/Drew-Stokes/osTicket---Ticket-Lifecycle/blob/0c8b00ca1a565b881f306eeff1ec75fdf35a45ec/top_level_sysadmin.png" height="30%" width="30%" alt="Disk Sanitization Steps"/>
</p>
 
2. **Delete** (not archive) the **Maintenance Department**.
   <p>
<img src="https://github.com/Drew-Stokes/osTicket---Ticket-Lifecycle/blob/0c8b00ca1a565b881f306eeff1ec75fdf35a45ec/delete_maitanance.png" height="30%" width="30%" alt="Disk Sanitization Steps"/>
</p>

</details>

---

## **Step 3: Create and Manage Tickets**
### **Ticket #1: Online Banking System Down**
<details>
<summary><b>Click to Expand</b></summary>

#### **As an End-User**:
1. Navigate to the **End-User Portal**.
2. Create a ticket:
 - **Issue**: Entire mobile/online banking system is down.
<p>
<img src="https://github.com/Drew-Stokes/osTicket---Ticket-Lifecycle/blob/ed00ff30ed8126a3df29631b1fdd1ea11a9877c7/banking_system_down.png" height="30%" width="30%" alt="Disk Sanitization Steps"/>
</p>

#### **As a Help Desk Agent (John)**:
1. Observe the ticket’s properties:
 - 🏷️ **Priority**  
 - 🏢 **Department**  
 - ⏳ **SLA**  
 - 👤 **Assigned To**  

2. Set properties:
 - **SLA**: 🔥 **Sev-A (1 hour, 24/7)**  
 - **Department**: **Online Banking**  

3. Attempt to observe the ticket again as **John**. Can you still view or modify it?

4. **Work the ticket to completion as Jane**.
</details>

---

### **Ticket #2: Adobe Upgrade Needed (Broken)**
<details>
<summary><b>Click to Expand</b></summary>

#### **As an End-User**:
1. Create a ticket:
 - **Issue**: Accounting department needs Adobe upgrade, broken.

#### **As a Help Desk Agent (John)**:
1. Observe the ticket’s properties:
 - 🏷️ **Priority**  
 - 🏢 **Department**  
 - ⏳ **SLA**  
 - 👤 **Assigned To**  

2. Set properties:
 - **SLA**: ⏳ **Sev-B (4 hours, 24/7)**  
 - **Department**: **Support**  

3. **Work the ticket to completion as John**.
</details>

---

### **Ticket #3: CFO’s Laptop Won’t Turn On**
<details>
<summary><b>Click to Expand</b></summary>

#### **As an End-User**:
1. Create a ticket:
 - **Issue**: CFO’s laptop will no longer turn on.

#### **As a Help Desk Agent (John)**:
1. Observe the ticket’s properties:
 - 🏷️ **Priority**  
 - 🏢 **Department**  
 - ⏳ **SLA**  
 - 👤 **Assigned To**  

2. Set properties:
 - **SLA**: ⏳ **Sev-B (4 hours, 24/7)**  
 - **Department**: **Support**  

3. **Work the ticket to completion as John**.
</details>

---

## **Step 4: Escalation and Access Control**
<details>
<summary><b>Click to Expand</b></summary>

1. **Set all tickets' properties**:  
 - **Sev-A tickets last (SysAdmins)**.  
 - Observe that the **ticket becomes inaccessible** to John.  

2. **Switch to the Admin Panel**:
 - Assign yourself **View-Access** to **SysAdmins**.

3. **Switch back to the Agent Panel**:
 - Observe the **escalated ticket**.  
 - Notice that you can **no longer make changes** to it.  
</details>

---

## **Step 5: Completing and Reviewing Tickets**
<details>
<summary><b>Click to Expand</b></summary>

✅ **Solve all remaining tickets** in the system.  
✅ **Explain how most ticketing systems (including osTicket) send email notifications** when a ticket is updated, allowing users to respond via email.  
✅ **Understand ticket intake in real life (IRL)**:
 - Tickets may come from **phone, chat apps, email, web forms, or in-person** interactions.  
 - Many users **approach IT directly**, but **always log tickets for tracking and metrics**.  
</details>

---

## **Step 6: Additional Practice and Technical Skills**
<details>
<summary><b>Click to Expand</b></summary>

- There is **much more to explore** in osTicket—take time to review its **email features** and automation tools.  
- **Redo this lab multiple times** until you can complete it from memory using a simple checklist.  
- Building **technical intuition** comes from **repetition and hands-on experience**.  
- Revisit the **Technical Skill Pillar** and refine your troubleshooting process.  
</details>

---

## 🎉 **Lab Complete!**
You've successfully created, escalated, and resolved tickets in osTicket! 🚀 Keep practi
</p>
