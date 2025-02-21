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
<p>
<img src="https://github.com/Drew-Stokes/osTicket---Ticket-Lifecycle/blob/b1d2f231c607c0bf3eef68c6e30d454cdfef6e65/observe_ticket.png" height="30%" width="30%" alt="Disk Sanitization Steps"/>
</p>
4. **Work the ticket to completion as Jane**.
<p>
<img src="https://github.com/Drew-Stokes/osTicket---Ticket-Lifecycle/blob/181f4337f9f3a9962c68d777085415eb679e690d/jane_take_over.png" height="30%" width="30%" alt="Disk Sanitization Steps"/>
</p>
</details>

---

### **Ticket #2: Adobe Upgrade Needed**
<details>
<summary><b>Click to Expand</b></summary>

#### **As an End-User**:
1. Create a ticket:
 - **Issue**: Accounting department needs Adobe upgrade, broken.
<p>
<img src="https://github.com/Drew-Stokes/osTicket---Ticket-Lifecycle/blob/181f4337f9f3a9962c68d777085415eb679e690d/adobe_ticket.png" height="30%" width="30%" alt="Disk Sanitization Steps"/>
</p>
#### **As a Help Desk Agent (John)**:
1. Observe the ticket’s properties:
 - 🏷️ **Priority**  
 - 🏢 **Department**  
 - ⏳ **SLA**  
 - 👤 **Assigned To**  

2. Set properties:
 - **SLA**: ⏳ **Sev-C (8 hours, Business hours)**  
 - **Department**: **Support**  
<p>
<img src="https://github.com/Drew-Stokes/osTicket---Ticket-Lifecycle/blob/181f4337f9f3a9962c68d777085415eb679e690d/adobe_ticket.png" height="30%" width="30%" alt="Disk Sanitization Steps"/>
</p>
3. **Work the ticket to completion as John**.
<p>
<img src="https://github.com/Drew-Stokes/osTicket---Ticket-Lifecycle/blob/450d76c365a12b4411874269916e4c2817dc25fc/john_close_out_adobe_ticket.png" height="30%" width="30%" alt="Disk Sanitization Steps"/>
</p>
</details>

---

### **Ticket #3: CFO’s Laptop Won’t Turn On**
<details>
<summary><b>Click to Expand</b></summary>

#### **As an End-User**:
1. Create a ticket:
 - **Issue**: CFO’s laptop will no longer turn on.
<p>
<img src="https://github.com/Drew-Stokes/osTicket---Ticket-Lifecycle/blob/3a36447c6863f63041b1a936139e8b10db1c9070/cfo_ticket.png" height="30%" width="30%" alt="Disk Sanitization Steps"/>
</p>

#### **As a Help Desk Agent (John)**:
1. Observe the ticket’s properties:
 - 🏷️ **Priority**  
 - 🏢 **Department**  
 - ⏳ **SLA**  
 - 👤 **Assigned To**
 -  **SLA**: ⏳ **Sev-B (4 hours, 24/7)**
 -  **Department**: **Support**
<p>
<img src="https://github.com/Drew-Stokes/osTicket---Ticket-Lifecycle/blob/3a36447c6863f63041b1a936139e8b10db1c9070/setting_properties_on_cfo_ticket.png" height="30%" width="30%" alt="Disk Sanitization Steps"/>
</p>
3. **Work the ticket to completion as John**.
<p>
<img src="https://github.com/Drew-Stokes/osTicket---Ticket-Lifecycle/blob/47df22051920e8300954e4487d31c1011feed667/CFO_ticket_resolved.png" height="30%" width="30%" alt="Disk Sanitization Steps"/>
</p>
</details>

---

## 🎉 **Lab Complete!**
You've successfully created, escalated, and resolved tickets in osTicket! 🚀 Keep practi
</p>
