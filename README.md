

<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post Install Configuration</h1>
# osTicket - Post-Installation Configuration  

This repository demonstrates the **post-installation configuration** of the open-source help desk ticketing system **osTicket**.  

---


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
- Configure Roles (for grouping permissions)
Admin Panel -> Agents -> Roles
Supreme Admin


<img width="1916" height="1073" alt="Screenshot 2025-09-13 112752" src="https://github.com/user-attachments/assets/fecc9a5e-8199-4860-b3f4-ff3aa44de11c" />
<img width="1943" height="1076" alt="Screenshot 2025-09-13 113153" src="https://github.com/user-attachments/assets/1e5cf7af-26bf-462f-8463-e71d4af57ff7" />



---

### 2. Configure Departments  
- Go to **Admin Panel → Agents → Departments**.  
- Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
SysAdmins


📸 **Screenshot:**  
<img width="1923" height="1080" alt="Screenshot 2025-09-13 113544" src="https://github.com/user-attachments/assets/29dafcc6-7301-48f5-956f-655d016c609d" />


---

### 3. Configure Teams  
- Go to **Admin Panel → Agents → Teams**.  
- Teams can include members from multiple departments.  
- Online Banking

 
<img width="1916" height="1080" alt="Screenshot 2025-09-13 113845" src="https://github.com/user-attachments/assets/4d133214-997b-43af-9c35-fdab7490620f" />
 

---

### 4. Allow Anyone to Create Tickets  
- Go to **Admin Panel → Settings → User Settings**.  
- Check “**Require registration/login to create tickets**” → **Disable** (if you want open ticketing).  


<img width="1916" height="1080" alt="Screenshot 2025-09-13 114523" src="https://github.com/user-attachments/assets/00289bdb-cf15-47f3-b681-48cefb720cab" />
 

---

### 5. Configure Agents (Help Desk Staff)  
- Go to **Admin Panel → Agents → Add New**.  
- Assign to a Department, Role, and Team.
Jane (Dept: SysAdmins)
John (Dept: Support)
  

  
<img width="1920" height="1080" alt="Screenshot 2025-09-13 115004" src="https://github.com/user-attachments/assets/89e3ec62-4441-4e5f-a72a-374ce8eba334" />
 

---

### 6. Configure Users (End Users/Clients)  
- Switch to the **Agent Panel → Users → Add New**.  
- These are the people who will submit tickets.
Karen



 
<img width="1920" height="1080" alt="Screenshot 2025-09-13 115337" src="https://github.com/user-attachments/assets/41c4065d-d387-4844-aff1-5154366d7c07" />


---

### 7. Configure Service Level Agreements (SLAs)  
- Go to **Admin Panel → Manage → SLA**.  
- Example:  
  - SEV-A (24/7, 1-hour response, 4-hour resolution).  
  - SEV-B (24/7, 4-hour response, 8-hour resolution).  
  - SEV-C (Business hours, 8-hour response, 24-hour resolution).  


<img width="1920" height="1080" alt="Screenshot 2025-09-13 115804" src="https://github.com/user-attachments/assets/ebdb762e-a373-49a9-8c4b-5cb783507b64" />


---

### 8. Configure Help Topics  
- Go to **Admin Panel → Manage → Help Topics**.  
- Examples:  
- Business Critical Outage
- Personal Computer Issues
- Equipment Request
- Password Reset
- Other



<img width="1920" height="1080" alt="Screenshot 2025-09-13 120144" src="https://github.com/user-attachments/assets/1ed7a959-7f7f-4b12-aca4-707042ab21db" />


---

## 📂 Repository Structure  

