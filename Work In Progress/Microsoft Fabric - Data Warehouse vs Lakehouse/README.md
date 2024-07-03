# Microsoft Fabric: Data Warehouse vs. Lakehouse

## Abstract
Microsoft Fabric is a data analytics offering from Microsoft that combines ETL, data warehousing, data lakes, Spark, Power BI, and more into a single connected platform. The challenge with so many options is choosing the right tool for the job. In this session, you will learn about the similarities and differences between Fabric Data Warehouse and Fabric Lakehouse so you can make an informed decision about architecting your next analytics solution. We will talk about data loading, data engineering/cleansing, reporting, and integration with the broader Microsoft platform.

**Session level:** Intermediate - L200  
**Session length:** 60 minutes

|Time       |Topic                                      |
|---        |---                                        |
|10 min     |Data Lakes, Lakehouses, Warehouses         |
|5 min      |What is Fabric?                            |
|15 min     |Using the Fabric Lakehouse                 |
|15 min     |Using the Fabric Data Warehouse            |
|5 min      | Combining Fabric Lakehouse and Warehouse  |
|10 min     | Questions                                 |

## Before you begin
1. Ensure the Demo Hub has been created.

## Data Lakes, Lakehouses, Warehouses
Items here. 

## What is Fabric?
Items here.

## 	Using the Fabric Lakehouse
**Build Bronze**  
1. **Show** Pipeline: Load files section
   - **Name:** PL_Lakehouse_Files_FactSales
   - **Data Source:** Azure Data Lake Sotrage
   - **Data Source Location:** sampledata/Wide World Importers DW/Clean/Parquet/Fact_Sale.parquet
   - **Destination:** Files
   - **Path:** Bronze/Sales_Invoices
   - **File Format:** Parquet
1. **Build** Shortcut for the Application_Cities data:
   - **Source:** Azure Data Lake Storage
   - **Location:** sampledata/bronze/Application_Cities
   - **Shortcut Name:** cities

**Build Silver**  
Something.

**Highlights**  
1. Load data with a pipeline (or Dataflow Gen2)
1. Transform data with a notebook (or Dataflow Gen2)
1. Analyze with T-SQL or Spark

## Using the Fabric Data Warehouse
Items here.

## Combining Fabric Lakehouse and Warehouse
Items here.

## Cleaning up
Items here.