## Retail Sales Analytics Platform 

#### Medallion Architecture Implementation in Microsoft Fabric

#### Project Overview
I built this project to understand the concept of the Medallion Architecture using Microsoft Fabric. This platform transforms raw retail data into a clean Star Schema, focusing on the core steps of data engineering: ingestion, cleaning, and modeling.

#### What I Did
•	Bronze Layer: Ingested the raw CSV sales data into the Lakehouse.
•	Silver Layer: Cleaned the data using PySpark (removing duplicates, fixing date formats, and casting data types).
•	Gold Layer: Organized the data into a Star Schema with Fact and Dimension tables for better reporting.
•	Validation: Checked the final tables to ensure data integrity and accuracy.

#### Architecture Diagram
<img src="https://github.com/Tungana-Bhavya/MICROSOFT_FABRIC/blob/main/PROJECTS/RETAIL-SALES-ANALYTICS-PLATFORM/IMAGES/MEDALLION_ARCHITECTURE.png" alt="Image" width="700" height="720">

#### Technical Stack
•	Platform: Microsoft Fabric (Lakehouse)
•	Processing: PySpark (Notebooks)
•	Storage: Delta Lake
•	Modeling: Star Schema (Fact/Dimension)

#### Requirements
•	Microsoft Fabric workspace (Trial or Premium).
•	Lakehouse with Schema Support enabled.
•	Spark compute to run the notebooks.

#### Future Goals
•	Handle more data: Work with multiple files types and much larger data volumes.
•	Use SQL: Build SQL views to make it easier to query the data.
•	Automation: Use Data Factory pipelines to run the notebooks automatically.
•	Add Logging: Create log files to track errors and pipeline success.
•	Real-time: Explore Eventhouses and Eventstreams for live data.

#### Learning Resources
[Microsoft Medallion Architecture](https://learn.microsoft.com/en-us/fabric/onelake/onelake-medallion-lakehouse-architecture)
[Microsoft Fabric Documentation](https://learn.microsoft.com/en-us/fabric/)
[Apache Spark](https://learn.microsoft.com/en-us/training/modules/use-apache-spark-work-files-lakehouse/?source=recommendations)

