***ARM Templates README***

This repository contains a collection of Azure Resource Manager (ARM) templates that can be used to deploy various Azure resources.

**Templates**

`Templates/Apps/webAppCluster.json`
- This template deploys an Azure Web App in a cluster configuration. The template provisions the necessary resources to create a scalable and highly available web app cluster.


`Templates/Apps/webAppNodeJs.json`
- This template deploys an Azure Web App for a Node.js web application. The template provisions the necessary resources to create a scalable and highly available web app that can run Node.js applications.


`Templates/Apps/webAppWithDatabase.json`
- This template deploys an Azure Web App with an Azure SQL Database backend. The template provisions the necessary resources to create a web app that can store and retrieve data from an Azure SQL Database.


`Templates/Databases/sqlDatabase.json`
- This template deploys an Azure SQL Database. The template provisions the necessary resources to create a SQL Database with a specified name, collation, and edition.


`Templates/Networks/networkWithTwoSubnets.json`
- This template deploys an Azure Virtual Network with two subnets. The template provisions the necessary resources to create a virtual network with two subnets, one for web traffic and one for database traffic.


`Templates/Networks/virtualNetwork.json`
- This template deploys an Azure Virtual Network. The template provisions the necessary resources to create a virtual network with a specified name, address space, and subnet.

`Templates/Security/azureSecurityCentre.json`
- This template deploys Azure Security Center. The template provisions the necessary resources to create a security solution for your Azure environment, including security policies, threat detection, and vulnerability assessments.


`Templates/Security/keyVault.json`
- This template deploys an Azure Key Vault. The template provisions the necessary resources to create a secure store for keys, secrets, and certificates.


`Templates/Storage/backupVault.json`
- This template deploys an Azure Backup vault. The template provisions the necessary resources to create a backup solution for your Azure resources, including backup policies, storage accounts, and retention settings.


`Templates/Storage/storageAccount.json`
- This template deploys an Azure Storage account. The template provisions the necessary resources to create a storage account with a specified name, replication type, and access tier.


**Contributing**
Contributions to this repository are welcome! If you find a bug, have a suggestion, or want to contribute an ARM template, please open an issue or pull request.


**License**
This repository is licensed under the MIT License. See the LICENSE file for details.
