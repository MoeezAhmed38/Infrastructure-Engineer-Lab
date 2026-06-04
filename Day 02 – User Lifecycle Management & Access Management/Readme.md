## Project Overview

This project simulates day-to-day identity and access management activities performed by a System Administrator or Infrastructure Engineer within a Microsoft Entra ID environment.

The objective was to manage the complete employee lifecycle, including onboarding, department transfers, offboarding, access reviews, and security group administration.

---

## Business Scenario

FutureTech Solutions continues to grow and requires ongoing management of employee accounts and access permissions.

As the Infrastructure Engineer, I was responsible for ensuring users received appropriate access based on their role while maintaining security and governance standards.

The following requests were received from Human Resources and Management:

* Onboard a new employee
* Process an internal department transfer
* Offboard a departing employee
* Conduct an access review
* Prepare the environment for future growth

---

## Technologies Used

* Microsoft Entra ID
* Azure Portal
* Role Based Access Control (RBAC)
* User Administration
* Security Groups
* Identity Governance

---

## Task 1 - New Employee Onboarding

### User Created

| User          | Department |
| ------------- | ---------- |
| david.finance | Finance    |

### Actions Completed

* Created user account
* Assigned Finance-Team membership
* Assigned M365-License group
* Verified account configuration

### Outcome

Successfully onboarded a new employee and assigned appropriate department-based access.

---

## Task 2 - Internal Department Transfer

### User Modified

| User     | Previous Department | New Department |
| -------- | ------------------- | -------------- |
| emma.ops | Operations          | HR             |

### Actions Completed

* Removed Operations-Team membership
* Added HR-Team membership
* Verified updated access permissions

### Outcome

Access permissions were successfully aligned with the employee's new role.

---

## Task 3 - Employee Offboarding

### User Offboarded

| User            |
| --------------- |
| michael.finance |

### Actions Completed

* Blocked sign-in access
* Reset account password
* Reviewed group memberships
* Retained account for future data retention requirements

### Outcome

User access was securely revoked while preserving organizational data.

---

## Task 4 - Access Review

An access review was conducted to verify group memberships and ensure users maintained appropriate permissions.

### Current Access Matrix

| User            | Department | Group Membership |
| --------------- | ---------- | ---------------- |
| john.it         | IT         | IT-Team          |
| sarah.hr        | HR         | HR-Team          |
| david.finance   | Finance    | Finance-Team     |
| emma.ops        | HR         | HR-Team          |
| michael.finance | Disabled   | Finance-Team     |

### Findings

* Group memberships aligned with departmental responsibilities.
* No excessive administrative privileges were identified.
* Offboarded user access was successfully disabled.

---

## Task 5 - Future Growth Planning

The following groups were created to support future business requirements:

| Group          |
| -------------- |
| Managers       |
| Remote-Workers |
| Contractors    |

These groups will be used in future projects involving Conditional Access, Intune, and remote access controls.

---

## Security Review

A basic account security review was performed.

Checks included:

* User status
* Group memberships
* Administrative privileges
* Account lifecycle status

### Results

* Active users retained only required access.
* Disabled user access was successfully removed.
* Environment remained aligned with least privilege principles.

---

## Key Skills Practiced

* User Lifecycle Management
* User Onboarding
* User Offboarding
* Group Administration
* Access Reviews
* RBAC
* Identity Governance
* Security Administration

---

## Business Value

This project demonstrated how identity management processes support operational efficiency and security within an organization.

Proper onboarding, access modification, and offboarding procedures reduce security risks and ensure users maintain appropriate access throughout their employment lifecycle.

