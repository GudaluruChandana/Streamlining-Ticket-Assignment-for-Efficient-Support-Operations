# 🎫 Streamlining Ticket Assignment for Efficient Support Operations

> 🚀 A ServiceNow automation project designed to intelligently route support tickets to the correct teams using Flow Designer, custom tables, roles, groups, and ACL-based security.

---

## 🌟 Project Overview

Modern support teams often face delays due to manual ticket assignment.  
This project automates ticket routing in ServiceNow based on issue type, ensuring faster resolution, improved efficiency, and optimized resource utilization.

The solution uses:

- Custom Tables
- Flow Designer Automation
- Role-Based Access Control (RBAC)
- ACL Security
- Group-based Assignment Logic

---

## 🎯 Objectives

- Automate support ticket assignment
- Reduce manual intervention
- Improve operational efficiency
- Implement secure role-based access
- Enhance support team productivity

---

## 👨‍💻 Team Members

| Team Member | Responsibility |
|---|---|
| G. Sravani | Users & Groups Creation |
| G. Chandana | Roles & Custom Table Configuration |
| J. Meghana | Role & User Assignment |
| M. Sanjana | ACL Configuration |
| S. Swathi | Flow Automation |

---

## 🧩 Project Architecture

### 🔹 Custom Table

**Operations Related (u_operations_related)**

Used to capture support issues and trigger automation workflows.

---

### 🔹 Issue Categories

- Regarding Certificates
- Unable to login to platform
- 404 Error
- Regarding user expired

---

### 🔹 User Groups

- Certificate Group  
- Platform Group

---

### 🔹 Roles

- Certification_role  
- Platform_role

---

## 🔐 Security Implementation

Role-based security implemented using:

- Access Control Lists (ACL)
- Read & Write permissions
- Admin-level validation

This ensures only authorized users can access or modify records.

---

## ⚙️ Flow Designer Automation

### 📌 Certificate Assignment Flow

**Trigger Condition:**


**Action:**  
➡ Ticket automatically assigned to **Certificate Group**

---

### 📌 Platform Assignment Flow

**Trigger Conditions:**


**Action:**  
➡ Ticket automatically assigned to **Platform Group**

---

## 🧪 Expected Output (Project Validation)

When a new ticket is created:

✔ Flow triggers automatically  
✔ Ticket assigned to correct group  
✔ No manual intervention required  
✔ Flow execution status = Successful

---

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| Platform | ServiceNow (Personal Developer Instance) |
| UI | ServiceNow Forms |
| Automation | Flow Designer |
| Database | ServiceNow Tables |
| Security | Roles & ACL |

---

## ▶️ How to Run the Project

### Step 1 — Create ServiceNow Personal Developer Instance

1. Go to https://developer.servicenow.com  
2. Sign in with your account  
3. Create a Personal Developer Instance (PDI)

---

### Step 2 — Import Update Set

Navigate to:


- Click **Import Update Set from XML**
- Upload project update set
- Click **Preview Update Set**
- Resolve preview issues (if any)
- Click **Commit Update Set**

---

### Step 3 — Verify Components

Ensure the following are available:

- Operations Related table
- Users & Groups
- Roles assigned correctly
- ACL rules configured
- Flow Designer flows:
  - Regarding Certificates
  - Regarding Platform

---

### Step 4 — Execute Project

Navigate to:


- Fill ticket details
- Select Issue type
- Click Submit

---

### Step 5 — Validate Automation

Expected Results:

- Issue = Regarding Certificates  
  → Assigned to Certificate Group

- Issue = Login / 404 / User Expired  
  → Assigned to Platform Group

---

### Step 6 — Verify Results

Open the created record and check:


Confirm automatic assignment via Flow Designer.

---

## 🧪 Testing

✔ Form submission testing  
✔ Flow execution testing  
✔ Group assignment validation  
✔ ACL security verification

---

## 🚀 Future Enhancements

- Email notifications
- SLA tracking
- Dashboard reporting
- Approval workflows
- AI-based ticket categorization

---

## 🏆 Conclusion

This project demonstrates how ServiceNow automation can streamline support operations by combining custom tables, security roles, and Flow Designer to automatically route tickets, reduce manual effort, and improve operational efficiency.

---

## 📄 License

Free to use for academic and learning purposes.
