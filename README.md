# WINDOWS SERVER ACTIVE DIRECTORY LAB

This lab involves the configuration, administration, and deployment of an enterprise Windows Server environment using the Active Directory Domain Services (AD DS). The lab includes the creation of organizational units, users, groups, assignment of users to their respective groups, creation of shared folders, and configuration of permissions using a Microsoft Windows Server 2019 virtual machine.

## Objective
* learn and understand the processes involved in Windows administration

* Deploy an Active Directory environment

* Manage enterprise users and groups

* Create shared folders and configure permissions on the shared folders



## Lab Environment
In this lab, I used a Microsoft Windows Server 2019 virtual machine hosted on VMware Workstation.

## Active Directory Deployment

I installed Active Directory Domain Services through Server Manager by navigating to
**(Manage > Add Roles and Features)** and selecting the Active Directory Domain Services role. 
I added the required features, and the installation was completed successfully. I promoted the server to a domain controller by configuring a new Active Directory forest with the domain name **training.global**. During the setup process, DNS services and the NetBIOS name were configured automatically, while a Directory Services Restore Mode (DSRM) password was created.


## Organizational Units 

I created Organizational Units to categorize users and groups into their respective departments for easier administration and management. 
I created the following departments:
* IT Department
* HR Department
* Finance Department

Each of these departments consists of their own groups and users. 


## User and Group Creation

## Shared Folder Configuration

## Permissions Configuration

## Skills Demonstrated
