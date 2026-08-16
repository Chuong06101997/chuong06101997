# Trần Văn Thành Chương

**Data Analyst | SQL · Python · Power BI · Statistics**

---

## About Me

I started my career in food technology, working in quality control where I was responsible for sampling and evaluating food products against quality standards. Over time, I realized that I wanted to work closer to business problems and develop stronger skills in problem-solving, communication, and decision-making.

Data Analytics became a natural intersection of the areas I was looking for: quantitative thinking, statistical reasoning, and business context. It also changed how I think about data. Rather than assuming a dataset is sufficient simply because it is available, I want to understand what decision the analysis supports, whether the data can actually answer the question, and what sources of bias or uncertainty may affect the conclusion.

My goal is to continuously improve the frameworks I use for analysis, reduce avoidable analytical errors, and provide stakeholders with evidence they can use to make better-informed decisions.

## Skills

### Analytics
- SQL
- Python
- Exploratory Data Analysis (EDA)
- Data Cleaning
- Business Analysis
- Statistical Analysis

### Business Intelligence
- Power BI
- DAX
- Data Visualization
- Dashboard Development

### Data Engineering
- SQL
- ETL / Data Transformation
- Data Modeling

### Statistics
- Descriptive Statistics
- Hypothesis Testing
- Statistical Inference
- Sampling & Bias Analysis

### Machine Learning
- Logistic Regression
- Classification
- Model Evaluation
- Predictive Analytics

### Tools
- Excel
- Google Sheets
- Jupyter Notebook
- Git / GitHub

## Selected Projects

### 01. Sales Performance & Profitability Root Cause Analysis

Context: Investigated a $2.3M, 9,994-row retail dataset where sales and profit increased while profit margin declined, identifying Q4-2017 vs Q4-2016 as the period driving the margin deterioration.

Analysis: Tested product mix, regional effects, discounting, and customer-segment explanations, then stress-tested findings across transaction levels and outlier treatments.

Insight: 60.8% of the Q4 profit decline was traceable to a small number of large, deeply discounted transactions, including an 8–10 transaction Binders cluster accounting for 96.6% of the sub-category's decline. A customer-segment finding weakened by 54.1% after large-transaction outliers were excluded.

Action: Built an executive-facing Power BI dashboard and recommended targeted discount-governance and approval-process reviews, while not recommending broad product-mix changes unsupported by the data.

### 02. Customer Churn Prediction & Profit Optimization         

Business Problem: Retaining every at-risk customer can waste retention budget because customer value varies significantly.      

Analysis: Estimated churn probability for 7,043 customers and integrated it with customer lifetime value and retention cost to calculate Expected Profit.  


Key Findings: Not all high-risk customers were worth retaining; profitability depended on both churn risk and customer value.      

Business Action: Prioritized retention for customers with positive Expected Profit, reducing projected retention costs by $7,280 while improving budget allocation.   

### 03. F&B Product Innovation Analytics | Python, Statistical Analysis

Business problem: Investigated which recipe attributes and categories could signal stronger consumer evaluation to support F&B product development decisions.

Analysis & key findings: Analyzed 10,000 recipes, accounting for review exposure, category differences and potential confounders; found no robust evidence that category, preparation time, or nutrition attributes meaningfully differentiated consumer ratings across tested specifications.

Actionable recommendation: Recommended not prioritizing product development based on these attributes from this dataset alone, and instead validating potential opportunities with additional consumer data before investment.



### 04. SALES VOLATILITY & PROMOTION EFFECTIVENESS ANALYTICS                                         
 
Context: Analyzed 152,460 daily transactions across 91 SKUs and 2 stores to investigate recurring demand volatility, promotion effectiveness, and planning uncertainty.

*Analysis:* Formulated and tested hypotheses on promotions, seasonality, store differences, and weather using appropriate non-parametric methods, followed by a transparent seasonal forecasting benchmark.

Insight: Promotion days showed a $151.53 higher average sales than non-promotion days, with no detectable sales dip in the following 3 days. The relationship was treated as associative rather than causal.

Action: Used the 28.63% WAPE benchmark as a baseline for targeted pilots, including promotion-day forecast adjustments and parallel testing against current planning, while avoiding unsupported ROI or causal claims.            

### 05. HR Data ETL Pipeline: Job Change Analytics
(Coursework project — Swiss Coding Academy Data Analytics Program)

Context: Built an end-to-end ETL pipeline consolidating ~20,000 HR enrollee records from 5 heterogeneous sources — Google
Sheets, Excel, CSV, a MySQL database, and a web-based table — into a single SQLite database for downstream analytics.

Process: Diagnosed data quality issues per source (missing values, inconsistent data types) and applied source-appropriate
fixes — mode imputation for categorical fields without added context, and explicit placeholder categories (e.g.,
"no_enrollment," "No Major") where a missing value carried real meaning rather than being random.

Implementation: Connected to a MySQL database via SQLAlchemy/pymysql, loaded and transformed all sources with pandas,
and refactored the load step into a reusable function across multiple tables.

Output: Documented a scheduling approach (Google Colab + Apps Script trigger) for running the pipeline on a recurring basis.

## Analytical Approach

Business Question  
↓  
Data Validation  
↓  
Exploratory Analysis  
↓  
Statistical / Analytical Testing  
↓  
Insight  
↓  
Business Recommendation

## Contact

- Email: tranchuong06101997@gmail.com
- LinkedIn: https://www.linkedin.com/in/ch%C6%B0%C6%A1ng-tr%E1%BA%A7n-9a5b54348/

<!--
**Chuong06101997/chuong06101997** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
