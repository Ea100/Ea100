# Cyber Security_Capstone_Project
As part of my cybersecurity training, I worked on this project to put theory into practice. It focuses on building a virtual lab environment and analyzing a mobile forensic image using real-world tools

### Project Title: Building a Virtual Cybersecurity Laboratory and Conducting Android Forensics Investigations

[Project Overview](#project-overview)

[Cyber Lab Setup](#Cyber-Lab-Setup)

[Screenshots & Configuration Evidence](#Screenshots-&-Configuration-Evidence)

[Tools Used](#tools-used)

[Virtual Machine Configuration](#Virtual-Machine-Configuration)

[Networking Setup](#Networking-Setup)

[Android Forensics](#Android-Forensics)

### Project Overview
---
This project demonstrates the practical implementation of cybersecurity concepts learned over the three-month training program.  It entails establishing a fully functional virtual cybersecurity lab as well as conducting a forensic investigation of an Android image with industry-standard tools.  The objective is to replicate real-world circumstances for threat analysis, evidence extraction, and secure network design..

### Cyber Lab Setup - Tools, Networking, and Configuration Notes
---
### Screenshots & Configuration Evidence
---
![Kali Linux IP Address](https://github.com/user-attachments/assets/da8346c8-346f-48c3-8764-7178e45b9dbe)
![Lab environment](https://github.com/user-attachments/assets/3ae4a9f5-0d77-4148-a645-d216f3a1d19c)
![Kali Linux completed VM](https://github.com/user-attachments/assets/fe3b7062-1f89-45b3-a8fd-2f10911d6b9b)
![Windows 10 Set up](https://github.com/user-attachments/assets/fbe11e90-1691-4922-bc01-affbc3f6b009)
![Windows 10 completed VM](https://github.com/user-attachments/assets/d8c429a4-650b-429b-89c7-038526c2e667)
![Ping Test](https://github.com/user-attachments/assets/2721d44a-f625-46e9-be76-b1f2ef5302bd)

### Tools Used
---
- VirtualBox (Type 2 Hypervisor): Used to create and manage virtual machines
- Kali Linux (Attacker VM)
- Windows 10 (Target VM): Simulates a vulnerable system for security testing

### Virtual Machine Configuration
---
- RAM: 2 GB
- Storage: 20 GB (dynamically allocated)
- Processor: 2 virtual CPUs
- BIOS Virtualization: Enabled in host system to support VM performance

### Networking Setup
---
- Network Mode: Internal Network (VirtualBox)
  1. Both VMs were connected to a private internal network
  2. This isolated network ensures secure communication between the attacker and target VMs without internet exposure
 
### Connectivity Test
---
 1. Verified network setup by running ping from Kali to the Windows VM.
 2. Conducted basic service enumeration using nmap on Kali to scan open ports and running services on the Windows VM.


### Android Forensics


