# iPhone Sales Comparison Analysis
Conduct a comparison analysis of iPhone 15 sales and iPhone 14 sales.
## Objective

- **Project objective:**
  The project objective is to compare the iPhone 15 and iPhone 14 sales performance comprehensively. This involves analyzing sales data from September, October, and November of 2022 for iPhone14   and from the same months in 2023 for iPhone15. The goal is to calculate and report both the absolute and percentage variances in sales between these two models, providing insights into the       differences in sales performance across various countries.

- **Datasets:**
  The following datasets are used for this analysis:

  **1.** fact_sales_iPhone14.csv
  
  **2.** fact_sales_iPhone15.csv
  
  **3.** dim_stores.csv
  
## Information about Tables

  - **dim_stores**
    
    **1.** store_id: Unique identifier for each store.
    
    **2.** country_name: Name of the country where the store is located.

  - **fact_sales_iPhone14** This table contains aggregated sales data for iPhone 14 in September, October, and November of 2022.
    
     **1.** month: This column represents month and year in the format 'Mmm_yy'.
    
     **2.** store_id: Unique identifier for each store.
    
     **3.** iphone14: This column represents the actual sales data for a specific store in a given month for iPhone 14.

  - **fact_sales_iPhone15** This table contains aggregated sales data for iPhone 15 in September, October, and November of 2023.

      **1.** month: This column represents month and year in the format 'Mmm_yy'.

      **2.** store_id: Unique identifier for each store.

      **3.** iphone15: This column represents the actual sales data for a specific store in a given month for iPhone 15.

## Information about Tables

 - **The following tasks outline the workflow for this analysis:**

      **1.** Review the Data: Analyze the datasets fact_sales_iPhone14 and fact_sales_iPhone15.
      
      **2.** Metrics to Compare: Compare iPhone 14 sales and iPhone 15 sales.

      **3.** Calculate Absolute Variance: Calculate the absolute difference between the iPhone 15 sales and iPhone 14 sales:

      **4.** Calculate Percentage Variance: Calculate the variance in percentage between iPhone 15 sales and iPhone 14 sales

      **5.** Report Generation: Provide a detailed report of the differences in sales numbers between iPhone 15 and iPhone 14 across the top 10 countries.


