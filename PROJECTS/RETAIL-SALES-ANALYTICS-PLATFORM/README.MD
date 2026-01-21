# Retail Sales Analytics Platform 

### Medallion Architecture Implementation in Microsoft Fabric

### Project Overview
I **built** this project to understand the concept of the **Medallion Architecture** using **Microsoft Fabric.** This platform transforms raw retail data into a clean Star Schema, focusing on the core steps of data engineering: ingestion, cleaning, and modeling.

### What I Did
•	**Bronze Layer:** **Ingested** the raw CSV sales data into the Lakehouse.</br>
•	**Silver Layer:** **Cleaned** the data using **PySpark** (removing duplicates, fixing date formats, and casting data types).</br>
•	**Gold Layer:** **Organized** the data into a Star Schema with Fact and Dimension tables for better reporting.</br>
•	**Validation:** **Checked** the final tables to ensure data integrity and accuracy.</br>

### Architecture Diagram
<img src="https://github.com/Tungana-Bhavya/MICROSOFT_FABRIC/blob/main/PROJECTS/RETAIL-SALES-ANALYTICS-PLATFORM/IMAGES/MEDALLION_ARCHITECTURE.png" alt="Image" width="800" height="820">

### Technical Stack
•	**Platform:** Microsoft Fabric (Lakehouse)</br>
•	**Processing:** PySpark (Notebooks)</br>
•	**Storage:** Delta Lake</br>
•	**Modeling:** Star Schema (Fact/Dimension)</br>

### Requirements
•	Microsoft Fabric workspace (Trial or Premium).</br>
•	Lakehouse with Schema Support enabled.</br>
•	Spark compute to run the notebooks.</br>

### Project Structure
•	NOTEBOOK: Contains PySpark logic with visible execution outputs and data profiles.</br>
•	DATA: Includes the raw source CSV file used for the transformation.</br>
•	IMAGES: Documentation of work including Lakehouse explorer, table schemas, and many more.</br>

### Future Goals
•	**Handle more data:** Work with multiple files types and much larger data volumes.</br>
•	**Use SQL:** Build **SQL** views to make it easier to query the data.</br>
•	**Automation:** Use Data Factory pipelines to run the notebooks automatically.</br>
•	**Add Logging:** Create log files to track errors and pipeline success.</br>
•	**Real-time:** Explore **Eventhouses** and **Eventstreams** for real time data.</br>

### Learning Resources
[Microsoft Medallion Architecture](https://learn.microsoft.com/en-us/fabric/onelake/onelake-medallion-lakehouse-architecture)

[Microsoft Fabric Documentation](https://learn.microsoft.com/en-us/fabric/)

[Apache Spark](https://learn.microsoft.com/en-us/training/modules/use-apache-spark-work-files-lakehouse/?source=recommendations)

