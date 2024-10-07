# Data Analyst Case Study: Analyzing Credit Usage and Repayment of Customers
## Introduction
This project analyzes credit issuance and repayment behavior using a dataset that includes information about users, their credit amounts, payment statuses, and demographic details. The goal is to gain insights into payment trends, identify factors influencing credit repayment, and visualize the data to support decision-making.

We utilize Python for data analysis, focusing on cleaning, transforming, and visualizing the dataset to understand credit usage and repayment behaviors among customers. This project leverages powerful libraries such as Pandas for data manipulation and Matplotlib and Seaborn for effective data visualization.

By the end of this analysis, we aim to uncover valuable insights that can help stakeholders make informed decisions regarding credit policies and repayment strategies.
## Data Description
The dataset includes the following key variables:
- `user_id`: Unique identifier for each user.
- `credit_id`: Unique identifier for each credit record.
- `credit_amount`: Amount of credit issued.
- `credit_service_fee`: Service fee associated with the credit.
- `credit_auto_repayment`: Indicates if the repayment is automated.
- `app_name`: Name of the application used for credit.
- `birthdate`: User's birthdate.
- `gender`: Gender of the user.
- `city`: City of residence.
- `payment_plan_id`: Identifier for the payment plan.
- `payment_plan_base_amount`: Base amount of the payment plan.
- `payment_plan_interest_amount`: Interest amount in the payment plan.
- `payment_plan_late_amount`: Late payment amount.
- `payment_plan_duedate`: Due date of the payment plan.
- `payment_plan_status`: Status of the payment (Paid, Unpaid, Late).
- `payment_id`: Identifier for each payment.
- `payment_amount`: Amount paid.
- `payment_date`: Date of payment.

## Analysis Goals
1. Analyze average credit amounts for unpaid credits.
2. Calculate average days late for late payments.
3. Find the average credit amount for early payments.
4. Analyze average age of customers by payment status.
5. Segment users into quartiles based on credit amounts.
6. Investigate the impact of demographic factors on credit behavior.

## Methodology
### Exploratory Data Analysis (EDA)
The project begins with an Exploratory Data Analysis (EDA) to understand the dataset's structure, identify patterns, and spot any anomalies. During the EDA phase, we perform the following tasks:
- Descriptive Statistics: Generate summary statistics to get an overview of the dataset.
- Distribution Analysis: Examine the distribution of key variables, such as credit amounts and repayment statuses.
- Correlation Analysis: Identify relationships between different features, such as age, credit amount, and payment status.
- Visualization: Utilize visual tools like histograms and box plots to represent the data visually and facilitate better understanding.

By performing EDA, we establish a foundation for more detailed analysis, allowing us to generate meaningful insights regarding credit usage and repayment behaviors among customers.
### Data Cleaning
- Missing Values: Analyze the dataset for any missing values and determine how to handle them, whether through imputation, removal, or other strategies.
- Outlier Analysis: Identify outliers that may skew the data and decide whether to remove or adjust them to ensure accurate analysis.
- Duplicate Rows: Examine the dataset for any duplicate entries and remove them to maintain data integrity.
### Data Transformation 
Various transformations were applied to derive new metrics, such as age, payment delays and quartiles.
### Analysis 
Used descriptive statistics and grouping methods to analyze payment behaviors.
### Visualization
Employed libraries like Matplotlib and Seaborn to visualize trends and insights.

## Conclusion
This analysis provides valuable insights into the credit data, revealing patterns in credit utilization, payment behaviors, and customer demographics. The visualizations serve to enhance the interpretation of the data, facilitating better decision-making and understanding of the credit landscape.

## Libraries
- pandas
- numpy
- matplotlib
- seaborn
- missingno
- warnings
