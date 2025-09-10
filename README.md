<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

# osTicket - Post-Installation Configuration
This project documents the post-installation configuration of osTicket.  
The focus is on setting up roles, departments, SLAs, and workflows that reflect real-world IT service desk operations.

---

## Video Demonstration
- [YouTube: osTicket Post-Installation Configuration](https://www.youtube.com)

---

## Environments and Technologies Used
- Microsoft Azure (Windows 10 VM)  
- osTicket (Open-Source Help Desk Ticketing System)  
- IIS, PHP, MySQL (from initial setup)  

---

## Operating Systems Used
- Windows 10 (21H2)  

---

## Configuration Steps

### 1) Admin and Agent Portals
- Admin/Analyst Login Page: `http://localhost/osTicket/scp/login.php`  
- End-User URL: `http://localhost/osTicket`  
- Acknowledged difference between the Agent Panel (staff workflows) and Admin Panel (system configuration).  

<p><img src="images/STEP1.png" width="80%" alt="Admin Login (placeholder)"/></p>  
<p><img src="images/STEP1.2.png" width="80%" alt="End-User Portal (placeholder)"/></p>  
<br />

### 2) Configure Roles & Departments
- Created custom role “Supreme Admin” with full permissions.  
- Configured a new department: “SysAdmins” for restricted ticket visibility.  

<p><img src="images/post-step2a.png" width="80%" alt="Supreme Admin Role (placeholder)"/></p>  
<p><img src="images/post-step2b.png" width="80%" alt="SysAdmins Department (placeholder)"/></p>  
<br />

### 3) Configure Teams
- Created “Online Banking” team by pulling agents across departments.  
- Demonstrates cross-department collaboration.  

<p><img src="images/post-step3.png" width="80%" alt="Online Banking Team (placeholder)"/></p>  
<br />

### 4) Configure Agents and Users
- Added Joe (Dept: SysAdmins, Role: Supreme Admin, Team: Online Banking).  
- Added Sam (Dept: Support, standard role).  
- Added Lisa as an example end-user.  

<p><img src="images/post-step4a.png" width="80%" alt="Joe Agent (placeholder)"/></p>  
<p><img src="images/post-step4b.png" width="80%" alt="Sam Agent (placeholder)"/></p>  
<p><img src="images/post-step4c.png" width="80%" alt="Lisa User (placeholder)"/></p>  
<br />

### 5) Configure SLA Plans
- Created SLA definitions to control response expectations:  
  - Sev-A (1 hour, 24/7)  
  - Sev-B (4 hours, 24/7)  
  - Sev-C (8 hours, business hours)  

<p><img src="images/post-step5.png" width="80%" alt="SLA Plans (placeholder)"/></p>  
<br />

### 6) Configure Help Topics
- Added structured help topics for end-users:  
  - Business Critical Outage  
  - Personal Computer Issues  
  - Equipment Request  
  - Password Reset  
  - Other  

<p><img src="images/post-STEP6.1.png" width="80%" alt="Help Topics (placeholder)"/></p>  
<p><img src="images/post-STEP6.png" width="80%" alt="Help Topics (placeholder)"/></p>
<br />

---

## ✅ Final Result
osTicket is now fully configured with real-world IT workflows:  
- Clear separation of Admin vs Agent panels  
- Controlled access via Roles, Departments, Teams  
- Realistic SLAs and Help Topics to drive ticket workflow  
- Staff and end-users properly onboarded  

---

## 🤳 Connect with me
<a href="https://www.linkedin.com/in/abdel-b-893256362/">
  <img align="left" alt="Abdel | LinkedIn" width="22px" src="https://img.icons8.com/ios-filled/50/FFFFFF/linkedin.png" />
</a>
<a href="https://www.linkedin.com/in/abdel-b-893256362/">LinkedIn</a>
