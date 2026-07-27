Business Intelligence & Purchase Behavior Analysis
📊 Overview-
This project demonstrates an end-to-end Business Intelligence workflow, transforming raw retail customer data into actionable business insights. The analysis covers data preprocessing, exploratory data analysis (EDA), SQL-based business queries, interactive dashboard development, and executive reporting.

The objective is to analyze customer purchasing behavior, identify sales trends, understand customer demographics, and build an interactive dashboard that supports data-driven business decisions.

📁 Dataset

The dataset contains customer shopping transactions with information such as:

Customer ID
Age
Gender
Item Purchased
Category
Purchase Amount (USD)
Location
Size
Color
Season
Review Rating
Subscription Status
Shipping Type
Discount Applied
Promo Code Used
Payment Method
Frequency of Purchases

🛠️ Tools & Technologies-
Python-	Data loading, preprocessing, EDA
Pandas-	Data cleaning and manipulation
NumPy	- Numerical operations
PostgreSQL Server	Business query analysis
Power BI	Interactive dashboard development

Jupyter Notebook in VS Code	Analysis and development
🔄 Project Workflow
1. Data Loading
Imported the dataset using Pandas.
Inspected data structure and data types.
Verified dataset dimensions.
2. Data Cleaning
Checked for missing values.
Removed duplicate records.
Corrected data types where required.
Validated data consistency.

3. SQL Analysis-
The cleaned dataset was imported into SQL databases PostgreSQL.

Business-focused SQL queries were written to answer questions such as:

Total revenue by category
Average purchase amount
Customer segmentation
Subscription-based analysis
Shipping method trends
Revenue by demographic groups
Category performance

4. Power BI Dashboard

An interactive dashboard was developed to visualize key business metrics and support decision-making.

The dashboard includes:

KPI Cards
Sales by Category
Revenue by Category
Customer Subscription Analysis
Sales by Age Group
Revenue by Age Group
Interactive Filters (Category, Shipping Type, Gender, Subscription Status)

📈 Dashboard Highlights- The Power BI dashboard provides an interactive overview of customer purchasing behavior through:

Total Customers
Average Review Rating
Average Purchase Amount
Sales by Product Category
Revenue Analysis
Subscription Status Distribution
Age Group Analysis
Dynamic Filters for better exploration
💡 Key Insights
Clothing generated the highest number of purchases and revenue.
Young Adults represented the largest customer segment.
Most customers were non-subscribers.
Purchase behavior varied across product categories and age groups.
Interactive filtering enables detailed business analysis across multiple dimensions.

<img width="374" height="226" alt="image" src="https://github.com/user-attachments/assets/1e6e388a-14aa-4320-a57c-9641ea047a0f" />

📂 Project Structure
Business-Intelligence-Purchase-Behavior-Analysis/
│
├── data/
│   └── customer_shopping_behavior.csv
│
├── notebooks/
│   └── Intelligence.ipynb
│
├── sql/
│   └── Purchase_behavior.sql
│
├── powerbi/
│   └── Purchase behavior analysis.pbix
│
│
└── README.md


▶️ How to Run
1. Clone the repository
git clone https://github.com/your-username/Business-Intelligence-Purchase-Behavior-Analysis.git
2. Install required Python libraries
pip install pandas numpy matplotlib seaborn sqlalchemy
3. Run the Jupyter Notebook

Open Intelligence.ipynb and execute all cells to:

Load the dataset
Perform data cleaning
Conduct exploratory data analysis
4. Execute SQL Queries
Import the cleaned dataset into PostgreSQL, MySQL, or SQL Server.
Run the queries provided in Purchase_behavior.sql.
5. Open the Power BI Dashboard

Open:

Purchase behavior analysis.pbix

using Microsoft Power BI Desktop.

