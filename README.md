# ActiveDirectoryLab
This project demonstrates the setup of a fully functional Windows Server Active Directory environment using Oracle VirtualBox. It serves as a hands-on lab for learning and testing Windows Server administration, domain management, and PowerShell scripting.

# 🛠️ Features
Deployed Windows Server 2019 and Windows 10 virtual machines

Configured Active Directory Domain Services (AD DS)

Promoted the server to a domain controller

Set up DNS and DHCP services

Joined a Windows 10 client machine to the domain

Automated the creation of multiple user accounts using PowerShell scripting

# 📦 Requirements
Oracle VirtualBox

Windows Server 2019 ISO

Windows 10 ISO

Minimum hardware: 8 GB RAM, 50 GB free disk space (recommended 16 GB RAM for smoother experience)

# 🚀 Setup Instructions
Install VirtualBox on your host machine.

Create virtual machines:

Windows Server 2019 VM (recommend 4 GB RAM, 2 vCPUs)

Windows 10 VM (recommend 4 GB RAM, 2 vCPUs)

Install Windows Server 2019 and complete initial configuration.

Install AD DS role:

Open Server Manager → Add roles and features → Select AD DS.

Promote server to domain controller:

Run dcpromo or use Server Manager → AD DS → Promote to domain controller.

Configure DNS and DHCP to support the domain.

Set up the Windows 10 client VM:

Install Windows 10.

Join it to the domain (System → About → Join domain).

Automate user creation:

Write and run PowerShell scripts to bulk-create users.

# 💻 Usage
Once the setup is complete, you can:

Practice managing users, groups, and organizational units (OUs)

Test Group Policies and login scripts

Explore domain-joined machine management

Experiment with PowerShell automation in AD
