# 🖥️ Windows Server Infrastructure Deployment Project

**Author:** Junior Kalomba  
**Role:** Systems Administrator  
**Date:** July 2025

---

## 📘 Overview

This project demonstrates the deployment and configuration of a full Windows Server 2022 infrastructure in a simulated business environment using VMware. It includes Active Directory, DNS, DHCP, Group Policy Objects (GPO), and a secured File Server.

The goal was to simulate a real-world IT environment with centralized user management, role-based access control, and secure network services.

---

## 🔧 Tools & Technologies

- **Windows Server 2022**
- **Windows 10/11 Clients**
- **VMware Workstation**
- **Active Directory Domain Services (AD DS)**
- **DNS / DHCP**
- **Group Policy (GPO)**
- **File Server / NTFS Permissions**

---

## 🎯 Objectives Achieved

- ✅ Centralized user authentication using Active Directory  
- ✅ Role-based Organizational Units (OUs) and Groups  
- ✅ Automated IP management via DHCP  
- ✅ Domain-level name resolution with DNS  
- ✅ GPO enforcement (password policy, control panel restrictions, drive mapping)  
- ✅ Secure file sharing with NTFS and Share-level permissions  

---

## 🗂️ Project Breakdown

### 🔹 Step 1: Rename the Server
Renamed the server to `DC01` to prepare for Domain Controller promotion.

### 🔹 Step 2: Static IP Setup
Configured a static IP: `192.168.1.10` for consistent DNS/DHCP service.

### 🔹 Step 3: Install AD DS Role
Installed and promoted the server to a Domain Controller with domain: `kalomba.local`.

### 🔹 Step 4: Create OUs, Users & Groups
Created `IT`, `HR`, `Sales` OUs. Created user accounts and added them to corresponding Security Groups.

### 🔹 Step 5: Install and Configure DHCP
Deployed DHCP role with a scope (192.168.1.100–192.168.1.200) and linked it to the domain.

### 🔹 Step 6: Group Policy Configuration
Used GPMC to apply security policies:
- Disabled Control Panel access for HR
- Enforced password complexity
- Mapped network drives

### 🔹 Step 7: File Server Setup
Created shared folders (`HR_Reports`, `Sales_Data`, etc.) with NTFS and Share permissions based on group access.

---

## 📸 Screenshots

Screenshots of each configuration step and UI interaction are included in the project PDF.

📄 [Download Full Project Report with Screenshots (PDF)](Junior_Kalomba_Windows_Server_Project_Final.pdf)

---

## 🧠 Skills Demonstrated

- Windows Server Administration  
- Networking & DNS/DHCP Configuration  
- Group Policy & Security Enforcement  
- Organizational Unit & Access Control Design  
- VMware-based Lab Simulation

---

## 📌 Conclusion

This project replicates a typical enterprise network infrastructure, showcasing my ability to configure and manage Windows Server services effectively. It highlights strong foundational skills in system administration and network design.

---

## 🔗 Links

- 📄 [Final Project PDF](Junior_Kalomba_Windows_Server_Project_Final.pdf)
- 🎥 [Live Demo Video](link-to-video) *(coming soon)*

# windows-server
