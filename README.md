Integrating Azure Automation with Event grid
============================================

            




This sample Automation runbook integrates with Azure event grid subscriptions to get notified when a write command is performed against an Azure VM. The runbook adds a cost tag to the VM if it doesn't exist. It also sends an optional notification to a
 Microsoft Teams channel indicating that a new VM has been created and that it is set up for automatic shutdown / start up tags.


 





        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
