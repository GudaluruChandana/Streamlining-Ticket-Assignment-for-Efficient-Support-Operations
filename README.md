# 🎫 Streamlining Ticket Assignment for Efficient Support Operations

A ServiceNow-based automation project designed to simplify and automate ticket assignment using Flow Designer, custom tables, roles, groups, and ACL security.

---

## 📌 Overview

### 🎯 Purpose
This project automates support ticket routing in ServiceNow to reduce manual work, improve response time, and ensure efficient group-based ticket handling.

### ✨ Key Features
- 🧑‍💻 Custom **Operations Related** table
- 👥 User & Group management (Certificate & Platform)
- 🔐 Role-based access using ACL
- ⚙️ Automated ticket assignment using Flow Designer
- 📄 Issue-based routing logic
- 🚀 Reduced manual intervention

---

## 🛠 Tech Stack

| Layer | Technology |
|-------|------------|
| Platform | ServiceNow (Personal Developer Instance) |
| UI | Form-based Modules |
| Logic | Flow Designer |
| Database | ServiceNow Tables |
| Security | Roles & ACL |

---

## ⚙️ Project Modules

### 👤 Users
Created users for support team members.

### 👥 Groups
- Certificate Group  
- Platform Group  

### 🔑 Roles
- Certification_role  
- Platform_role  

### 🗂 Custom Table
**Operations Related (u_operations_related)**

### 🧾 Issue Choices
- Regarding Certificates  
- Unable to login to platform  
- 404 Error  
- Regarding user expired  

---

## 🔄 Flow Automation

### 📌 Certificate Flow
If issue = *Regarding Certificates*  
➡ Ticket auto-assigned to **Certificate Group**

### 📌 Platform Flow
If issue =  
- Unable to login  
- 404 Error  
- User expired  

➡ Ticket auto-assigned to **Platform Group**

---

## ▶️ How It Works

1. User opens Operations Related form  
2. Enters issue details  
3. Clicks **Submit**  
4. Flow Designer triggers automatically  
5. Ticket gets assigned to correct group  

---

## 🧪 Testing
✔ Manual testing performed for:
- Form submission  
- Flow execution  
- Group assignment  
- ACL access control  

---

## 🔐 Authentication
- Role-based access within ServiceNow  
- Admin-level testing environment  

---

## 🚀 Future Scope
- Email notifications  
- Dashboard reporting  
- SLA tracking  
- Advanced workflow approvals  

---

## 👨‍💻 Team Members

- G. Sravani – Users & Groups  
- G. Chandana – Roles & Table Creation  
- J. Meghana – Role & User Assignment  
- M. Sanjana – ACL Configuration  
- S. Swathi – Flow Automation  

---

## 📌 Conclusion
This project successfully demonstrates ServiceNow automation by integrating custom tables, security roles, and Flow Designer to streamline ticket assignment and improve operational efficiency.

---

## 📄 License
Free to use for academic and learning purposes.
