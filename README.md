# Data Analytics Project: Customer Behavior Analysis  
**A comprehensive end-to-end analysis uncovering customer shopping behavior using transactional data from 3,900 purchases across various product categories to drive data-informed decision making.**

### Overview  
This project demonstrates a full data lifecycle: from raw data ingestion and cleaning in **Python** to advanced querying in **SQL** and interactive visualization in **Power BI**. The final insights were distilled into a professional report and an AI-enhanced presentation for stakeholder review.

### Tools & Technologies  
**Languages**: Python (Pandas, NumPy, Matplotlib/Seaborn)  
**Database**: PostgreSQL / MySQL / SQL Server  
**Visualization**: Power BI  
**Reporting**: Gamma AI (Presentation), Microsoft Word/PDF (Technical Report)  

### Project Steps  
1. Data Cleaning & EDA (Python)   
Performed initial data profiling to handle missing values, duplicates, and outliers.
* Identified and imputed null values in the review rating field.
* Conducted Exploratory Data Analysis (EDA) for summary statistics from the products and customers.
2. SQL Analysis  
The cleaned data was migrated to a relational database. I executed complex queries to answer business questions, such as:
* Trend Analysis: Measuring the data across all purchases.
* Segmentation: Categorizing users based on age, subscription status, and gender.
* Performance: Identifying the top 5 performing products.  
3. Power BI Dashboard  
Built an interactive dashboard to visualize the SQL-derived insights. Key features include:
* DAX Measures: Created custom measures for revenue based on different categories.
* Dynamic Filters: Users can slice data by Subscription Status, Gender, and Category.
### Key Results & Insights
* Insight 1: Discovered an average review rating of 3.75 throughout the products.
* Insight 2: Identified percentage of subscribed customers, which could be improved by advertising towards the repeat customers.
* Insight 3: Uncovered the distinctions between purchases from different age groups, emphasizing the ability to promote towards young adults.
### How to Run  
1. Clone the repo: git clone https://github.com/parbole1/customer_behavior_analysis.git
2. Python: Open the Customer_Shopping_Behavior_Analysis.ipynb notebook.
3. SQL: Import the customer_behavior_queries.sql file into your local database instance to view the queries.
4. Power BI: Open the customer_behavior_dashboard.pbix file to interact with the dashboard.
5. Presentation: View the Gamma-generated slides via the link provided in the reports/folder.
