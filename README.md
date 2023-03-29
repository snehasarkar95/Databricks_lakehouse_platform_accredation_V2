# Databricks lakehouse platform accredation V2 Questions

Fundamentals of the Databricks Lakehouse Platform Accreditation - v2

1) Which of the following architecture benefits is provided directly by the Databricks Lakehouse Platform? Select three responses.

- [ ] Scalable, redundant cloud-based data storage
- [ ] Efficient on-premises optimized hardware
- [ ] Built on open source and open standards
- [ ] Unified security and governance approach for all data assets
- [ ] Available on and across multiple clouds


2) A data architect is evaluating data warehousing solutions for their organization to use. As a part of this, the architect is considering the Databricks Lakehouse Platform.
Which of the following is a benefit of using the Databricks Lakehouse Platform for warehousing? Select four responses.

- [ ] Best available price/performance
- [ ] A rich ecosystem of business intelligence (BI) integrations
- [ ] Engineering capabilities supporting warehouse source data
- [ ] Built-in governance for single-source-of-truth data
- [ ] Local development software to integrate with other capabilities

3) One of the foundational technologies provided by the Databricks Lakehouse Platform is an open-source, file-based storage format that provides a number of benefits. These benefits include ACID transaction guarantees, scalable data and metadata handling, audit history and time travel, table schema enforcement and schema evolution, support for deletes/updates/merges, and unified streaming and batch data processing.
Which of the following technologies is being described in the above statement? Select one response.

- [ ] MLflow
- [ ] Apache Spark
- [ ] Photon
- [ ] Unity Catalog
- [ ] Delta Lake

4) Which of the following is a common problem within a data lake architecture that can be easily solved by using the Databricks Lakehouse Platform? Select three responses.

- [ ] Lack of ACID transaction support
- [ ] Ineffective partitioning
- [ ] Inability to use open-source data formats
- [ ] Lack of cloud service integrations
- [ ] Too many small files

5) Which of the following describes the motivation for the creation of the data lakehouse? Select one response.

- [ ] Organizations needed a reliable data management system with transactional guarantees for their structured data.
- [ ] Organizations needed to reduce the costs of storing their open-format data files in the cloud.
- [ ] Organizations needed a single, flexible, high-performance system to support data, analytics, and machine learning workloads
- [ ] Organizations needed a way to scale their data lake workloads without investing in additional on-premises hardware.
- [ ] Organizations needed to be able to develop increasingly complex machine learning workloads using a simple, SQL-based solution.

6) Data sharing has traditionally been performed by proprietary vendor solutions, SSH File Transfer Protocol (SFTP), or cloud-specific solutions. However, each of these sharing tools and solutions comes with its own set of limitations. As a result, Databricks helped to develop the solution, Delta Sharing.
Which of the following describes Delta Sharing as a solution for data sharing? Select one response.

- [ ] Delta Sharing is a multicloud, open-source solution for distributing data across a number of compute resources for efficient data shuffling.
- [ ] Delta Sharing is a multicloud, open-source solution to share data between Databricks workspaces within a single Databricks account.
- [ ] Delta Sharing is a multicloud, proprietary solution for efficiently copying and transferring data from the lakehouse to any external system.
- [ ] Delta Sharing is a multicloud, proprietary solution to securely and efficiently share data while maintaining control of the source data.
- [ ] Delta Sharing is a multicloud, open-source solution to securely and efficiently share live data from the lakehouse to any external system.

7) Which of the following describes what challenges a data organization would likely face when migrating from a data warehouse to a data lake? Select two responses.

- [ ] There are increased cloud storage costs in a data lake.
- [ ] There are increased security and privacy concerns in a data lake.
- [ ] There are increased data reliability issues in a data lake.
- [ ] There are increased data quality guarantees in a data lake.
- [ ] There are increased performance speeds in a data lake.

8) Which of the following is a benefit of the Databricks Lakehouse Platform being designed to support all data and artificial intelligence (AI) workloads? Select four responses.

- [ ] Data analysts, data engineers, and data scientists can easily collaborate within a single platform.
- [ ] Analysts can easily integrate their favorite business intelligence (BI) tools for further analysis.
- [ ] There is increased need for multiple, specialist platform administrators to maintain each component of the unified platform.
- [ ] Data workloads can be automatically scaled when needed.
- [ ] Data teams can all utilize secure data from a single source to deliver reliable, consistent results across workloads at scale.

9) Many organizations use a variety of open-source and proprietary tools for data orchestration, but these tools often have their own limitations. To address the orchestration needs of these organizations, Databricks developed Databricks Workflows.
Which of the following is a benefit of using Databricks Workflows for orchestration purposes? Select two responses.
 
- [ ] Databricks Workflows provides Git-backed version control capabilities to notebooks
- [ ] Databricks Workflows supports automating workloads as long as they are not in notebooks
- [ ] Databricks Workflows supports tasks for data ingestion, data engineering, machine learning, and business intelligence (BI)
- [ ] Databricks Workflows provides multiple-task workflow functionality only for Delta Live Tables workloads
- [ ] Databricks Workflows supports workloads across multiple cloud service providers and tools

10) It can be challenging for a data lakehouse to provide both performance and scalability for all of its query-based workloads to the standards of a data warehouse and a data lake. As a result, Databricks has introduced a technology built atop Apache Spark to further speed up and scale these varied workloads.
Which of the following technologies is being described in the above statement? Select one response.

- [ ] Unity Catalog
- [ ] Delta Lake
- [ ] Photon
- [ ] AutoML

11) Which of the following correctly describes how a specific capability of the Databricks Lakehouse Platform supports a data streaming pattern? Select three responses.

