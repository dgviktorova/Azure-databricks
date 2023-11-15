# Azure-databricks


![Azure-databricks](https://github.com/dianaviktorova/Azure-databricks/assets/145328524/5d26be47-8bb7-43e0-8ee4-6735544e003c)


Basic configuration for the project with resources below included.

1.Azure Virtual Network (VNet):
  - Virtual Network will be created to securely connect on-premise and Azure resources. Azure ExpressRoute or VPN Gateway can be used for secure communication between on-premise and Azure.
2. Azure Blob Storage:
  - Azure Blob Storage will be used as a central data lake for storing both - on-premise and cloud data. All the data will be organized in containers and folders.
3. Azure Databricks:
  - An Azure Databricks workspace will be provisioned to provide an integrated platform for data engineering and data science tasks. And the Databricks workspace will be connected to the Azure Blob Storage for data storage.
  - Clusters within Databricks for parallel processing and scalable computing resources will be created.
4. Azure Data Factory:
  - Azure Data Factory will be used to orchestrate data workflows between on-premise and Azure Blob Storage.
  - It will be created pipelines to move, transform, and load data from on-premise storage to Azure Blob Storage and vice versa.
5. Azure Active Directory (AAD):
  - Azure Databricks will be integrated with Azure Active Directory for authentication and authorization. This ensures that only authorized users can access the Databricks workspace.
6. Azure Key Vault:
  - Sensitive information such as credentials, secrets, and encryption keys will be stored in Azure Key Vault for enhanced security.
7. Monitoring and Logging:
  - Azure Monitor and Azure Log Analytics will be implemented for monitoring the performance and health of the Azure Databricks workspace.
  - Azure Databricks workspace logs wiil be utilized for auditing and troubleshooting.
8. Network Security:
  - Network Security Groups (NSGs) will be configured to control inbound and outbound traffic to and from the Databricks workspace. Ports 443 (HTTPS) and 22 (SSH) will be used
9. Azure Policy and Compliance:
  - Azure Policy will be implemented to enforce organizational standards and compliance requirements across the Azure resources.
10. Collaboration Tools:
  - GitHub will be integrated as a collaboration tool to manage code and collaboration among different teams.
11. Cost Management:
  - Azure Cost Management and Billing will be leveraged to monitor and optimize resource usage, ensuring cost-effectiveness.

    
