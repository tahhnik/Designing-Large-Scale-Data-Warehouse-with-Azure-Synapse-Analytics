![Static Badge](https://img.shields.io/badge/Data%20Warehousing-blue?style=plastic&logoColor=Blue)
![Static Badge](https://img.shields.io/badge/Azure-blue?style=plastic)
![Static Badge](https://img.shields.io/badge/Azure-Synapse_Analytics-blue?style=plastic)
![Static Badge](https://img.shields.io/badge/Data-Analytics-%2397c900?style=plastic)
![Static Badge](https://img.shields.io/badge/Azure-Stream_Analytics-%230273b4?style=plastic)
![Static Badge](https://img.shields.io/badge/Azure-Machine_Learning-%230273b4?style=plastic)
![Static Badge](https://img.shields.io/badge/Web-Application-%238c37db?style=plastic)
![Static Badge](https://img.shields.io/badge/System-Design-%238c37db?style=plastic)
![Static Badge](https://img.shields.io/badge/Function-Apps-%238c37db?style=plastic)



# From Design to Deployment: Data Warehousing with Azure Synapse Analytics 
The repo simulates query load, optimizes performance, and offers practical guidance for building data warehouses with Azure Synapse Analytics. 🚀
The project follows the following architecture,
![Infrastructure Diagram](Assets/working-Animation.gif)

# Directories 📂

1. **data:** The datasets, fact, and dimension tables for the data warehouse
2. **Queries_Part4.sql:** SQL code for querying and analyzing the created data warehouse
3. **setup.json:** ARM (Azure Resource Manager) template. It is a block of code that defines the infrastructure and configuration for the project
4. **setup.ps1:** PowerShell script to provision the Azure Synapse Workspace along with the tables of the data warehouse (configured in setup.sql)
5. **setup.sql:** SQL script for creating the tables of the data warehouse
6. **table_creation_codes.sql:** SQL script to create the fact and dimension tables with dedicated SQL pool

## Prerequisites:
1. An active Azure subscription
2. Knowledge of Azure Data Fundamentals, [Good to begin from here](https://learn.microsoft.com/en-us/training/courses/dp-900t00)

## Getting Started 🚀

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/tahhnik/Designing-Large-Scale-Data-Warehouse-with-Azure-Synapse-Analytics.git

![synapase-ui-shell-gitclone](https://github.com/tahhnik/Designing-Large-Scale-Data-Warehouse-with-Azure-Synapse-Analytics/assets/25973761/6624d5a1-dc98-45a3-b819-63f3344e659e)

2. **Explore the Directories:**
   Navigate into each directory to find detailed automation scripts, SQL codes for queries, and configurations.

3. **Follow the Blog:**
   Implementation details and insights are documented in the associated [series of blog posts in Medium](URL_HERE).
   
      ⚡**If you want to skip the initial processes like data modeling, schema design and directly jump onto building the warehouse on Azure Synapse Analytics, _follow the Blog Three_**,
   
      ⚡**If you want to skip the building warehouse processes on Azure Synapse Analytics and directly jump onto querying the tables with SQL (T-SQL in this context), _follow the Blog Four_**
   



   

  ## **Blog One: _From Design to Deployment: Data Warehousing with Azure Synapse Analytics (Part 1: Architecture)_**
  <img width="1440" alt="Final Draft" src="https://github.com/tahhnik/Designing-Large-Scale-Data-Warehouse-with-Azure-Synapse-Analytics/assets/25973761/a0ef0dbe-8486-40f3-b817-0a4068f5e432">

   **Components:**
   * The architecture of the data warehouse
   * The details of the data pipeline
   * Brief Discussions of the tools and processes used

   
   ## **Blog Two: _From Design to Deployment: Data Warehousing with Azure Synapse Analytics (Part 2: Data Modeling and Schema Design_)**
   <img width="1440" alt="Final Draft (3)" src="https://github.com/tahhnik/Designing-Large-Scale-Data-Warehouse-with-Azure-Synapse-Analytics/assets/25973761/21347ad3-03d5-47de-a624-672ece59e261">
   
   **Components:**
   * The architecture of the data warehouse
   * The details of the data pipeline
   * Brief Discussions of the tools and processes used


   ## **Part Three: _From Design to Deployment: Data Warehousing with Azure Synapse Analytics (Part 3: Design and Creation)_**
   <img width="1440" alt="Final Draft (3)" src="https://github.com/tahhnik/Designing-Large-Scale-Data-Warehouse-with-Azure-Synapse-Analytics/assets/25973761/12131ee8-2585-4080-b3f3-2fa9ed5929f2">

   ## **Part Four: _From Design to Deployment: Data Warehousing with Azure Synapse Analytics (Part 3: Querying the Data Warehouse)_**
   <img width="1440" alt="Final Draft (3)" src="https://github.com/tahhnik/Designing-Large-Scale-Data-Warehouse-with-Azure-Synapse-Analytics/assets/25973761/7ec03419-2e5a-41ea-a72a-796eb0256366">

    
   **Components:**
   * The architecture of the data warehouse
   * The details of the data pipeline
   * Brief Discussions of the tools and processes used

## Tools Explored 🛠️
1. **Azure Synapse Analytics**: Enterprise analytics service for data warehouses and big data systems.
2. **Azure Portal**: Unified console to manage Azure resources.
3. **Azure Stream Analytics**: Real-time stream processing engine.
4. **Azure Machine Learning**: Cloud service for ML project lifecycle.
5. **Azure Data Lake Storage Gen2**: Scalable storage for data lakes.
6. **Power BI**: Business analytics service for data visualization.
7. **Azure Function Apps**: Serverless applications for event-driven scenarios.
8. **Azure Cosmos DB**: Globally distributed, multi-model database.


## Blog Implementation 📝
   To implement this project, follow the step-by-step guide in our detailed [blog post](URL_Here). Learn how each tool plays a crucial role in creating and scaling a data warehouse on Azure.

## Acknowledgments 🙌
   Special thanks to the open-source community and the contributors who make learning and collaboration an incredible journey.

## License 📄
   This project is licensed under the Apache-2.0 license see the [LICENSE](http://www.apache.org/licenses/) file for details.
   
## Connect with Me ⬇️
   [![LinkedIn](https://img.shields.io/badge/Connect%20with%20me%20on-LinkedIn-blue.svg)](https://www.linkedin.com/in/tahnikahmed/)
   [![Twitter](https://img.shields.io/badge/Connect%20with%20me%20on-Twitter/X-blue.svg)](https://twitter.com/TahnikAhmed)
