# Azure Windows Enterprise Infrastructure

**Enterprise Windows infrastructure deployed on Microsoft Azure using Hyper-V, Active Directory Domain Services (AD DS), DNS, DHCP, Windows Deployment Services (WDS), Group Policy and Windows PowerShell.**

##  Executive Summary

This repository documents the successful design, deployment and validation of a Windows-based enterprise infrastructure hosted on Microsoft Azure.

The solution was implemented using nested Hyper-V virtualization to simulate a production Windows enterprise environment. Core infrastructure services including Active Directory Domain Services (AD DS), Domain Name System (DNS), Dynamic Host Configuration Protocol (DHCP), Windows Deployment Services (WDS), Group Policy and Windows Remote Management (WinRM) were deployed to provide centralized identity management, automated operating system deployment, network services and enterprise security.

The completed environment demonstrates the deployment of a fully functional Windows domain consisting of a dedicated Domain Controller and an enterprise workstation capable of centralized authentication, policy enforcement, secure resource access and remote administration.

---

## Business Scenario

A growing organisation required a centralized Windows infrastructure capable of supporting user authentication, workstation deployment, network services and security policy enforcement.

To improve operational efficiency, reduce manual workstation provisioning and provide consistent security across the organisation, an enterprise Windows environment was designed and deployed within Microsoft Azure.

The completed infrastructure enables administrators to deploy new Windows workstations through PXE boot, centrally manage users and computers using Active Directory, automate IP address allocation using DHCP and enforce security policies using Group Policy.


##  Project Objectives

The project was completed to achieve the following objectives: 

- Deployed a Windows Server virtual machine within Microsoft Azure.
- Configured nested Hyper-V virtualization.
- Created external and private virtual networks.
- Deployed and configured a Domain Controller (DC01).
- Installed Active Directory Domain Services (AD DS).
- Configured DNS services for enterprise name resolution.
- Installed and authorized the DHCP Server role.
- Configured a DHCP scope for automatic IP address allocation.
- Installed and configured Windows Deployment Services (WDS).
- Imported Windows boot and installation images into WDS.
- Deployed Windows 10 using PXE network boot.
- Upgraded the deployed workstation to Windows 11.
- Joined the workstation to the Active Directory domain.
- Installed Remote Server Administration Tools (RSAT).
- Created Organizational Units (OU), users, groups and computer accounts.
- Implemented Group Policy Objects (GPOs) to enforce enterprise security policies.
- Configured password complexity and password expiration requirements.
- Restricted user access to Windows Settings and Control Panel.
- Configured secure file sharing using Share and NTFS permissions.
- Protected sensitive data using Encrypting File System (EFS).
- Configured Windows Firewall rules.
- Enabled Windows Remote Management (WinRM).
- Validated the completed infrastructure using PowerShell.


## Solution Architecture

The environment consists of a Microsoft Azure virtual machine hosting a nested Hyper-V infrastructure.

Within Hyper-V, a dedicated Domain Controller provides centralized identity management and network services while a Windows workstation consumes those services as a domain client.

The deployment includes:

- Microsoft Azure Virtual Machine
- Hyper-V
- DC01 Domain Controller
- Wkstn01 Enterprise Workstation
- External Virtual Switch
- Private Virtual Switch
- Active Directory Domain Services
- DNS
- DHCP
- Windows Deployment Services
- Group Policy
- WinRM

A detailed architecture diagram will be included in a later revision.*

## Enterprise Environment 

Component                                     Description 
**Microsoft Azure**                           Cloud platform hosting the Windows Server environment 
**Windows Server 2022**                       Azure Hosted Virtual Machine running the enterprise Infrastructure
**Hyper-V**                                   Nested virtualization platform
**DC01**                                      Enterprise Domain Controller
**Wkstn01**                                   Enterprise Windows workstation
**Active Directory**                          Centralized identity management
**DNS**                                       Name resolution
**DHCP**                                      Automatic IP address allocation 
**WDS**                                       PXE operating system deployment
**Group Policy**                              Enterprise policy management 
**WinRM**                                     Remote administration
**RSAT**                                      Remote management tools


## Technologies Used:

The following technologies were used throughout the deployment and administration of the enterprise environment.

### Cloud Platform
- Microsoft Azure
### Operating System 
- Windows Server 2022
- Windows 10
- Windows 11 
### Virtualisation
- Hyper-V
### identity and Access Management
- Active Directory Domain Services (AD DS)
- Group Policy

### Network Services
- Domain Name System (DNS)
- Dynamic Host Configuration Protocol (DHCP)
- Windows Deployment Services (WDS)

### Administration 

- Windows PowerShell
- Remote Server Administration Tools (RSAT)
- Windows Remote Management (WinRM)

### Security

- Windows Firewall
- NTFS Permissions
- Encrypting File System (EFS)

##  Skills Demonstrated 

The project demonstrates practical skills across cloud infrastructure, Windows Server administration, enterprise networking and security.

### Cloud Infrastructure

- Microsoft Azure virtual machine deployment
- Cloud-hosted infrastructure administration
- Virtual network configuration

### Windows Server Administration

- Windows Server 2022 administration
- Hyper-V virtualisation
- Active Directory Domain Services (AD DS)
- Domain administration

### Enterprise Networking

- DNS configuration and management
- DHCP configuration and scope management
- PXE network deployment using Windows Deployment Services (WDS)
- Virtual switch configuration

### Identity and Access Management

- User and group administration
- Organisational Unit (OU) management
- Computer account management
- Group Policy administration

### Security Administration

- Password policy configuration
- Windows Firewall configuration
- NTFS and Share permissions
- Encrypting File System (EFS)

### System Administration

- Windows PowerShell
- Windows Remote Management (WinRM)
- Remote Server Administration Tools (RSAT)
- Infrastructure validation and troubleshooting
 

## Project Deliverables

The completed project delivered a fully functional Windows enterprise environment hosted on Microsoft Azure with the following capabilities:

- Enterprise Windows Server environment hosted in Microsoft Azure
- Nested Hyper-V virtualisation platform
- Active Directory Domain Services (AD DS)
- Domain Name System (DNS)
- Dynamic Host Configuration Protocol (DHCP)
- Windows Deployment Services (WDS)
- Windows 10 deployment using PXE boot
- Windows 11 workstation upgrade
- Domain-joined client workstation
- Organisational Unit (OU) structure
- User, group and computer account management
- Group Policy implementation
- Secure file sharing with Share and NTFS permissions
- Encrypting File System (EFS)
- Windows Firewall configuration
- Windows Remote Management (WinRM)
- PowerShell validation of deployed services

## Project Status

**Status:** Completed

This repository documents the successful deployment of a Windows enterprise infrastructure hosted on Microsoft Azure.

The project demonstrates the end-to-end implementation of core Windows Server technologies, including Active Directory Domain Services, DNS, DHCP, Windows Deployment Services, Group Policy and enterprise security features. It serves as a practical showcase of cloud-hosted Windows infrastructure administration and reflects the skills developed through hands-on implementation rather than theoretical study.

Future updates to this repository will focus on improving the documentation with architecture diagrams, deployment screenshots and validation evidence while keeping the technical implementation unchanged.




