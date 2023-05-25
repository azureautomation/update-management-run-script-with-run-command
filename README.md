Update Management - Run Script with Run Command
===============================================

            
This script is intended to be run as a part of Update Management Pre/Post scripts.

 

It will run a script locally on an Azure VM using the
[Run Command](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/run-command) functionality. It requires the module 'ThreadJob' from the PowerShell Gallery.

UpdateManagement-RunCommand.ps1 uses Az cmdlets and System Managed Identity.

This differs from the [Run Script Locally](https://gallery.technet.microsoft.com/Update-Management-Run-6949cc44) which can act on on-prem machines, but requires a hybrid worker. 

Change the $scriptBlock parameter to be the script you wish to run locally.


 



        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
