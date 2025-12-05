# Customer-Behavior-Analysis-
This project focuses on analyzing customer purchasing behavior to uncover insights that help businesses improve sales strategies, customer retention, and product performance. Using a real-world customer shopping dataset, the project includes data cleaning,  and insight generation using Python, SQL Server, and Power BI.


⭐ Overview

This project demonstrates an end-to-end data analytics workflow using Python, SQL, and Power BI.
The goal is to analyze customer purchasing behavior, identify key business insights, build an interactive dashboard, and present findings in a clear, data-driven report.

The project includes:
Loading and exploring a real-world dataset
Cleaning and transforming data in Python
Running analytical SQL queries in MySQL Server
Designing a Power BI dashboard
Creating a final report and presentation
This repository is structured to be simple, readable, and recruiter-friendly, showing my complete analytics skill set.

📁 Dataset

  The dataset contains customer shopping behavior information, including:
  Demographics (age, gender, subscription status)
  Purchase behavior (items purchased, amount spent, shipping type)
  Discounts and review ratings
  Previous purchase history
  
  This data is used to derive insights on customer segments, product performance, and revenue drivers.

🛠 Tools & Technologies

  Python — Pandas, NumPy, Matplotlib/Seaborn for EDA
  MySQL Server — SQL queries for deeper analytical tasks
  Power BI — Dashboard and data visualization
  Jupyter Notebook — EDA and data cleaning workflow
  Gamma / PPT — Final presentation and storytelling
  GitHub — Version control and project documentation

🔧 Project Steps
  1. Load the Dataset (Python)
     Import CSV into a Pandas DataFrame
     Inspect structure (info(), describe(), head())
     Check data types and missing values

2. Exploratory Data Analysis (EDA)
  Analyze demographic and behavioral patterns 
  Visualize spending, ratings, and category distributions
  Identify trends and outliers

3. Data Cleaning
  Handle missing values
  Fix inconsistent formatting
  Create new features (age groups, purchase frequency, customer segments)
  Encode categorical variables

4. SQL Analytics (MySQL Server)
  Analytical queries include:
  Revenue comparison by gender
  Top 5 products by rating
  New vs Returning vs Loyal customer segmentation
  Shipping type performance
  Discount effectiveness
  Revenue contribution by age group

5. Build the Power BI Dashboard
Dashboard includes:
   KPIs (revenue, average order value, customer count)
   Top products & categorie
   Customer segmentation view
   Demographic analysis
   Shipping & discount performance

6. Create Final Report & Presentation
  Using Gamma / PowerPoint, I created a clear business-focused presentation summarizing:
  Key insights
 Visualizations

Recommendations for business decisions

📊 Dashboard Preview
The Power BI dashboard provides a complete picture of customer behavior with:
 Interactive filters
 Dynamic charts
 Product performance visuals
 Customer segments and trends

✅ Key Results & Insights
  Identified high-value customer groups and buying patterns
  Top-rated and top-selling products highlighted
  Loyal customers show significantly higher lifetime value
  Discounts influence purchasing but not always revenue
  Express shipping customers tend to spend more on average
  Age group 25–34 contributes the most to overall revenue

These insights can help marketing, product teams, and customer retention teams make better decisions.

How to Run This Project Locally
1. Clone the Repository
git clone https://github.com/yourusername/customer-behavior-analysis.git
cd customer-behavior-analysis

2. Install Python Dependencies
pip install -r requirements.txt

3. Run the Notebook
Open Jupyter Notebook:
jupyter notebook
Run the EDA and cleaning steps.

4. Load Data into MySQL Server
Use the SQL scripts in /sql/ and run them in MySQL Workbench or cmd.

5. Open Power BI Dashboard
Load the .pbix file to view or edit dashboards.

6. View Report / PPT

Open the Gamma-generated PPT in /presentation/.

📂 Project Structure
├── data/
│   └── customer_shopping_behavior.csv
├── notebooks/
│   └── EDA_and_Cleaning.ipynb
├── sql/
│   └── analytics_queries.sql
├── dashboard/
│   └── customer_behavior.pbix
├── presentation/
│   └── final_report.pptx
└── README.md

🎯 Conclusion

This project demonstrates practical analytics skills:
Python for data wrangling
SQL for structured insights
Power BI for business intelligence
Presentation for storytelling
