__**ARM Templates**__

1. ***Virtual network with two subnets***: This template creates a virtual network with two subnets, one for the front-end and one for the back-end. This is a fundamental template that can be used in many scenarios. You can customize the IP address ranges, subnets, and other settings according to your needs.

2. ***Azure Web App with a database***: This template creates an Azure Web App and an Azure SQL Database. The Web App is configured to connect to the SQL Database using the connection string provided by the template. You can use this template to quickly deploy a web application that requires a database.

3. ***Azure Load Balancer with multiple VMs***: This template creates an Azure Load Balancer and multiple virtual machines that are configured to use the load balancer. You can customize the VMs' settings, such as the operating system, disk size, and network configuration. The template also creates a virtual network with a subnet for the VMs.

4. ***Azure Kubernetes Service with a deployment***: This template creates an Azure Kubernetes Service cluster and deploys a containerized application to the cluster. You can customize the number of nodes in the cluster, the Kubernetes version, and other settings. The template also creates a virtual network with a subnet for the Kubernetes cluster.

5. ***Azure Key Vault with secrets***: This template creates an Azure Key Vault and stores secrets in it. You can use this template to manage secrets such as passwords, API keys, and certificates in a centralized location. The template also creates an access policy that allows your applications to access the secrets stored in the Key Vault.

***Bonus Content***

****StaticApp_NodeJs.json****

To use this template, replace the following placeholders with the appropriate values:

- `<username>/<repository>`: The GitHub repository that contains your Node.js web application.
- `<keyVaultName>`: The name of the Azure Key Vault where you want to store the API credentials.
- `<apiKeyName>`: The name of the API key that you want to store in Azure Key Vault.
- `<yyyy-dd-mm>`: Dates need updating.
