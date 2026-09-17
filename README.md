# Banking-Data-Analysis-with-AI-Tools 


### Dashboard Link : 

### Data set: Perplexity, SQL Server Management Studio (SSMS) 

## Problem Statement:

The objective of this project is to analyze banking customer, account, and transaction data to gain meaningful insights into customer behavior, account activity, and financial transactions. The analysis focuses on transforming raw banking data into interactive and informative Power BI dashboards that support data-driven decision-making.

The project involves integrating and analyzing customer information, account details, and transaction records to identify key trends and patterns such as transaction activity, account balances, customer segments, transaction types, and overall financial performance.

The analysis aims to provide stakeholders with a clear view of banking operations, help identify high-value customers and accounts, monitor transaction patterns, and uncover potential areas for improving customer engagement and financial performance. Power BI is used to create interactive visualizations, KPIs, filters, and dashboards that enable users to explore the data and derive actionable business insights.

### Steps followed 

- Step 1: Generated and structured a banking dataset using Perplexity as the data source for a Power BI analytics project.
- Step 2: Using SQL Server Management Studio (SSMS), created a new database named Power_BI2. Copied and executed the SQL code generated with the help of Perplexity to create the required database structure and populate the tables with banking data.

  <img width="440" height="139" alt="Image" src="https://github.com/user-attachments/assets/dc27fe37-473f-4d6c-9bc9-cfcc28c19c1c" />

- Step 3: First, executed the SQL query to create and generate the Customer table, as shown below.


 <img width="958" height="275" alt="Image" src="https://github.com/user-attachments/assets/5e1c668f-04c8-4133-ad59-b4e39ca3c1e0" />

- Step 4: Next, executed the SQL query to create and populate the Accounts table. Finally, executed the SQL query to create and populate the Transactions table, completing the database setup.
  

<img width="705" height="164" alt="Image" src="https://github.com/user-attachments/assets/221b0077-e633-4bf1-b7be-bf347c6bb835" />



<img width="646" height="313" alt="Image" src="https://github.com/user-attachments/assets/b1f140ab-aeb8-4f5c-bad8-822af171ada6" />


- Step 5: Using the New Query option in SSMS, used the INSERT INTO statement to add customer data to the Customer table and account data to the Accounts table.

<img width="771" height="182" alt="Image" src="https://github.com/user-attachments/assets/ac89b947-fbb1-4cb4-8f3c-114cf8a7a3ec" />

<img width="881" height="165" alt="Image" src="https://github.com/user-attachments/assets/65c2e40f-d2d1-4496-98bf-1f45ca76ee98" />


- Step 6: Similarly, created the Transactions table and used the INSERT INTO statement to insert the required transaction data. After executing the query, verified that the table was successfully created and populated with 10,000 transaction records.



<img width="1071" height="541" alt="Image" src="https://github.com/user-attachments/assets/0648f75a-a2f0-4899-983e-daf6f19d63e0" />


<img width="934" height="487" alt="Image" src="https://github.com/user-attachments/assets/361e9597-5bbd-411b-b228-518998d77115" />

<img width="1084" height="589" alt="Image" src="https://github.com/user-attachments/assets/3c6ec599-4775-4077-b3c5-9a55db0f58d8" />


- Step 7: Identified inconsistencies in the data formats across the Customer, Account, and Transaction tables.
  
- Step 8: Used Perplexity to refine the SQL query and update the date column format.

  <img width="749" height="380" alt="Image" src="https://github.com/user-attachments/assets/8d5e7460-49ba-4900-8ecc-d39461da104b" />
  
  
- Step 9: Copied and executed the updated SQL query from Perplexity to update the date column in the Account table.

  <img width="728" height="332" alt="Image" src="https://github.com/user-attachments/assets/d7d6c722-7590-4d8d-bd03-ea0d0e3ae0a7" />
  
- Step 10: As shown in the image below, the date column has been successfully updated in the Account table.

  <img width="607" height="317" alt="Image" src="https://github.com/user-attachments/assets/44be5475-c697-4145-83d8-23ba6a5b1ffc" />

  
- Step 11: Similarly, applied the updated SQL query to modify the date column in the Customer table, as illustrated below.

  <img width="800" height="496" alt="Image" src="https://github.com/user-attachments/assets/f79afd66-1607-463c-aeec-b5801eaf108e" />

  
- Step 12: As demonstrated below, the date column in the Customer table has been successfully updated.

<img width="800" height="496" alt="Image" src="https://github.com/user-attachments/assets/f79afd66-1607-463c-aeec-b5801eaf108e" />
  
- Step 13: As shown below, the date column has been successfully updated.


<img width="728" height="450" alt="Image" src="https://github.com/user-attachments/assets/7e6a5697-45bb-4775-a7fb-a70e28bb4f6a" />


- Step 14:  As demonstrated below, the date column in the Transactions table has been successfully updated.
<img width="1094" height="553" alt="Image" src="https://github.com/user-attachments/assets/47b2223d-72ab-4c18-b26f-c309e4c5df63" />

<img width="1033" height="589" alt="Image" src="https://github.com/user-attachments/assets/dc06c939-bf56-404c-808b-8d4a613eea20" />
  
- Step 15: To combine the three tables into a single dataset, an SQL query was obtained using Perplexity. Before creating the query, all column names from the Transaction table were retrieved using SQL to ensure that the required fields were included.

<img width="1085" height="556" alt="Image" src="https://github.com/user-attachments/assets/fa6ca603-72eb-43f1-b665-145715322fdd" />
  
- Step 16: The same process was followed to retrieve the column names from the Customer and Account tables, as shown below.

  

<img width="747" height="212" alt="Image" src="https://github.com/user-attachments/assets/02b611a1-3f34-453b-828b-6be327462c80" />



<img width="664" height="285" alt="Image" src="https://github.com/user-attachments/assets/2c5d06fc-4ccd-45c0-a03b-14b5bf9d01be" />


- Step 17: The SQL query generated with the assistance of Perplexity was executed in SQL Server Management Studio (SSMS) to merge the Customer, Account, and Transaction tables into a single table. The execution successfully impacted 10,000 records, confirming that the three tables were combined successfully.

<img width="447" height="332" alt="Image" src="https://github.com/user-attachments/assets/72ffb3dd-7eea-4a16-8b2e-d8865fb5ca77" />


<img width="1089" height="589" alt="Image" src="https://github.com/user-attachments/assets/273210a7-3252-404c-8008-1e6de286fb31" />

- Step 18: Successfully imported the consolidated data into Power BI Desktop for further transformation, analysis, and visualization.
- Step 19: Connected Power BI Desktop to SQL Server as the data source and successfully imported the consolidated dataset for analysis
- Step 20: Copied the final SQL query into Perplexity and used it as a reference to identify relevant KPIs and develop the required DAX measures for the Power BI report.
- Step 21:Loaded the data into Power BI Desktop and performed data transformation and cleaning to ensure the dataset was accurate, consistent, and ready for analysis.
- Step 22: Using Power Query, updated the data types of the relevant columns. 
- Step 23: An error occurred while changing the data type of certain date columns. To resolve the issue, the Using Locale option in Power Query was used to correctly interpret the date values and apply the English (United States) date format. The same process was followed for all other date columns to successfully convert the data type from Text to Date.




