# Active-Directory-Windows-10-Lab
This project simulates a small IT environment using Windows Server 2022 and Windows 10 Pro in VirtualBox. It demonstrates user onboarding, domain join, DNS configuration, and account management — the same tasks handled by IT Assistants and 1st Line IT Support staff.

# Tools Used
- Oracle VirtualBox  
- Windows Server 2022 (Standard Evaluation)  
- Windows 10 Pro (x64)
  
# Lab Setup
*Domain Controller (DC1)* 
- Configured with Active Directory Domain Services (AD DS)  
- Domain: `lab.local`  
- Static IP: `192.168.10.10`  
- DNS service running locally
  
# Windows 10 Client (Win10Client)  
- Joined to domain `lab.local`  
- Static IP: `192.168.10.11`  
- DNS pointing to DC1

# Networking
- Adapter 1: NAT (Internet access)  
- Adapter 2: Internal Network `LabNet` (Domain traffic)

# Tasks Completed
- Installed and configured Windows Server 2022 as a Domain Controller  
- Set up DNS and static IP addressing  
- Installed Windows 10 client and joined it to the domain  
- Created users: **Alice Smith** and **Bob Jones**  
- Created groups: **Employees**, **Sales**  
- Added Bob Jones to the Sales group  
- Logged in as Alice and Bob on the client machine  
- Verified group memberships with `whoami /groups`  
- Tested connectivity with `ping`

# Screenshots
Screenshots are available in the `/Screenshots` folder, including:  
- Domain join success  
- ADUC showing user accounts  
- Group membership (Bob in Sales)  
- Ping tests between client and server  
- Successful logins as Alice and Bob

# Skills Demonstrated
- Active Directory setup and management  
- User onboarding and account management  
- Password reset and login troubleshooting  
- Group-based access control  
- Network configuration and testing  
- First-line IT support practices

# Purpose
This lab demonstrates practical IT support skills relevant to an IT Assistant role.  
It shows the ability to configure, troubleshoot, and manage a Windows domain environment, the same tasks performed in day-to-day IT support.
