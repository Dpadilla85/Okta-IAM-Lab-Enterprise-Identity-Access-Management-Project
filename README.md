# Okta IAM Lab – Enterprise Identity & Access Management Project

## 📌 Overview
This project demonstrates the design and implementation of an enterprise-grade Identity and Access Management (IAM) solution using Okta. It showcases hands-on experience configuring core IAM components including user lifecycle management, directory integration, authentication policies, and secure Single Sign-On (SSO).

The goal of this project is to simulate a real-world enterprise environment and apply security best practices aligned with Zero Trust principles.

---

## 🧱 Architecture Summary
This lab environment includes:

- Okta tenant (Identity Provider)
- Active Directory integration via Okta AD Agent
- User and group lifecycle management
- Group-based access control
- Authentication and security policies
- Application SSO integrations

> 📊 *Architecture diagram available in the `/architecture` folder*

---

## 🔑 Key Features & Implementations

### 👤 User & Group Management
- Created and managed users within Okta
- Imported users from Active Directory
- Designed group structures for role-based access control (RBAC)
- Implemented dynamic group rules for automated user assignment

---

### 🔐 Authentication & Security Policies
- Configured **Password Policies** based on user groups
- Implemented **Sign-On Policies** with conditional access
- Enabled **Multi-Factor Authentication (MFA)** using Okta Authenticators
- Configured **Global Session Policies** for session security

---

### 🛡️ Password Policy Configuration
Example of a high-security password policy:

- Minimum length: 12 characters  
- Complexity: Uppercase, lowercase, number, symbol  
- Account lockout: 5 failed attempts  
- Password history: Last 10 passwords  

**Use Case:**  
Applied stricter policies to privileged groups (e.g., admins) to reduce risk of credential compromise.

---

### 🔄 Directory Integration (Hybrid Identity)
- Installed and configured Okta AD Agent
- Imported Organizational Units (OUs)
- Enabled delegated authentication
- Synced users and groups between AD and Okta

---

### 🔗 Application SSO Integration
- Configured SSO for applications using Okta
- Demonstrated centralized identity management
- Implemented secure access workflows

---

### 🌐 Org2Org Integration
- Connected multiple Okta tenants
- Demonstrated cross-org identity federation

---

## 🧠 Design Principles

This project follows modern IAM and security best practices:

- **Zero Trust Security Model**
- **Least Privilege Access**
- **Group-Based Policy Enforcement**
- **Centralized Identity Management**
- **Elimination of Legacy Authentication**

---

