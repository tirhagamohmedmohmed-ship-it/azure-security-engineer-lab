# Azure Security Engineer Lab (AZ-500)



## Architecture

![48](48-architecture-diagram.png)

## Overview

This repository documents my hands-on Azure Security labs while preparing for the Microsoft AZ-500 certification.

The project demonstrates practical experience with:

- Azure Firewall
- Azure Firewall Policy
- Azure Virtual Machine
- Azure Key Vault
- Microsoft Defender for Cloud
- Azure Policy
- Azure Monitor
- Log Analytics
- Azure Backup
- Microsoft Entra ID

---

# Lab Walkthrough

## 1. Azure RBAC

### 01. Add Role Assignment

![01](01-Add-Role-Assignment.png)

Configured Azure Role-Based Access Control (RBAC) permissions.

---

## 2. Resource Group

### 02. Resource Group Overview

![02](02-Resource-Group-Overview.png)

Created the Resource Group used throughout the project.

---

## 3. Azure Firewall

### 03. Application Rules

![03](03-Application-Rules.png)

Configured Azure Firewall Application Rules.

---

### 04. Rule Collection Configuration

![04](04-Rule-Collection-Configuration.png)

Configured Firewall Rule Collection Groups.

---

## 5. Log Analytics

### 05. Log Analytics Workspace Creation

![05](05-Log-Analytics-Workspace-Creation.png)

Created a Log Analytics Workspace.

---

### 06. Diagnostic Settings Configuration

![06](06-Diagnostic-Settings-Configuration.png)

Enabled Azure Firewall Diagnostic Logs.

---

### 07. Log Analytics Logs

![07](07-Log-Analytics-Workspace-Logs.png)

Verified Firewall logs inside Log Analytics.

---

## 5. IP Groups

### 08. IP Group Creation

![08](08-IP-Group-Creation.png)

Created Azure IP Groups.

---

### 09. KQL Query

![09](09-KQL-Query.png)

Executed KQL queries to inspect Azure Firewall logs.

---

### 10. IP Group Details

![10](10-IP-Group-Details.png)

Verified the IP Group configuration.

---
## 6. Firewall Rule Collections

### 11. Edit Rule Collection

![11](11-Edit-Rule-Collection.png)

Edited the existing Firewall Rule Collection to update security rules.

---

### 12. Application Rules Configuration

![12](12-Application-Rules-Configuration.png)

Configured Azure Firewall Application Rules to allow specific outbound traffic.

---

### 13. Updated Rule Collection

![13](13-Edit-Rule-Collection-Updated.png)

Verified the updated Rule Collection after applying the new configuration.

---

## 7. Azure Firewall Deployment

### 14. Azure Firewall Creation

![14](14-Azure-Firewall-Creation.png)

Successfully deployed Azure Firewall into the Azure Virtual Network.

---

### 15. Add Network Rule Collection

![15](15-Add-Network-Rule-Collection.png)

Created a new Azure Firewall Network Rule Collection to define allowed network traffic based on source, destination, protocol, and destination ports.

---

### 16. Add Role Assignment

![16](16-Add-Role-Assignment.png)

Granted the required Azure RBAC permissions for managing Azure resources.

---

## 8. Azure Bastion

### 17. Connect using Azure Bastion

![17](17-Connect-Bastion.png)

Connected securely to the Azure Virtual Machine using Azure Bastion.

---

### 18. Reset Virtual Machine Password

![18](18-VM-Reset-Password.png)

Reset the administrator password for the virtual machine.

---

## 9. Route Table

### 19. Route Table

![19](19-Route-Table.png)

Configured a Route Table to force traffic through Azure Firewall.

---

## 10. Microsoft Defender for Cloud

### 20. Just-In-Time VM Access

![20](20-Defender-JIT-Rule.png)

Enabled Just-In-Time VM Access to reduce the attack surface.

---
## 11. IP Groups

### 21. Create IP Group

![21](21-Create-IP-Group.png)

Created an Azure IP Group to simplify firewall rule management.

---

## 12. Microsoft Defender for Cloud

### 22. Microsoft Defender for Cloud Recommendations

![22](22-Microsoft-Defender-Recommendations.png)

Reviewed Microsoft Defender for Cloud security recommendations.

---

### 23. Configure Defender Plan

![23](23-Configure-Defender-Plan.png)

Enabled and configured Microsoft Defender plans for Azure resources.

---

### 24. Virtual Machine Resource Health

![24](24-VM-Resource-Health.png)

Verified the health status of the Azure Virtual Machine.

---

### 25. Azure Resource Health

![25](25-Azure-Resource-Health.png)

