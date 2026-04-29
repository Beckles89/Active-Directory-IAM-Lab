# 🛡️ Active Directory IAM Lab

## 📌 Overview
This project demonstrates the implementation of Identity and Access Management (IAM) using Microsoft Active Directory in a virtualized lab environment.

The lab simulates a real-world enterprise network where users, groups, and permissions are managed using role-based access control (RBAC).

---

## 🧰 Technologies Used
- Windows Server 2022
- Active Directory Domain Services (AD DS)
- DNS
- Oracle VirtualBox
- NTFS Permissions
- SMB File Sharing

---

## 🏗️ Lab Setup

### Domain Configuration
- Domain Name: securelab.local
- Domain Controller: DC01

---

## 👥 User Creation

Users were created inside Organizational Units:

- ajohnson (HR)
- bsmith (IT)
- cbrown (Finance)
- dlee (Sales)

---

## 👨‍💼 Group Configuration (RBAC)

Security groups created:

- HR_Users
- IT_Admins
- Finance_Users
- Sales_Users

Users were assigned to groups based on roles.

---

## 📁 File Share Setup

Shared folders created:

- HR
- Finance
- Sales
- IT

Each folder was configured with:
- SMB Share Permissions
- NTFS Permissions

---

## 🔐 Access Control Implementation

### Example:
- HR_Users → Access to HR folder ✔
- Non-HR users → Access denied ❌

This demonstrates:
- Least privilege principle
- Role-based access control

---

## 🧪 Testing

Access was tested using domain user accounts:

Example:

\\DC01\HR$

- Authorized users: Successful access
- Unauthorized users: Access denied

---

## 📸 Screenshots

### Server Setup
![Server Manager](screenshots/server_manager.png)

### Users & Groups
![AD Users](screenshots/ad_users.png)

### Permissions
![Permissions](screenshots/permissions.png)

---

## 🧠 Key Skills Demonstrated

- Active Directory Administration
- Identity & Access Management (IAM)
- Role-Based Access Control (RBAC)
- Windows Server Configuration
- Network File Sharing & Security

---

## 🚀 Outcome

This lab demonstrates how enterprise environments manage user identities and enforce access control using Active Directory.
