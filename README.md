# AZ-104-Study-Notes
Microsoft AZ-104: Azure Administrator Associate Study Notes

# Disclaimer
Do not rely on these notes to pass the exam.

## Skills measured as of April 27, 2023

### Audience profile

Candidates for this exam should have subject matter expertise in implementing, managing, and monitoring an organization’s Microsoft Azure environment, including virtual networks, storage, compute, identity, security, and governance.

An Azure administrator often serves as part of a larger team dedicated to implementing an organization's cloud infrastructure. Azure administrators also coordinate with other roles to deliver Azure networking, security, database, application development, and DevOps solutions.

Candidates for this exam should be familiar with operating systems, networking, servers, and virtualization. In addition, professionals in this role should have experience using PowerShell, Azure CLI, the Azure portal, Azure Resource Manager templates (ARM templates), and Microsoft Azure Active Directory (Azure AD), part of Microsoft Entra.

---

# Exam Objectives

## Manage Azure identities and governance (15–20%)

### Manage Azure AD objects

- Create users and groups
- Manage licenses in Azure AD
- Create administrative units
- Manage user and group properties
- Manage device settings and device identity
- Perform bulk updates
- Manage guest accounts
- Configure self-service password reset

### Manage access control

- Create custom role-based access control (RBAC) and Azure AD roles
- Provide access to Azure resources by assigning roles at different scopes
- Interpret access assignments

### Manage Azure subscriptions and governance

- Configure and manage Azure Policy
- Configure resource locks
- Apply and manage tags on resources
- Manage resource groups
- Manage subscriptions
- Manage costs by using alerts, budgets, and recommendations
- Configure management groups


## Implement and manage storage (15–20%)

### Configure access to storage

- Configure network access to storage accounts
- Create and configure storage accounts
- Generate shared access signature tokens
- Configure stored access policies
- Manage access keys
- Configure Azure AD authentication for a storage account
- Configure storage encryption

### Manage data in Azure storage accounts

- Create import and export jobs
- Manage data by using Azure Storage Explorer and AzCopy
- Implement Azure Storage redundancy
- Configure object replication

### Configure Azure Files and Azure Blob Storage

- Create an Azure file share
- Configure Azure Blob Storage
- Configure storage tiers
- Configure blob lifecycle management


## Deploy and manage Azure compute resources (20–25%)

### Automate deployment of resources by using templates

- Modify an ARM template
- Deploy a template
- Save a deployment as an ARM template
- Deploy virtual machine (VM) extensions

### Create and configure VMs

- Create a VM
- Manage images by using the Azure Compute Gallery
- Configure Azure Disk Encryption
- Move VMs from one resource group to another
- Manage VM sizes
- Add data disks
- Configure VM network settings
- Configure VM availability options
- Deploy and configure VM scale sets

### Create and configure containers

- Configure sizing and scaling for Azure Container Instances
- Configure container groups for Azure Container Instances
- Create and configure Azure Container Apps
- Configure storage for Azure Kubernetes Service (AKS)
- Configure scaling for AKS
- Configure network connections for AKS
- Upgrade an AKS cluster

### Create and configure an Azure App Service

- Create an App Service plan
- Configure scaling settings in an App Service plan
- Create an App Service
- Secure an App Service
- Configure custom domain names
- Configure backup for an App Service
- Configure networking settings
- Configure deployment settings


## Configure and manage virtual networking (20–25%)

### Configure virtual networks

- Create and configure virtual networks and subnets
- Create and configure virtual network peering
- Configure private and public IP addresses
- Configure user-defined network routes
- Configure Azure DNS

### Configure secure access to virtual networks

- Create and configure network security groups (NSGs) and application security groups (ASGs)
- Evaluate effective security rules
- Implement Azure Bastion
- Configure service endpoints
- Configure private endpoints

### Configure load balancing

- Configure Azure Application Gateway
- Configure an internal or public load balancer
- Troubleshoot load balancing

### Monitor virtual networking

- Monitor on-premises connectivity
- Configure and use Azure Monitor for networks
- Use Azure Network Watcher
- Troubleshoot external networking
- Troubleshoot virtual network connectivity

## Monitor and maintain Azure resources (10–15%)

### Monitor resources by using Azure Monitor

- Configure and interpret metrics
- Configure Azure Monitor Logs
- Query and analyze logs
- Set up alerts and actions
- Configure monitoring of VMs, storage accounts, and networks by using VM insights

### Implement backup and recovery

- Create an Azure Recovery Services vault
- Create an Azure Backup vault
- Create and configure backup policy
- Perform backup and restore operations by using Azure Backup
- Configure Azure Site Recovery for Azure resources
- Perform failover to a secondary region by using Azure Site Recovery
- Configure and review backup reports
