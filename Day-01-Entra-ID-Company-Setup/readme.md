# Day 01 - Microsoft Entra ID Company Setup

## Project Overview

This project simulates the initial identity and access management deployment for a fictional company called FutureTech Solutions.

As the Infrastructure Engineer, I was responsible for building the Microsoft Entra ID structure, creating departmental groups, onboarding users, assigning administrative roles, and implementing foundational security groups.

---

## Business Scenario

FutureTech Solutions is a newly established organization with four departments:

* Information Technology
* Human Resources
* Finance
* Operations

The company requires a centralized identity platform to manage users, permissions, and future Microsoft 365 services.

---

## Objectives

* Create departmental groups
* Create user accounts
* Assign users to appropriate groups
* Configure administrative roles
* Establish naming standards
* Build a scalable identity structure

---

## Technologies Used

* Microsoft Azure
* Microsoft Entra ID
* Role Based Access Control (RBAC)
* Security Groups
* User Administration

---

## User Accounts Created

| User            | Department |
| --------------- | ---------- |
| john.it         | IT         |
| sarah.hr        | HR         |
| michael.finance | Finance    |
| emma.ops        | Operations |

---

## Department Groups

| Group Name      |
| --------------- |
| IT-Team         |
| HR-Team         |
| Finance-Team    |
| Operations-Team |

---

## Security Groups

| Group Name     |
| -------------- |
| M365-License   |
| VPN-Users      |
| Intune-Managed |

---

## Administrative Roles

| User     | Role                   |
| -------- | ---------------------- |
| john.it  | Helpdesk Administrator |
| sarah.hr | User Administrator     |

---

## Naming Standards

### Users

firstname.lastname

Example:

john.it

### Groups

Department-Team

Example:

IT-Team

### Devices

FT-LAPTOP-001

### Servers

FT-SRV-001

---

## Challenges Encountered

Dynamic Group creation was unavailable due to licensing limitations within the lab environment.

As a workaround, users were manually assigned to their respective department groups.

This reflects a common real-world scenario where infrastructure teams must operate within licensing and budget constraints.

---

## Outcomes

Successfully established the foundational identity structure for the organization.

Implemented:

* Department-based access control
* Security groups
* Administrative delegation
* User onboarding process
* Enterprise naming conventions

This environment will be used in future projects involving Microsoft 365, Intune, Conditional Access, and Exchange Online.

---

## Key Skills Practiced

* Microsoft Entra ID Administration
* User Lifecycle Management
* RBAC
* Security Group Management
* Identity Governance
* Infrastructure Documentation

