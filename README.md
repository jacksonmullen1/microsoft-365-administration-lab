# Microsoft 365 Administration Lab

A hands-on Microsoft 365 administration lab designed to simulate real-world IT support and system administration tasks. This project demonstrates practical experience administering Microsoft 365 services including Microsoft Entra ID (Azure AD), Exchange Online, SharePoint Online, OneDrive, Microsoft Intune, Microsoft Defender, Multi-Factor Authentication (MFA), Conditional Access, and user lifecycle management.

---

## Project Overview

This lab was built to gain hands-on experience performing common Microsoft 365 administration tasks found in enterprise IT environments.

The environment simulates a small business called **MullenTech Solutions**, where users, groups, security policies, collaboration tools, and device management were configured using Microsoft 365 Business Premium.

---

## Technologies Used

- Microsoft 365 Admin Center
- Microsoft Entra ID (Azure AD)
- Microsoft Exchange Online
- Microsoft Intune
- Microsoft SharePoint Online
- Microsoft OneDrive
- Microsoft Defender
- Microsoft Teams
- Multi-Factor Authentication (MFA)
- Conditional Access
- Windows 11

---

## Skills Demonstrated

### Identity & Access Management
- Created and managed Microsoft Entra ID (Azure AD) user accounts
- Assigned Microsoft 365 Business Premium licenses
- Created and managed Security Groups and Microsoft 365 Groups
- Configured Multi-Factor Authentication (MFA)
- Implemented Conditional Access policies
- Performed user password resets
- Completed user offboarding by blocking sign-in, removing licenses, and removing group memberships

### Exchange Online Administration
- Created shared mailboxes
- Configured mailbox permissions
- Created and managed distribution groups
- Managed user mailboxes and licensing

### SharePoint & OneDrive Administration
- Created a SharePoint Team Site
- Configured document library permissions
- Managed file sharing using OneDrive
- Configured user access to organizational resources

### Microsoft Intune
- Created device compliance policies
- Created Windows configuration profiles
- Assigned policies to device security groups
- Configured Windows security baseline settings

### Security
- Configured Microsoft Security Defaults
- Created Conditional Access policies requiring Multi-Factor Authentication

---

# Project Walkthrough

## 1. Microsoft 365 Tenant Administration

Created and configured a Microsoft 365 Business Premium tenant for a simulated organization (MullenTech Solutions). The tenant served as the centralized environment for identity management, messaging, collaboration, security, and endpoint management.

![Admin Center Overview](screenshots/01-admin-center-overview.png)

---

## 2. User Provisioning & License Management

Created employee accounts, assigned Microsoft 365 Business Premium licenses, and configured user profiles to simulate onboarding new employees.

### Active Users

![Active Users](screenshots/02-active-users.png)

### User Profile

![Alex Rivera Profile](screenshots/03-user-profile-alex-rivera.png)

---

## 3. Group Management

Created Security Groups for access management and Microsoft 365 Groups for collaboration.

### Security Groups

![Security Groups](screenshots/04-security-groups.png)

### Microsoft 365 Groups

![Microsoft 365 Groups](screenshots/05-microsoft-365-groups.png)

---

## 4. Exchange Online Administration

Configured shared mailboxes and distribution groups to support organizational communication.

### Shared Mailboxes

![Shared Mailboxes](screenshots/06-shared-mailboxes.png)

### Distribution Group

![Distribution Group](screenshots/07-distribution-group.png)
- Configured Microsoft Defender security requirements
- Implemented enterprise identity security best practices

---

## 5. Identity Security

Configured Microsoft Security Defaults and implemented a Conditional Access policy requiring Multi-Factor Authentication (MFA) for employee accounts.

### Security Defaults

![Security Defaults](screenshots/08-security-defaults.png)

### Conditional Access

![Conditional Access](screenshots/09-conditional-access-policy.png)

---

## 6. User Lifecycle Management

Performed a simulated employee offboarding by blocking user sign-in, removing Microsoft 365 licensing, and revoking organizational access.

![User Offboarding](screenshots/10-user-offboarding.png)

---

## 7. SharePoint Online Administration

Created a SharePoint Team Site to simulate centralized document management for organizational departments.

### Team Site

![SharePoint Team Site](screenshots/11-sharepoint-site.png)

### Permission Management

Configured SharePoint document permissions to provide department-specific access.

![SharePoint Permissions](screenshots/12-sharepoint-permissions.png)

---

## 8. OneDrive Administration

Configured secure document sharing between users by assigning edit permissions through OneDrive.

![OneDrive Sharing](screenshots/13-onedrive-sharing.png)

---

## 9. Microsoft Intune

Configured Microsoft Intune to manage organizational security policies and Windows device settings.

### Intune Dashboard

![Intune Dashboard](screenshots/14-intune-home.png)

### Compliance Policy

Created a Windows compliance policy enforcing BitLocker, Secure Boot, TPM, Microsoft Defender Antivirus, password requirements, and assigned the policy to the **Corporate Devices** security group.

![Compliance Policy Settings](screenshots/15A-Compliance-Policy-Settings.png)

![Compliance Policy Assignments](screenshots/15B-Compliance-Policy-Assignments.png)

### Configuration Profile

Created a Windows configuration profile to standardize enterprise device settings and improve endpoint security.

![Configuration Profile Overview](screenshots/16A-Configuration-Profile-Overview.png)

![Configuration Profile Settings](screenshots/16B-Configuration-Settings.png)
