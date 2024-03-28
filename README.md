## End-to-End Data Solution Development

The use case for this project is building an end to end solution by ingesting the tables from on-premise SQL Server database using Azure Data Factory and then store the data in Azure Data Lake. Next, Azure databricks is used to transform the Raw data to the cleanest form of data. After that, I used Azure Synapse Analytics to load the clean data and finally used Microsoft Power BI to integrate with Azure synapse analytics to build an interactive dashboard. Also, I am using Azure Active Directory (AAD) and Azure Key Vault for the monitoring and governance purpose.

The tools that are covered in this project are:

1. Azure Data Factory
2. Azure Data Lake Storage Gen2
3. Azure Databricks
4. Azure Synapse Analytics
5. Azure Key vault
6. Azure Active Directory (AAD) and
7. Microsoft Power BI

AdventureWorks sample databases from Microsoft:
https://learn.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver16&tabs=ssms
