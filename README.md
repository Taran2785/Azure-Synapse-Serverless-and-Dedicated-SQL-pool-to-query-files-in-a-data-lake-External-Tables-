# Azure-Synapse-Serverless-and-Dedicated-SQL-pool-to-query-files-in-a-data-lake-(External-Tables)

**Azure Synapse Analytics** provides a cloud platform for all of analytical workloads through support for multiple data storage, processing, and analysis technologies in a single, integrated solution. The integrated design of Azure Synapse Analytics enables organizations to leverage investments and skills in multiple commonly used data technologies, including SQL, Apache Spark, and others; while providing a centrally managed service and a single, consistent user interface.

A Synapse Analytics workspace defines an instance of the Synapse Analytics service in which you can manage the services and data resources needed for your analytics solution. You can create a Synapse Analytics workspace in an Azure subscription interactively by using the Azure portal, or you can automate deployment by using Azure PowerShell, the Azure command-line interface (CLI), or with an Azure Resource Manager or Bicep template.


<img width="400" alt="synapse-studio" src="https://github.com/Taran2785/Azure-Synapse-Serverless-and-Dedicated-SQL-pool-to-query-files-in-a-data-lake-External-Tables-/assets/100719085/ea2ce97c-6332-49d1-a786-3d1b60d94f38">

**Working with files in a data lake**

One of the core resources in a Synapse Analytics workspace is a data lake, in which data files can be stored and processed at scale. A workspace typically has a default data lake, which is implemented as a linked service to an Azure Data Lake Storage Gen2 container. You can add linked services for multiple data lakes that are based on different storage platforms as required.


<img width="400" alt="data-lake-store" src="https://github.com/Taran2785/Azure-Synapse-Serverless-and-Dedicated-SQL-pool-to-query-files-in-a-data-lake-External-Tables-/assets/100719085/ec2dfdcc-4565-4d2b-b08d-0c6aef08a70e">



**Querying and manipulating data with SQL**

Azure Synapse Analytics supports SQL-based data querying and manipulation through two kinds of SQL pool that are based on the SQL Server relational database engine:

A built-in serverless pool that is optimized for using relational SQL semantics to query file-based data in a data lake.

Custom dedicated SQL pools that host relational data warehouses.

<img width="400" alt="synapse-sql" src="https://github.com/Taran2785/Azure-Synapse-Serverless-and-Dedicated-SQL-pool-to-query-files-in-a-data-lake-External-Tables-/assets/100719085/08b27274-bedb-412c-83fd-86fe1a1bbd74">



