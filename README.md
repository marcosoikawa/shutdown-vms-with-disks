# Shutdown VMs and convert disks to Stardard HDD
Powershell script for Azure Automation that shutdown all VMs of a given Resource Group and also update all disks of VMs to Stardard HDD disk. Good for shutdown your lab or dev environment. Choose only your target Resource Group. 
Use in conjunction with the script "Start VMs and convert disks to Premium SSD" (https://github.com/marcosoikawa/start-vms-with-disks)

## Requirements

- Azure Account
- Azure Automation Service with managed identity configured (https://learn.microsoft.com/en-us/azure/automation/quickstarts/enable-managed-identity)


## Recommended Use

If you want to optimize the costs of your demo environment, not only shuttingdown VMs, but also converting all disk to Stardard HDD.
To start VMs, you can use the script "Start VMs and convert disks to Premium SSD" (https://github.com/marcosoikawa/start-vms-with-disks)