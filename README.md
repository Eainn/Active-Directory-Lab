# Active Directory Lab

## Overview

Built a Windows Server 2022 Active Directory lab in VMware to gain hands-on experience with Windows Server administration, identity and access management, and domain services.

## Lab Objectives

* Deploy a Windows Server 2022 Domain Controller
* Configure Active Directory Domain Services (AD DS)
* Configure DNS services
* Create Organizational Units (OUs)
* Create and manage domain user accounts
* Simulate common IT Support and System Administration tasks

## Environment

| Component  | Details             |
| ---------- | ------------------- |
| Hypervisor | VMware Workstation  |
| Server     | Windows Server 2022 |
| Domain     | corp.local          |
| Hostname   | DC01                |

## Configuration Steps

### 1. Server Deployment

* Installed Windows Server 2022
* Renamed server to DC01
* Configured a static IP address

### 2. Active Directory Deployment

* Installed Active Directory Domain Services (AD DS)
* Promoted the server to a Domain Controller
* Created a new forest and domain: **corp.local**

### 3. Identity and Access Management

Created Organizational Unit:

* IT Department

Created domain user accounts:

* helpdesk.user
* soc.analyst
* it.support

## Skills Demonstrated

* Windows Server Administration
* Active Directory Administration
* User Account Management
* Organizational Unit (OU) Management
* DNS Configuration
* Identity and Access Management (IAM)
* IT Support Fundamentals

## Screenshots

### Server Renamed to DC01

![Server Renamed](screenshots/02-server-renamed-dc01.png)

### Static IP Configuration

![Static IP](screenshots/03-static-ip-configured.png)

### Active Directory Domain Services Installed

![AD DS Installed](screenshots/04-adds-installed.png)

### Domain Controller Created

![Domain Created](screenshots/05-domain-created-corp-local.png)

### Active Directory Users and Computers

![ADUC](screenshots/06-aduc-console.png)

### Organizational Unit Created

![OU Created](screenshots/07-ou-created.png)

### Domain Users Created

![Users Created](screenshots/08-users-created.png)
