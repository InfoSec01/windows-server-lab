# 🖥️ Windows Server Administration Lab

A hands-on project designed to simulate enterprise-level Windows Server management. This lab focuses on deploying and administering **Active Directory**, **Group Policy**, **File Services**, **DNS**, **DHCP**, and virtualized environments using **Windows Server 2019** and **Windows 10 Pro** VMs.

---

## 🚀 Objectives

- Deploy and configure Windows Server 2019 in a virtual lab  
- Implement Active Directory and domain services  
- Apply Group Policies to manage users and endpoints  
- Set up file sharing and access permissions  
- Configure DNS and DHCP for internal name resolution and IP address management  
- Practice VM management and user authentication  

---

## 🧰 Lab Tools & Technologies

- **Windows Server 2019**  
- **Windows 10 Pro**  
- **VirtualBox / VMware Workstation**  
- **Active Directory Domain Services (AD DS)**  
- **Group Policy Management Console (GPMC)**  
- **File and Storage Services**  
- **DNS & DHCP Server Roles**  
- **RSAT (Remote Server Administration Tools)**  

---

## 🛠️ Key Skills Demonstrated

### 🔐 Active Directory
- Deployed AD DS and promoted domain controller  
- Created OUs, users, groups, and managed organizational hierarchy  
- Joined Windows 10 client to the domain  

### ⚙️ Group Policy (GPO)
- Enforced password policies, desktop restrictions, and mapped drives  
- Configured software restrictions and startup scripts via GPMC  
- Linked GPOs to OUs and tested inheritance and precedence  

### 🌐 DNS
- Installed DNS Server role and created Forward Lookup Zone for domain  
- Added A and CNAME records for internal name resolution  
- Verified DNS with `nslookup` and tested connectivity using hostnames  

### 📡 DHCP
- Installed and configured DHCP Server role  
- Created DHCP scope for dynamic IP leasing  
- Set scope options for default gateway, DNS server, and domain name  
- Verified IP assignments with `ipconfig /all` on clients  

### 📁 File Services
- Set up shared folders with NTFS and share permissions  
- Implemented Access-Based Enumeration (ABE)  
- Configured disk quotas and monitored storage usage  

### 🧪 VM Lab Environment
- Built isolated network for Windows VMs in VirtualBox  
- Snapshots used to test policy changes and rollback scenarios  
- Simulated user logins to validate access control  

---

## 📸 Screenshots

> Add screenshots showing:
- AD DS installation and domain structure  
- GPO creation and link to OUs  
- DNS Forward Lookup Zone and A records  
- DHCP scope and lease assignments  
- File share permission settings  
- Windows 10 client joined to domain  

---

## 📄 Summary

This lab demonstrates core skills required for Windows System Administration roles. By integrating **AD**, **GPO**, **DNS**, **DHCP**, and **file services** in a virtual environment, it simulates real-world IT infrastructure management and helps enforce enterprise-level security, identity control, and network automation.

---

## 🔗 Related Projects

- [Linux System Administration Lab](https://github.com/YourUsername/Linux-Lab)  
- [Penetration Testing Lab](https://github.com/YourUsername/PenTest-Lab)  

---

## 📬 Contact

**Baratul Khan**  
💼 [LinkedIn](https://www.linkedin.com/in/baratulkhan)  
📧 baratulkhan@gmail.com  
🔗 [GitHub](https://github.com/InfoSec01)
