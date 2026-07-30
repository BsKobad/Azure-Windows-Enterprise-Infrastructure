#  Azure-Hosted Windows Enterprise Infrastructure 

>**Enterprise Windows Infrastructure Deployment | Microsoft Azure | Hyper-V | Active Directory | Windows Deployment Services | Group Policy**

##  Executive Summary

This repository documents the successful design, deployment and validation of a Windows-based enterprise infrastructure hosted on Microsoft Azure.

The solution was implemented using nested Hyper-V virtualization to simulate a production Windows enterprise environment. Core infrastructure services including Active Directory Domain Services (AD DS), Domain Name System (DNS), Dynamic Host Configuration Protocol (DHCP), Windows Deployment Services (WDS), Group Policy and Windows Remote Management (WinRM) were deployed to provide centralized identity management, automated operating system deployment, network services and enterprise security.

The completed environment demonstrates the deployment of a fully functional Windows domain consisting of a dedicated Domain Controller and an enterprise workstation capable of centralized authentication, policy enforcement, secure resource access and remote administration.

---

# Business Scenario

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


# Solution Architecture

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

# Enterprise Environment 

Component                                     Description 
Microsoft Azure                        Cloud platform hosting the Windows Server environment 
Hyper-V                                Nested virtualization platform
DC01                                   Enterprise Domain Controller
Wkstn01                                Enterprise Windows workstation
Active Directory                       Centralized identity management
DNS                                    Name resolution
DHCP                                   Automatic IP address allocation 
WDS                                    PXE operating system deployment
Group Policy                           Enterprise policy management 
WinRM                                  Remote administration
RSAT                                   Remote management tools


#  Technologies Used:

Microsoft Azure 
Windows Server
Windows 10
Windows 11
Hyper-V 
Active Directory Domain Services (AD DS)
Domain Name System (DNS)
Dynamic Host Configuration Protocol 
Windows Deployment Service (WDS)
Group Policy Management
Remote Server Administration tools (RSAT)
Windows Remote Management (WinRM)
Windows Power Shell
Windows firewall
NTFS permissions
Encrypting File System (EFS)

#  Skills Demonstrated 

## Cloud Infrastructure

- Microsoft Azure Virtual Machines
- Infrastructure Deployment
- Virtual Network Configuration

## Windows Server Administration

- Windows Server Administration
- Hyper-V Virtualization
- Active Directory Administration
- DNS Administration
- DHCP Administration
- Windows Deployment Services

## Enterprise Networking

- Virtual Switching
- IP Address Management
- PXE Network Deployment
- Domain Integration

## Identity and Access Management

- Active Directory Users and Computers
- Organizational Units
- Security Groups
- Authentication
- Authorization

## Enterprise Security

- Group Policy
- Password Policies
- Windows Firewall
- NTFS Permissions
- Share Permissions
- Encrypting File System

## Automation and Administration

- Windows PowerShell
- WinRM
- RSAT
- Enterprise Validation
 

# Technical Deliverables

The completed infrastructure includes:

- Azure-hosted Windows Server environment
- Nested Hyper-V deployment
- Enterprise Active Directory domain
- DNS infrastructure
- DHCP infrastructure
- Windows Deployment Services
- Windows 10 PXE deployment
- Windows 11 upgrade
- Enterprise workstation domain integration
- Organizational Unit administration
- Group Policy implementation
- Secure file sharing
- Enterprise firewall configuration
- Remote administration
- PowerShell validation




