# Employees Performance Tracker Analysis With Power BI
# Introduction
Behind every company’s success are the people who make it happen. But managing people isn’t always simple — especially when it comes to understanding performance, satisfaction, and why some employees decide to leave.

To explore this challenge, I worked on a project using HR data from a fictional company called Atlas Lab. The goal was to transform raw data into insights that managers and HR leaders could actually use: Who are our employees? How satisfied are they? And what’s driving attrition?

Using Power BI, I designed interactive dashboards that told the story behind the numbers and helped highlight opportunities for action.
Problem Statement
Atlas Lab’s HR team had lots of employee data, but no clear way to turn it into decisions. They wanted to:

Monitor workforce size and attrition.
Understand demographics like age, gender, and marital status.
Track employee performance and satisfaction.
Discover patterns behind attrition and take steps to address them.
Without this, leaders were left guessing — making workforce planning harder than it needed to be.

# Methodology
Here’s how I approached the project step by step:

Data Preparation & Transformation — cleaned the dataset, removed duplicates, handled missing values, and created helpful new fields like age groups and full name.

Data Modeling — connected multiple tables and created a date table to support time-based analysis.

Data Exploration & Deep Dive — explored the data using over 25 dynamic measures in Power BI to drill into attrition, demographics, and performance.

Dashboard Development — designed four dashboards: Overview, Demography, Performance Tracker, and Attrition.

# Preparing the Data
Like any analysis, the first step was cleaning and preparing the data. I imported the dataset into Power Query, where I handled missing values, removed duplicates, and reshaped columns into a usable format.
From there, I built a data model with five connected tables. I also created my own Date table, which was crucial for running time-based calculations.
Press enter or click to view image in full size

# Data Exploration
The first step was to understand the workforce. I created dynamic measures to track:
Total Employees
Active vs. Inactive Employees
Attrition Rate → around 16.1%, a signal that turnover needed close attention.

As I explored deeper, several patterns stood out:
Age: Employees ranged from 18 to 51, with the majority (874) aged 20–29.

Gender: Roughly equal split between male and female, with a small group identifying as non-binary.

Marital Status: 37% single, 32% married, 20% divorced.

Ethnicity & Salary: White and Native Hawaiian employees earned the highest average salaries, while multi-ethnic employees earned the lowest — pointing to potential pay disparities.

### Key Finding: Travel & Attrition
The clearest insight came when I compared attrition against travel frequency:

Employees who traveled frequently had the highest attrition rates, across both departments and years.
Those with no travel requirements had the lowest attrition overall.
The “sometimes travel” group also showed elevated attrition in certain roles.
This highlighted travel as a potential root cause of turnover. Frequent travel often brings stress, fatigue, and work-life imbalance — and the data reflected that reality.

# Performance & Satisfaction Tracker
To support managers and stakeholders, I created a Performance Tracker dashboard. This report allows them to easily view and track key aspects of employee performance and satisfaction over time, including:

Job satisfaction
Environmental satisfaction
Relationship satisfaction
Work-life balance
Manager ratings
Sales ratings
This gives HR leaders and managers a clear, real-time view of how employees feel about their work environment and performance, helping them make better workforce decisions.

# Recommendations
Based on the insights, here’s what I recommended for Atlas Lab:

Review Travel Policies — reduce unnecessary travel, rotate assignments, and support frequent travelers with wellness programs.

Support Early-Career Employees — since attrition is highest in the first 1–2 years, strengthen onboarding and mentoring.

Investigate Pay Gaps — especially for multi-ethnic employees who consistently earned less.

Monitor Satisfaction Trends — use regular check-ins or surveys to catch dissatisfaction early.

Balance Workloads — address overtime patterns that also contributed to attrition.

# Conclusion
This project showed how HR data can do more than sit in spreadsheets — it can guide meaningful action. By transforming the data into interactive dashboards, Atlas Lab’s HR leaders could see not just how many people were leaving, but why.

The most important takeaway? Travel demands were a major driver of turnover. By addressing this, along with improving early-career support and pay equity, the company could improve retention and create a more sustainable workplace.
