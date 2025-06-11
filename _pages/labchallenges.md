---
title: Lab Challenges
permalink: /labchallenges/
---

# 🧪 Lab Challenges

## 🔧 Lab 05 – Implement Intersite Connectivity  
**Platform:** Microsoft Azure (AZ-104)  
**Program:** Microsoft ADC Cybersecurity Skilling Program

---

### 📝 Problem Statement

Create and configure multiple Azure virtual machines across different virtual networks, then enable secure communication between them using virtual network peering. Validate connectivity through tools like Network Watcher and PowerShell.

---

### 🧭 Approach

1. **Deployed VMs in Isolated VNets**  
   - Created two separate virtual machines in different virtual networks (CoreServicesVnet and ManufacturingVnet).

2. **Tested Initial Connectivity**  
   - Used Azure Network Watcher to run diagnostics and confirm that the VMs were not reachable across VNets.

3. **Configured VNet Peering**  
   - Established bi-directional virtual network peerings to allow secure cross-VNet communication.

4. **Tested Post-Peering Connectivity**  
   - Verified successful RDP port connectivity (3389) using PowerShell’s `Test-NetConnection` from one VM to another.

5. **Created Custom Routes**  
   - Designed and implemented a custom route table for future use with a Network Virtual Appliance (NVA).

---

### 🛠 Tools & Services Used

- Microsoft Azure Portal  
- Virtual Machines (VM)  
- Virtual Networks (VNet)  
- Network Watcher  
- Azure PowerShell  
- Route Tables

---

### 📸 Screenshots

- ![VM Creation](images/lab05_vm_creation.png)  
- ![Peering Configuration](images/lab05_peering.png)  
- ![PowerShell Test](images/lab05_powershell.png)  

---

### 💡 Key Lessons Learned

- Understanding the role of **network peering** in Azure to enable private communication across isolated networks.
- Using **Network Watcher** and **PowerShell scripts** to troubleshoot and verify connectivity.
- Creating **custom route tables** to simulate advanced network routing setups (e.g., NVAs).
- Gained deeper insights into managing cloud-based network infrastructure for enterprise use.

---

> ✅ This lab strengthened my understanding of cloud networking and intersite security configurations in Azure.
