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

I created 8 users in the Active Directory for the various departments in the organization. This was done by right-clicking on the 'create user' icon on the top part of the Active Directory Users and Computers (ADUC), and then creating a new user. 
The following groups were created for each department: 
### IT DEPARTMENT 
- IT_ADMINISTRATORS 
- IT_SUPPORT
   
### HR DEPARTMENT 
- HR_STAFF 
- HR_MANAGERS
  
### FINANCE DEPARTMENT
- FINANCE_TEAM 
- FINANCE_MANAGERS 

The groups were created using the Active Directory Users and Computers (ADUC) by right-clicking on the 'create group' icon on the top part of the ADUC, and then creating a new group. Users were assigned to their respective groups by accessing the user's properties, navigating to the **Member Of** tab, and adding the required group memberships.

![A](screenshots/creation_of_users.png)

*Figure 2.1: Users Created.*

![B](screenshots/adding_user_to_group.png)

*Figure 2.2: User added to a group.*

## Shared Folder Configuration

## Permissions Configuration

## Skills Demonstrated
