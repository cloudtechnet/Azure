# To Chech Azure CLI is installed or not and Check which Version of Azure CLI is installed ?
az version

# Create resource group
az group create --name rgtest01 --location 'Central US'

# Create Storage Account in specific resource group using ARM JSON template
az deployment group create --resource-group rgtest01 --template-file storage-account.json
