# Azure - Update all disk of all VMs to Premium Disks
Powershell script for Azure Automation that shutdown all VMs of a given Resource Group ann also update all disks of VMs to Stardard HDD disk. Good for shutdown your lab. Choose only your target Resource Group

## Requirements

- Azure Account
- Azure Automation Service with managed identity configured (https://learn.microsoft.com/en-us/azure/automation/quickstarts/enable-managed-identity)


## Recommended Use

If you want to optimize the costs of your demo environment, not only shuttingdown VMs, but also converting all disk to Stardard HDD