# ansible-playbookS


# AKS create

Login into Azure  
Create SSH key  
Note down location you want to use 
Create App Registration and Secret  
Run Azure Powershell Cli  
Check AKS version - az aks get-versions --location <location. --subscription <mysubscriptionid>  
Copy azure_create_aks.yml to Powershell cli  
Run ansible-playbook azure_create_aks.yml and fill in parameters 
  
  
    
# AKS delete
Login into Azure  
Run Azure Powershell Cli 
Run ansible-playbook azure_create_aks.yml and fill in parameters  


NOTE: SSH Public key and App Registrations Client Secret will not be displayed when entered.



  
  
