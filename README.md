

<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post Install Configuration</h1>
# osTicket - Post-Installation Configuration  

This repository demonstrates the **post-installation configuration** of the open-source help desk ticketing system **osTicket**.  

---

## 🎥 Video Demonstration  
📺 [How To Configure osTicket After Installation](#)  
*(Add your YouTube or video link here)*  

---

## 🖥️ Environments and Technologies Used  
- **Microsoft Azure** (Virtual Machines / Compute)  
- **Remote Desktop** (RDP)  
- **Internet Information Services (IIS)**  
- **MySQL / HeidiSQL**  
- **osTicket (Admin Panel)**  

---

## 💻 Operating Systems Used  
- **Windows 10 (21H2)**  

---

## 📋 Post-Installation Configuration Checklist  

1. Configure **Roles** (permissions for agents).  
2. Configure **Departments** (ticket routing).  
3. Configure **Teams** (groups of agents across departments).  
4. Allow **Anyone to Create Tickets**.  
5. Configure **Agents (Help Desk Staff)**.  
6. Configure **Users (End Users/Clients)**.  
7. Configure **Service Level Agreements (SLAs)**.  
8. Configure **Help Topics** (categorize tickets).  

---

## ⚙️ Configuration Steps  

### 1. Configure Roles  
- Navigate to **Admin Panel → Agents → Roles**.  
- Create roles to define what agents can/can’t do.  

📸 **Screenshot:**  
![Roles Configuration](images/step1_roles.png)  

---

### 2. Configure Departments  
- Go to **Admin Panel → Agents → Departments**.  
- Example: IT Support, Customer Service, HR Help Desk.  

📸 **Screenshot:**  
![Departments Configuration](images/step2_departments.png)  

---

### 3. Configure Teams  
- Go to **Admin Panel → Agents → Teams**.  
- Teams can include members from multiple departments.  

📸 **Screenshot:**  
![Teams Configuration](images/step3_teams.png)  

---

### 4. Allow Anyone to Create Tickets  
- Go to **Admin Panel → Settings → User Settings**.  
- Check “**Require registration/login to create tickets**” → **Disable** (if you want open ticketing).  

📸 **Screenshot:**  
![User Settings](images/step4_user_settings.png)  

---

### 5. Configure Agents (Help Desk Staff)  
- Go to **Admin Panel → Agents → Add New**.  
- Assign to a Department, Role, and Team.  

📸 **Screenshot:**  
![Agents Setup](images/step5_agents.png)  

---

### 6. Configure Users (End Users/Clients)  
- Switch to the **Agent Panel → Users → Add New**.  
- These are the people who will submit tickets.  

📸 **Screenshot:**  
![Users Setup](images/step6_users.png)  

---

### 7. Configure Service Level Agreements (SLAs)  
- Go to **Admin Panel → Manage → SLA**.  
- Example:  
  - SEV-A (24/7, 1-hour response, 4-hour resolution).  
  - SEV-B (24/7, 4-hour response, 8-hour resolution).  
  - SEV-C (Business hours, 8-hour response, 24-hour resolution).  

📸 **Screenshot:**  
![SLA Setup](images/step7_sla.png)  

---

### 8. Configure Help Topics  
- Go to **Admin Panel → Manage → Help Topics**.  
- Examples:  
  - Business Critical Outage  
  - Personal Computer Issues  
  - Equipment Request  
  - Password Reset  

📸 **Screenshot:**  
![Help Topics](images/step8_help_topics.png)  

---

## 📂 Repository Structure  

