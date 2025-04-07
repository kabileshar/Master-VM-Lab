# 💻 Virtualization and Cloud Security – Lab 1

**Course:** INFO8855 – Virtualization and Cloud Security  
**Student:** Kabileshar Ramakrishnan Mohan Kumar  
**Student ID:** 8856188  

This repository contains lab work focused on virtualization, VM deployment, private cloud infrastructure, and secure identity management using VMware tools.

---

## 📚 Overview

The goal of this lab is to:
- Create a **Golden Master Image (GMI)** in VMware
- Clone and deploy VMs from the master image
- Configure **private cloud infrastructure** using ESXi and vCenter
- Secure authentication via **Active Directory**
- Centrally manage hosts using **vCenter Server Appliance**

---

## 🛠️ Technologies Used
- **VMware Workstation**
- **VMware vSphere & vCenter**
- **ESXi Hosts**
- **Windows Server (AD DS)**
- **Kali Linux**

---

## ✅ Lab Breakdown

### 🔸 Lab 1.1 – Master VM Lab
- **Task 1:** Created a base VM using Kali Linux
- **Task 2:** Exported the VM as an OVF/OVA (Golden Master Image)
- **Task 3:** Cloned and deployed two VMs from the master image

### 🔸 Lab 1.2 – Private Cloud Infrastructure Lab
- **Task 1:** Setup and authenticated ESXi hosts with Active Directory
- **Task 2:** Installed and configured vCenter Server Appliance (VCSA)
- **Task 3:** Added ESXi hosts to the datacenter and managed via vCenter

---

## 💡 Key Concepts Learned
- Benefits of using a Golden Master Image
- Difference between OVF and OVA
- Configuring NTP and Active Directory for secure environments
- Single Sign-On (SSO) using AD
- Centralized host management using vCenter

---

## 📸 Screenshots
> Screenshots and detailed documentation can be found in the lab document:  
**`LAB - 1 - Master VM Lab.docx`**

---

## 🧠 Reflections
This lab gave me hands-on experience with enterprise-level virtualization tools. I understood the importance of:
- Config management
- Secure identity and access
- Infrastructure as a service (IaaS) models
- Real-world use cases for vSphere and AD integration

---

## 🔗 References
- [Benefits of Active Directory](https://www.microsoft.com/en-us/security/business/identity-and-access-management/benefits-of-active-directory)
- [VMware vCenter Server – PDF](https://www.vmware.com/content/dam/digitalmarketing/vmware/en/pdf/products/vcenter/VMware_vCenter_Server.pdf)
- [Why is NTP Important?](https://www.greywizard.com/why-is-ntp-important/)
- [What is Single Sign-On (SSO)?](https://learn.microsoft.com/en-us/azure/active-directory/manage-apps/what-is-single-sign-on)

---

## 📁 Project Structure
## ✍️ Author
**Kabileshar Ramakrishnan Mohan Kumar**  
Cybersecurity & Cloud Enthusiast | VMware 🛡️