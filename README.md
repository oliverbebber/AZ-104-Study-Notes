# AZ-104-Study-Notes
Microsoft AZ-104: Azure Administrator Associate Study Notes

# Disclaimer
Do not rely on these notes to pass the exam. It's advised to use Microsoft's study guide for the exam: https://learn.microsoft.com/en-us/certifications/resources/study-guides/az-104

Microsoft has listed several study resources on their study guide.

Additional Microsoft resources:
- [Manage Azure Identities & Governance Video](https://learn.microsoft.com/en-us/shows/exam-readiness-zone/preparing-for-az-104-manage-azure-identities-and-governance-1-of-5)
- [Implement & Manage Storage Video](https://learn.microsoft.com/en-us/shows/exam-readiness-zone/preparing-for-az-104-implement-and-manage-storage-2-of-5)
- [Deploy & Manage Azure Compute Resources Video](https://learn.microsoft.com/en-us/shows/exam-readiness-zone/preparing-for-az-104-deploy-and-manage-azure-compute-resources-3-of-5)
  - Note: the instructor covers ARM template elements, however, in this video there is a discrepency between what the instructor states is required and what the documentation states is required.
  - See [Template Format](https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/syntax#template-format)
- [Configure & Manage Virtual Networking Video](https://learn.microsoft.com/en-us/shows/exam-readiness-zone/preparing-for-az-104-configure-and-manage-virtual-networking-4-of-5)
- [Monitor & Backup Azure Resources Video](https://learn.microsoft.com/en-us/shows/exam-readiness-zone/preparing-for-az-104-monitor-and-maintain-azure-resources-5-of-5)

## Skills measured as of July 28, 2023

### Audience profile

Candidates for this exam should have subject matter expertise in implementing, managing, and monitoring an organization’s Microsoft Azure environment, including virtual networks, storage, compute, identity, security, and governance.

An Azure administrator often serves as part of a larger team dedicated to implementing an organization's cloud infrastructure. Azure administrators also coordinate with other roles to deliver Azure networking, security, database, application development, and DevOps solutions.

Candidates for this exam should be familiar with operating systems, networking, servers, and virtualization. In addition, professionals in this role should have experience using PowerShell, Azure CLI, the Azure portal, Azure Resource Manager templates (ARM templates), and Microsoft Azure Active Directory (Azure AD), part of Microsoft Entra.

---

# Exam Objectives

## Manage Azure identities and governance (20-25%)

### Manage Azure AD objects

- Create users and groups
- Manage user and group properties
- Manage licenses in Azure AD
- Manage external users
- Configure self-service password reset (SSPR)

### Manage access to Azure resources

- Manage built-in Azure roles
- Assign roles at different scopes
- Interpret access assignments

### Manage Azure subscriptions and governance

- Implement and manage Azure Policy
- Configure resource locks
- Apply and manage tags on resources
- Manage resource groups
- Manage subscriptions
- Manage costs by using alerts, budgets, and Azure Advisor recommendations
- Configure management groups

## Implement and manage storage (15–20%)

### Configure access to storage

- Configure Azure Storage firewalls and virtual networks
- Create and use shared access signature (SAS) tokens
- Configure stored access policies
- Manage access keys
- Configure identity-based access for Azure Files

### Configure and manage storage accounts

- Create and configure storage accounts
- Create Azure Storage redundancy
- Configure object replication
- Configure storage account encryption
- Manage data by using Azure Storage Explorer and AzCopy

### Configure Azure Files and Azure Blob Storage

- Create and configure a file share in Azure Storage
- Create and configure a container in Blob Storage
- Configure storage tiers
- Configure snapshots and soft delete for Azure Files
- Configure blob lifecycle management
- Configure blob versioning

## Deploy and manage Azure compute resources (20–25%)

### Automate deployment of resources by using Azure Resource Manager (ARM) templates or Bicep files

- Interpret an ARM template or a Bicep file
- Modify an existing ARM template
- Modify an existing Bicep file
- Deploy resources using an ARM template or a Bicep file
- Export a deployment as an ARM template or compile a deployment as a Bicep file

### Create and configure virtual machines

- Create a virtual machine
- Configure Azure Disk Encryption
- Move a virtual machine to another resource group, subscription, or region
- Manage virtual machine sizes
- Manage virtual machine disks
- Deploy virtual machines to availability zones and availability sets
- Deploy and configure an Azure Virtual Machine Scale Sets

### Provision and manage containers in the Azure portal

- Create and manage an Azure container registry
- Provision a container by using Azure Container Instances
- Provision a container by using Azure Container Apps
- Manage sizing and scaling for containers, including Azure Container Instances and Azure Container Apps

### Create and configure an Azure App Service

- Provision an App Service plan
- Configure scaling for an App Service plan
- Create an App Service
- Configure certificates and TLS for an App Service
- Map an existing custom DNS name to an App Service
- Configure backup for an App Service
- Configure networking settings for an App Service
- Configure deployment slots for an App Service

## Implement and manage virtual networking (15–20%)

### Configure and manage virtual networks in Azure

- Create and configure virtual networks and subnets
- Create and configure virtual network peering
- Configure public IP addresses
- Configure user-defined network routes
- Troubleshoot network connectivity

### Configure secure access to virtual networks

- Create and configure network security groups (NSGs) and application security groups (ASGs)
- Evaluate effective security rules in NSGs
- Implement Azure Bastion
- Configure service endpoints for Azure platform as a service (PaaS)
- Configure private endpoints for Azure PaaS

### Configure name resolution and load balancing

- Configure Azure DNS
- Configure an internal or public load balancer
- Troubleshoot load balancing

## Monitor and maintain Azure resources (10–15%)

### Monitor resources in Azure

- Interpret metrics in Azure Monitor
- Configure log settings in Azure Monitor
- Query and analyze logs in Azure Monitor
- Set up alerts, action groups, and alert processing rules in Azure Monitor
- Configure and interpret monitoring of virtual machines, storage accounts, and networks by using Azure Monitor Insights
- Use Azure Network Watcher and Connection Monitor

### Implement backup and recovery

- Create a Recovery Services vault
- Create an Azure Backup vault
- Create and configure backup policy
- Perform backup and restore operations by using Azure Backup
- Configure Azure Site Recovery for Azure resources
- Perform failover to a secondary region by using Azure Site Recovery
- Configure and interpret reports and alerts for backups
