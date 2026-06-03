# Active-Directory-Hybrid-Identity-Lab-Windows-Server-2025-Microsoft-Entra-ID-Entra-Connect
Built a Hybrid Identity Lab using Windows Server 2022, Active Directory, DNS, Microsoft Entra ID, and Microsoft Entra Connect in VMware. Configured a Domain Controller, OUs, users, security groups, Windows 11 domain integration, and synchronized on-premises identities with Microsoft Entra ID using Password Hash Synchronization.

# Active Directory Hybrid Identity Lab

## Overview

This project demonstrates the implementation of a Hybrid Identity environment using Windows Server 2022, Active Directory Domain Services (AD DS), Microsoft Entra ID, and Microsoft Entra Connect within a VMware-based lab environment. The objective was to synchronize on-premises Active Directory identities with Microsoft Entra ID, providing a real-world hybrid identity solution commonly used in enterprise environments.

## Technologies Used

* Windows Server 2025
* Active Directory Domain Services (AD DS)
* DNS Server
* Microsoft Entra ID (Azure AD)
* Microsoft Entra Connect Sync
* Windows 11
* VMware Workstation
* PowerShell

## Lab Architecture

* **DC01** – Windows Server 2025 Domain Controller
* **Windows 11 Client** – Domain-joined workstation
* **Microsoft Entra ID** – Cloud identity platform
* **Microsoft Entra Connect** – Identity synchronization service

## Key Tasks Performed

### Active Directory Deployment

* Installed and configured Active Directory Domain Services (AD DS).
* Promoted Windows Server 2025 to a Domain Controller.
* Configured DNS services and domain name resolution.
* Created Organizational Units (OUs) for departmental management.
* Created and managed user accounts and security groups.

### Domain Integration

* Configured static IP addressing.
* Joined Windows 11 client machine to the Active Directory domain.
* Verified domain authentication and user logon functionality.

### Hybrid Identity Configuration

* Installed and configured Microsoft Entra Connect.
* Configured Password Hash Synchronization (PHS).
* Enabled Password Writeback.
* Synchronized on-premises Active Directory users with Microsoft Entra ID.
* Verified successful identity synchronization and cloud visibility of users.

### Security & Identity Management

* Configured Self-Service Password Reset (SSPR).
* Implemented Multi-Factor Authentication (MFA) policies.
* Tested user synchronization and password synchronization between on-premises AD and Microsoft Entra ID.

## Skills Demonstrated

* Active Directory Administration
* Microsoft Entra ID Administration
* Hybrid Identity Management
* Identity and Access Management (IAM)
* DNS Administration
* Windows Server Administration
* User and Group Management
* Microsoft Entra Connect Sync
* Password Hash Synchronization
* Password Writeback
* Multi-Factor Authentication (MFA)
* Self-Service Password Reset (SSPR)
* VMware Virtualization
* PowerShell Administration

## Outcome

Successfully built and validated a Hybrid Identity environment that synchronizes on-premises Active Directory identities with Microsoft Entra ID. This project provided hands-on experience with enterprise identity management, cloud integration, authentication services, and Microsoft infrastructure technologies commonly used in System Administrator and Infrastructure Support roles.
