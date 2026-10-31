# NETWORKWALKS-B084-WEEK1-CYBERSECURITY-LAB-SETUP
 ## Project Overview (Week 1 | Project Module 1)
This repository contains the documentation and proof of execution for setting up a baseline Cybersecurity testing lab environment. The lab consists of a host machine running VirtualBox and a Kali Linux virtual machine configured for penetration testing tasks.

##  Lab Requirements Achieved
- **Hypervisor:** VirtualBox (Latest Version)
- **Attacker Machine:** Kali Linux (Latest Version, VM)
- **Network Configuration:** NATNetwork configured with `10.0.0.0/24` subnet
- **VM Settings:** Bidirectional Clipboard & File drag/drop enabled
- **Shared Folders:** `/downloads` folder successfully shared from the host machine to the VM
- **IP Configuration:** Kali Linux assigned the IP Address `10.0.0.2/24`
- **Connectivity:** Verified that Kali Linux has full Internet access

## 📸 Proof of Concept (Screenshots)

Below are the screenshots verifying the successful configuration of the lab environment:

### 1. Kali Linux virtual machine
[Kali linux](kaliVM.png)

### 2. VirtualBox NAT Network Configuration
[NAT Network](NAT.png)

### 3. Kali Linux IP Address (`10.0.0.2`)
[Kali IP Address](ipconfig.png)

### 4. Internet Access
[Internet Access such as ping](ping.png)

### 4.Snapshot of VM
[snapshot](snapshotVM.png)
