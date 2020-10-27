Backup Azure V2 VMs to a Recovery Services vault using Azure Automation
=======================================================================

            

 

 

This runbook backs up Azure V2 virtual machines to a Recovery Services Vault. It accepts as optional input parameters the resource group of virtual machines, the specific VM in a resource group, a backup policy, and optional subscription ID. If none of the
 optional parameters are set, all V2 virtual machines in the default subscription will be backed up with the default backup policy.


It requires that a Recovery Services vault already be created created and the name of the vault passed in as a parameter to the runbook.


![Image](https://github.com/azureautomation/backup-azure-v2-vms-to-a-recovery-services-vault-using-azure-automation/raw/master/backupvm.png)


        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
