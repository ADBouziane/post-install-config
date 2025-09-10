<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Installation Configuration</h1>
This project documents the <b>post-installation configuration</b> of osTicket.  
The focus is on setting up roles, departments, SLAs, and workflows that reflect real-world IT service desk operations.<br />

<h2>Video Demonstration</h2>

- ### <a href="https://www.youtube.com">YouTube: osTicket Post-Installation Configuration</a>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Windows 10 VM)
- osTicket (Open-Source Help Desk Ticketing System)
- IIS, PHP, MySQL (from initial setup)

<h2>Operating Systems Used</h2>

- Windows 10 (21H2)

---

<h2>Configuration Steps</h2>

<h3>1) Admin and Agent Portals</h3>
- **Admin/Analyst Login Page:** `http://localhost/osTicket/scp/login.php`  
- **End-User URL:** `http://localhost/osTicket`  
- Acknowledged difference between the **Agent Panel** (staff workflows) and **Admin Panel** (system configuration).  
<p><img src="images/post-step1a.png" width="80%" alt="Admin Login"/></p>  
<p><img src="images/post-step1b.png" width="80%" alt="End-User Portal"/></p>  
<br />

<h3>2) Configure Roles & Departments</h3>
- Created custom role **Supreme Admin** with full permissions.  
- Configured a new department: **SysAdmins** for restricted ticket visibility.  
<p><img src="images/post-step2a.png" width="80%" alt="Supreme Admin Role"/></p>  
<p><img src="images/post-step2b.png" width="80%" alt="SysAdmins Department"/></p>  
<br />

<h3>3) Configure Teams</h3>
- Created **Online Banking** team by pulling agents across departments.  
- Demonstrates cross-department collaboration.  
<p><img src="images/post-step3.png" width="80%" alt="Online Banking Team"/></p>  
<br />

<h3>4) Configure Agents and Users</h3>
- Added **Jane** (Dept: SysAdmins, Role: Supreme Admin, Team: Online Banking).  
- Added **John** (Dept: Support, standard role).  
- Added **Karen** as an example end-user.  
<p><img src="images/post-step4a.png" width="80%" alt="Jane Agent"/></p>  
<p><img src="images/post-step4b.png" width="80%" alt="John Agent"/></p>  
<p><img src="images/post-step4c.png" width="80%" alt="Karen User"/></p>  
<br />

<h3>5) Configure SLA Plans</h3>
- Created SLA definitions to control response expectations:  
  - **Sev-A** (1 hour, 24/7)  
  - **Sev-B** (4 hours, 24/7)  
  - **Sev-C** (8 hours, business hours)  
- Demonstrates knowledge of IT service delivery standards.  
<p><img src="images/post-step5.png" width="80%" alt="SLA Plans"/></p>  
<br />

<h3>6) Configure Help Topics</h3>
- Added structured help topics for end-users:  
  - Business Critical Outage  
  - Personal Computer Issues  
  - Equipment Request  
  - Password Reset  
  - Other  
- Improves ticket routing and workflow.  
<p><img src="images/post-step6.png" width="80%" alt="Help Topics"/></p>  
<br />

<h2>✅ Final Result</h2>
osTicket is now fully configured with real-world IT workflows:  
- Clear separation of **Admin vs Agent panels**  
- Controlled access via **Roles, Departments, Teams**  
- Realistic **SLAs** and **Help Topics** to drive ticket workflow  
- Staff and end-users properly onboarded  

---

<h2>🤳 Connect with me</h2>
<a href="https://www.linkedin.com/in/abdel-b-893256362/">
  <img align="left" alt="Abdel | LinkedIn" width="22px" src="https://img.icons8.com/ios-filled/50/FFFFFF/linkedin.png" />
</a>
<a href="https://www.linkedin.com/in/abdel-b-893256362/">LinkedIn</a>
