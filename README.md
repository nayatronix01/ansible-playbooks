# ansible-playbooks


# AKS create

Login into Azure  
Create SSH key  
Note down location you want to use 
Search for Azure AD in search box at the top of the page  
Select App Registrations  
Create App Registration and Secret. Copy Secret
Run Azure Powershell Cli  
Check AKS version - az aks get-versions --location <location. --subscription <mysubscriptionid>  
Copy azure_create_aks.yml to Powershell cli  
Run ansible-playbook azure_create_aks.yml and fill in parameters 

To connect to AKS:  
In the search box at the top of the Azure portal page, enter you AKS cluster name  
At the top of the AKS cluster page, click on Connect
Follow instructions on the right of page to connect to AKE

  
    
# AKS delete
Login into Azure  
Run Azure Powershell Cli 
Run ansible-playbook azure_create_aks.yml and fill in parameters  


NOTE: SSH Public key and App Registrations Client Secret will not be displayed when entered.


# Wordpress HA

Login into Azure  

