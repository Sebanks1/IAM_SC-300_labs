# 🛡️SC-300 Identity and Access Administrator Labs

This repo tracks my hands-on progress through SC-300 labs as I focus on building skills in Identity and Access Management (IAM) with Microsoft Entra (formerly Azure AD). Each lab includes a video walkthrough.

---

## 🔐 Authentication & Access Control Labs

### 💻 Lab – Enable Multi-Factor Authentication (MFA)
**What I did:**  
Set up MFA for users in Microsoft Entra to improve identity security with an extra layer of protection.

📺 [Watch the walkthrough](https://youtu.be/qAM5ESiFXjk?si=oXJDhD0hvDa4O7uK)

---

### 💻 Lab – Configure MFA Registration Policy  
**What I did:**  
Configured policies requiring users to register for MFA during sign-in, helping enforce secure authentication practices across the organization.

📺 [Watch the walkthrough](https://youtu.be/CR7KnYjoF0c?si=B8GTjWHYFL3iSwZH)

---

### 💻 Enabled and configured Self-Service Password Reset (SSPR)  
**What I did:**
Enabled and configured Self-Service Password Reset (SSPR) in Microsoft Entra ID, assigned it to a test group, and validated the end-user password reset process to support secure and efficient account recovery.

📺 [Watch the walkthrough](https://youtu.be/fc62VihS1cQ?si=HM731E1QVgLy1DdC)

---
### 💻 Enabled user risk and sign-in risk policies  
**What I did:**
I configured and enabled user risk and sign-in risk policies in Microsoft Entra to automatically trigger password resets and MFA based on detected identity threats.

📺 [Watch the walkthrough](https://www.youtube.com/watch?v=YeEZblm48j0)

---
### 💻 Implement and Test a Conditional Access Policy 
**What I did:**
I created and tested a Conditional Access policy in Azure Entra ID that blocked user access to a specific application based on defined conditions.

📺 [Watch the walkthrough](https://www.youtube.com/watch?v=VKBDkiKeWb4&list=PLIjdhN2pMMAlr79TFYLziucDtzyEABUxL&index=6)

---

## 🔐 Priviledge Access Management

### 💻 Assign Azure resource roles in Privileged Identity Management (PIM)
**What I did:**
Assigned Azure resource roles using Privileged Identity Management (PIM), set up eligible assignments, configured just-in-time (JIT) access with MFA, and tested role activation to enforce least privilege across Azure resources.

📺 [Watch the walkthrough](https://youtu.be/ha36llBRQo8?si=-cRRjbSEJSN7HXZK)

---
  
### 💻 Configure Privileged Identity Management (PIM) for Microsoft Entra roles
**What I did:**
Configured Privileged Identity Management (PIM) for Microsoft Entra roles by setting up eligible role assignments, enforcing MFA, adding approval workflows, and defining activation settings to limit standing access and support least privilege.

📺 [Watch the walkthrough](https://youtu.be/ES3CUlvG8Kc?si=aLR6cHGFfgWFsnHT)

---

## 🔐 Federation & App Access (SAML_OpenID_OAuth 2.0)

### 💻 Add a Federated Identity Provider
**What I did:**
Configured Azure AD to add a federated identity provider by connecting an external service (like Google), setting up Azure AD B2C settings, and enabling conditional access for external users.

📺 [Watch the walkthrough](https://youtu.be/xF25Zrieqdc?si=RfxPe9LaXUEbiHfM)

---
### 💻 Register an application
**What I did:**
Registered an application in Azure AD (Entra ID) by specifying redirect URIs, selecting supported account types, and capturing the application and directory IDs to enable secure authentication and API access.

📺 [Watch the walkthrough](https://youtu.be/SUfG0xKWa9A?si=CLO81-6qvVD50O50)

---

### 💻 Grant tenant-wide admin consent to an application
**What I did:**
Granted tenant-wide admin consent to an application in Azure AD (Entra ID) by reviewing requested permissions, approving consent on behalf of all users, and verifying that the app could access organizational data without prompting individual users.

📺 [Watch the walkthrough](https://youtu.be/h12WoZ_TXH8?si=Ob1EUIs5qfpDb_s8)

---

### 💻 Implement access management for apps
**What I did:**
Implemented access management for apps in Azure AD (Entra ID) by assigning users and groups to applications, configuring app roles, and applying user consent and access review settings to control and monitor application access.

📺 [Watch the walkthrough](https://youtu.be/V3GJiZfySD0?si=EtCbxtvvfM47ImeO)

---

## 🔐 Identity Governance & Access Reviews

### 💻 Create and manage a catalog of resources in Microsoft Entra entitlement management
**What I did:**
Created and managed a catalog of resources in Microsoft Entra Entitlement Management by setting up access packages, defining resource roles, and organizing groups, apps, and Saleforce sites into a catalog to support automated access requests and governance.

📺 [Watch the walkthrough](https://youtu.be/XY-syeBJZJA?si=YK_EquH_GIEi2wmO)

---

### 💻 Add Terms of Use and Enable Acceptance Reporting  
**What I did:**
Added a Terms of Use policy in Microsoft Entra, assigned it to specific users, and enabled acceptance reporting to track and audit user acknowledgments for compliance.

📺 [Watch the walkthrough](https://youtu.be/5qSrbLW8z1A?si=Ruehr1hEsLoXl6BK)

---

### 💻 Manage the lifecycle of external users in Microsoft Entra Identity Governance settings 
**What I did:**
Managed the lifecycle of external users in Microsoft Entra Identity Governance by configuring access packages, setting expiration policies, and enabling automatic access reviews to control and audit guest user access over time.

📺 [Watch the walkthrough](https://youtu.be/BbLuwopQTFw?si=JFdaqL_SSkBQeoiA)

---

### 💻 Creating Access Reviews for Internal and External Users 
**What I did:**
Created access reviews in Microsoft Entra for both internal and external users to automate periodic access checks, enforce least privilege, and support compliance with identity governance policies.

📺 [Watch the walkthrough](https://youtu.be/aloThE5Z9bI?si=BPEs3qz79vVmNk6l)

---

## 🔐 Monitoring and Reporting

### 💻 Microsoft Sentinel Kusto Queries for Microsoft Entra data sources
**What I did:**
Developed and executed Kusto Query Language (KQL) queries in Microsoft Sentinel to analyze Microsoft Entra identity logs, enabling detection of suspicious activities and improved security monitoring.

📺 [Watch the walkthrough](https://youtu.be/WjBBJBS-7wc?si=PN3O0KUBWj2-LQmJ)

---

### 💻 Monitor and managed security posture with Identity Secure Score
**What I did:**
Navigated to Identity Secure Score in the Entra admin portal, reviewed the current score and historical trends, identified improvement recommendations, and prioritized changes to enhance overall identity security.

📺 [Watch the walkthrough](https://youtu.be/KO5YCiXYUHk?si=YVqTe4SWhjv7O0HU)

---

## 🔐 User and Group Management

### 💻 Manage User Accounts
**What I did:**
Created user accounts in Microsoft Entra ID, assigning roles and licenses, resetting passwords, enabling and disabling accounts, and verifying changes through the Azure portal.

📺 [Watch the walkthrough](https://youtu.be/Dd59xYJmKis?si=9K9PmKTyLO_qJKfC)

---

### 💻 Working with tenant properties
**What I did:**
Reviewed and updated tenant settings in Microsoft Entra ID, including branding, contact info, and privacy URLs, and verified changes in the Microsoft Entra Admin Center.

📺 [Watch the walkthrough](https://youtu.be/DdfTyOKlTO4?si=FZrujh4pnroST2Cg)

---

### 💻 Assigning licenses using group membership
**What I did:**
Created a security group, configuring group-based licensing, added users to the group, and verified that licenses were automatically assigned through Microsoft Entra ID.

📺 [Watch the walkthrough](https://youtu.be/VdlrKvIEMck)

---

## 🌐 External Collaboration

### 💻 Add Guest Users to the Directory
**What I did:**
Created user accounts in Microsoft Entra ID, assigned roles and licenses, reset passwords, enabled and disabled accounts, and verified changes through the Azure portal.

📺 [Watch the walkthrough](https://youtu.be/E7AwPUYb9CE)

---

### 💻 Invite External Users
**What I did:**
Invited external users to Microsoft Entra ID, configured user settings to support external collaboration, customized the invitation process, and verified that the invited users appeared in the directory with appropriate access.

📺 [Watch the walkthrough](https://youtu.be/um5IOXjdFlc)

---

### 💻 Configure External Collaboration Settings
**What I did:**
Configured external collaboration settings in Microsoft Entra ID, updated guest user access policies, adjusted invitation settings, and verified the changes in the Entra Admin Center to control how external users interact with the directory.

📺 [Watch the walkthrough](https://youtu.be/41hu8e4QE3w)

---

## About This Repo
These labs are part of my transition into Identity and Access Management (IAM)
