                            # NETWORKWALKS-B084-WK1-PM1-CYBERSECURITY-LAB-SETUP
                                 My week 1 Cybersecurity Internship Task
 # 🔐 Cybersecurity Lab Environment Setup

# 📌 Project Overview:
This project focuses on setting up a virtual cybersecurity and penetration-testing laboratory using VirtualBox and Kali Linux.
The purpose of the lab is to create a controlled environment where cybersecurity tools, network scanning, reconnaissance, vulnerability assessment, and other security-testing activities can be performed safely and repeatedly.
The lab is configured on a private virtual network so that additional machines can be added later and used as targets for authorized security testing.

# 🎯 Objectives:
The main objectives of this project are to:

Install and configure VirtualBox.
Install & import Kali Linux as a virtual machine.
Create a private NAT Network for the cybersecurity lab.
Configure network connectivity for Kali Linux.
Assign a consistent IP address to the Kali VM.
Verify network connectivity and DNS resolution.
Take a clean VM snapshot for recovery.
Document the complete setup process.
Prepare the environment for future cybersecurity projects.

# Purpose of the Lab
The lab provides an isolated and controlled environment for cybersecurity learning and authorized security testing.

It can be used for activities such as:

Network reconnaissance
Port scanning
Vulnerability assessment
Packet analysis
Web security testing
Exploitation practice
Security-tool experimentation

# Problems Encountered & Solutions
After manually configuring the IPv4 settings, Internet connectivity still failed along the line.
Solution: I used the following command on the kali CLI 
"sudo nmcli connection modify "Wired connection 1" ipv4.dad-timeout 0"


# Knowledge and Skills Gained
1. NAT vs NAT Network
A standard NAT configuration and a NAT Network serve different purposes.

A NAT Network allows multiple VMs connected to the same virtual network to communicate with one another while providing network address translation for external connectivity.
2. Virtual Machine
I learnt how to download, install and configure a virtual machine

3. Kali Linux: I learnt how to download, Install and configure kali on virtual box.

4. Static IP Configuration : I learnt how to configure IP Address on machines.

5. Documentation: I learnt about why it is necessary to document every details of work carried about especially taking screenshots and saving them on GITHUB for future purpose.

# Tools Used 
1. VirtualBox: https://virtualbox.org/wiki/Downloads
2. Kali Linux: https://kali.org/get-kali
3. Wireshark:
4. Windows 10:
5. Android:

#  Author
Emmanuel Ujah
Cybersecurity Intern B084
ID: NW-084-000