- [ ] Databricks Workflows automatically passes data from task to task in regular microbatches.
- [ ] Structured Streaming enables stream-based machine learning inference.
- [ ] Auto Loader continuously and incrementally ingests streaming data.
- [ ] Delta Live Tables processes ETL pipelines on streaming data with advanced monitoring mechanisms.
- [ ] MLflow ingests its automatic experiment tracking data into a stream for continuous monitoring.

12) Which of the following is a security feature made available in the Databricks Lakehouse Platform by Unity Catalog? Select two responses.

- [ ] Single-source-of-truth identity management
- [ ] Databricks SQL warehouse access control
- [ ] Workspace-specific identity management
- [ ] Workspace-specific data metastores
- [ ] Fine-grained access control on data objects

13) Data organizations need specialized environments designed specifically for machine learning workloads.
Which of the following is made available by Databricks as part of Databricks Machine Learning to support machine learning workloads? Select four responses.

- [ ] Optimized and preconfigured machine learning frameworks
- [ ] Lakehouse-specific deep learning frameworks
- [ ] Support for distributed model training on big data
- [ ] Built-in real-time model serving
- [ ] Built-in automated machine learning development

14) Which of the following do Databricks SQL users experience when using serverless Databricks SQL warehouses rather than classic Databricks SQL warehouses? Select one response.

- [ ] Increased total cost of use
- [ ] Availability of automatic scaling
- [ ] Expedited environment startup
- [ ] Availability of Photon
- [ ] Performance degradation on long-running queries

15) Which of the following compute resources is available in the Databricks Lakehouse Platform? Select two responses.

- [ ] Serverless Databricks SQL warehouses
- [ ] Classic clusters
- [ ] Local Databricks SQL warehouses
- [ ] Serverless clusters
- [ ] On-premises clusters

16) Which of the following Databricks Lakehouse Platform services or capabilities provides a data warehousing experience to its users? Select one response.

- [ ] Delta Lake
- [ ] Unity Catalog
- [ ] Databricks SQL
- [ ] Data Science and Engineering Workspace
- [ ] Databricks Machine Learning

17) While the Databricks Lakehouse Platform provides support for many types of data, analytics, and machine learning workloads, some organizations prefer to continue using other preferred vendors for use cases like data ingestion, data transformation, business intelligence, and machine learning.

- [ ] Databricks can be integrated directly with a large number of Databricks partners.
- [ ] Databricks cannot be used alongside other big data tools and platforms.
- [ ] Databricks can use cloud service provider capabilities to efficiently share data with other data tools and platforms.
- [ ] Databricks can be used on-premises to allow for secure, in-house integrations.
- [ ] Databricks can be used locally to allow developers to manually integrate with other systems.

18) Unity Catalog offers improved Lakehouse data object governance and organization capabilities for data segregation.
Which of the following is a consequence of using Unity Catalog to manage, organize and segregate data objects? Select one response.

- [ ] Data in tables and views must be stored in external storage locations
- [ ] Complete data object referencing requires three levels
- [ ] Views are made available outside of their schemas (databases)
- [ ] Catalogs exist within schemas (databases)
- [ ] Table metadata is required

19) In the past, a lot of data engineering resources needed to be contributed to the development of tooling and other mechanisms for creating and managing data workloads. In response, Databricks developed and released a declarative ETL framework so data engineers can focus on helping their organizations get value from their data
Which of the following technologies is being described above? Select one response.

- [ ] Databricks SQL Queries
- [ ] Delta Live Tables
- [ ] Databricks Jobs
- [ ] Delta Lake
- [ ] Autologging

20) Which of the following describes how the Databricks Lakehouse Platform makes data governance simpler? Select one response.

- [ ] Unity Catalog provides a different governance solution for each workload.
- [ ] Unity Catalog provides a different governance solution for each major Databricks Lakehouse Platform Service.
- [ ] Unity Catalog provides a different governance solution for each cloud.
- [ ] Unity Catalog provides a single governance solution across workload types and clouds.
- [ ] Unity Catalog provides a single governance solution fully managed by the Databricks team.

21) In which of the following ways do serverless compute resources differ from classic compute resources within the Databricks Lakehouse Platform? Select two responses.

- [ ] They are always running and reserved for a single, specific customer when needed
- [ ] They exist within the customer cloud account
- [ ] They exist within the Databricks cloud account
- [ ] They result in lower costs by not overprovisioning
- [ ] They are located within the cloud

22) Maintaining and improving data quality is a major goal of modern data engineering.
Which of the following contributes directly to high levels of data quality within the Databricks Lakehouse Platform? Select two responses.

- [ ] Simplified machine learning model serving
- [ ] Apache Spark’s data format flexibility
- [ ] Business intelligence (BI) tool integrations
- [ ] Data expectations enforcement
- [ ] Table schema evolution

23) The Databricks Lakehouse Platform architecture consists of a control plane and a data plane.
Which of the following resources exists within the Databricks control plane? Select two responses.

- [ ] Classic compute resources
- [ ] Cloud object storage
- [ ] Serverless compute resources
- [ ] Cluster configurations
- [ ] Notebooks

24) Which of the following lists the relational entities in order from largest (most coarse) to smallest (most granular) within their hierarchy? Select one response.

- [ ] Schema (Database) → Metastore → Catalog → Table
- [ ] Schema (Database) → Catalog → Table → Metastore
- [ ] Metastore → Catalog → Table → Schema (Database)
- [ ] Catalog → Metastore → Schema (Database) → Table
- [ ] Metastore → Catalog → Schema (Database) → Table

25) Which of the following data engineering capabilities simplifies the work of data engineers on the Databricks Lakehouse Platform? Select three responses.

- [ ] SQL and Python development compatibility
- [ ] Flexible machine learning development solutions
- [ ] End-to-end data pipeline visibility
- [ ] Serverless cluster startup times
- [ ] Automatic deployment and data operations