Reviewed Azure Resource Health for troubleshooting and availability monitoring.

---

## 13. Azure Key Vault

### 26. Create Certificate

![26](26-Create-Certificate.png)

Created a self-signed certificate in Azure Key Vault.

---

### 27. Storage Account Overview

![27](27-Storage-Account-Overview.png)

Reviewed the Storage Account configuration and settings.

---

### 28. Microsoft Defender Regulatory Compliance

![28](28-Microsoft-Defender-Regulatory-Compliance.png)

Reviewed Regulatory Compliance controls in Microsoft Defender for Cloud.

---

### 29. Key Vault Access Control (IAM)

![29](29-Key-Vault-Access-Control-IAM.png)

Configured Azure RBAC permissions for Azure Key Vault.

---

### 30. Key Vault Secrets

![30](30-Key-Vault-Secrets.png)

Created and managed secrets inside Azure Key Vault.

---
## 14. Azure Key Vault

### 31. Create Certificate

![31](31-Create-Certificate.png)

Created an additional certificate in Azure Key Vault for secure authentication scenarios.

---

### 32. Key Vault Access Control (IAM)

![32](32-Key-Vault-Access-Control-IAM-2.png)

Verified Azure RBAC permissions assigned to Azure Key Vault resources.

---

## 15. Azure Storage

### 33. Storage Account Container

![33](33-Storage-Account-Container.png)

Created a Blob Container inside the Azure Storage Account.

---

### 34. Shared Access Signature (SAS)

![34](34-Shared-Access-Signature.png)

Generated a Shared Access Signature (SAS) to securely delegate temporary access to storage resources.

---

### 35. Blob Overview

![35](35-Blob-Overview.png)

Uploaded and verified Blob Storage objects.

---

### 36. Storage Encryption

![36](36-Storage-Encryption-Key.png)

Reviewed Storage Account encryption settings and key management.

---

## 16. Microsoft Entra ID

### 37. Data Protection

![37](37-Data-Protection.png)

Reviewed Microsoft Entra ID protection and security settings.

---

### 38. Create New User

![38](38-Create-New-User.png)

Created a new Microsoft Entra ID user.

---

### 39. Default Directory Overview

![39](39-Default-Directory-Overview.png)

Reviewed Microsoft Entra ID tenant configuration.

---

## 17. Azure Policy

### 40. Assign Built-in Policy

![40](40-Assign-Built-in-Policy.png)

Assigned a built-in Azure Policy to enforce governance and compliance.

---
## 18. Azure Policy

### 41. Policy Assignment

![41](41-Policy-Assignment.png)

Assigned an Azure Policy to enforce governance across Azure resources.

---

## 19. Azure Storage

### 42. Create Storage Account

![42](42-Create-Storage-Account.png)

Created a new Azure Storage Account following Azure security best practices.

---

## 20. Azure Monitor

### 43. Create Alert Rule

![43](43-Create-Alert-Rule.png)

Configured an Azure Monitor Alert Rule to detect important events.

---

## 21. Azure Policy

### 44. Require Tag on Resources

![44](44-Require-Tag-Policy.png)

Applied an Azure Policy to require specific tags on newly created resources.

---

## 22. Resource Group

### 45. Resource Group Overview

![45](45-Resource-Group-Overview.png)

Verified the deployed Azure resources inside the Resource Group.

---

## 23. Azure Backup

### 46. Create Backup Vault

![46](46-Create-Backup-Vault.png)

Created a Backup Vault to protect Azure workloads.

---

## 24. Virtual Machine

### 47. Virtual Machine Overview

![47](47-VM-Overview.png)

Reviewed the Azure Virtual Machine configuration after completing the deployment.

---

# Skills Demonstrated

- Azure Firewall
- Azure Firewall Policy
- Azure Virtual Network (VNet)
- Network Security
- Route Tables
- IP Groups
- Azure RBAC
- Azure Monitor
- Log Analytics Workspace
- Kusto Query Language (KQL)
- Microsoft Defender for Cloud
- Regulatory Compliance
- Azure Key Vault
- Certificates
- Secrets Management
- Azure Storage Account
- Blob Storage
- Shared Access Signature (SAS)
- Storage Encryption
- Microsoft Entra ID
- Azure Policy
- Azure Backup
- Azure Virtual Machines

---

# Conclusion

This project demonstrates practical hands-on experience with Microsoft Azure Security services while preparing for the Microsoft AZ-500 certification. It covers identity management, network security, monitoring, governance, data protection, storage security, and infrastructure protection through real Azure Portal configurations.

Thank you for visiting this repository.
