# 🎫 Streamlining Ticket Assignment for Efficient Support Operations

A ServiceNow-based automation project designed to simplify and automate ticket assignment using Flow Designer, custom tables, roles, groups, and ACL security.

---

## 👨‍💻 Team Members

- G. Sravani – Users & Groups Creation  
- G. Chandana – Roles & Custom Table Configuration  
- J. Meghana – Role & User Assignment  
- M. Sanjana – ACL Configuration  
- S. Swathi – Flow Automation  

---

## 🎥 Demo

📌 Watch Project Demo:  


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

## ▶️ How to Run the Project

Follow the below steps to run this project in ServiceNow:

### Step 1 — Create ServiceNow Personal Developer Instance
1. Go to https://developer.servicenow.com  
2. Sign in with your account  
3. Create a Personal Developer Instance (PDI)

---

### Step 2 — Import the Update Set
1. Navigate to:
   **System Update Sets → Retrieved Update Sets**
2. Click **Import Update Set from XML**
3. Upload the project update set file (Streamlining Ticket Assignment).
4. Click **Preview Update Set**
5. Resolve any preview problems if shown.
6. Click **Commit Update Set**.

---

### Step 3 — Verify Project Components
After committing, verify the following:

- Custom Table: **Operations Related**
- Users and Groups created
- Roles assigned correctly
- ACL rules configured
- Flow Designer flows available:
  - Regarding Certificates
  - Regarding Platform

---

### Step 4 — Execute the Project
1. Navigate to:
   **Operations Related → New**
2. Fill in ticket details.
3. Select an Issue type.
4. Click **Submit**.

---

### Step 5 — Validate Automation
- If issue = Regarding Certificates  
  → Ticket auto-assigns to **Certificate Group**

- If issue = Platform related / Login / 404 / User Expired  
  → Ticket auto-assigns to **Platform Group**

---

### Step 6 — Verify Results
1. Open the created record.
2. Check **Assigned to Group** field.
3. Confirm automatic assignment by Flow Designer.



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

## 📌 Conclusion
This project successfully demonstrates ServiceNow automation by integrating custom tables, security roles, and Flow Designer to streamline ticket assignment and improve operational efficiency.

---

## 📄 License
Free to use for academic and learning purposes.
