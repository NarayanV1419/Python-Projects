# Overview
Welcome to my analysis of the data job market, focusing on data analyst roles. This project was created out of a desire to navigate and understand the job market more effectively. It delves into the top-paying and in-demand skills to help find optimal job opportunities for data analysts.

The data sourced from Luke Barousse's Python Course which provides foundation for my analysis, containing detailed information on job titles, salaries, locations, and essential skills. Through a series of Python scripts, I explore key question such as the most demanded skills, salary trends, and the intersection of demanded and salary in data analyst.

# The Questions
Below are the questions I want to answer in my project:
1. What are the skills most in demand for the top 3 most popular data roles?
2. How are in-demand skills trending for Data Analyst?
3. How well do jobs and skills pay for Data Analyst?

# Tools I Used
For my deep dive into the data analyst job market, I harnessed the power of several key tools:
1. Python: The Backbone of my analysis, allowing me to analyze the data and find critical insights. I also used following Python Libraries:
    1. Pandas Library: This was used to analyzed data.
    2. Matplotlib: Used to visualize data.
    3. Seaborn Library: Used to create more advance visualizations.

 2. Jupyter Notebook: The tool I used to run my Python scripts which let me easily include my notes and analysis.
 3. Visual Studio Code: My go-to for executing my Python scripts.
 4. Git & GitHub: Essential for version control and sharing my Python code and analysis. 

 # Challenges I faced
This Project was not without its challenges, but its provided good learning opportunities:

1. The biggest challenge was deciding what question to even ask from the data — separating "what skills get you hired" from "what skills get you paid" wasn't obvious at first and required multiple iterations of thinking before the right analytical framework clicked.

2. Filtering the dataset specifically for India introduced a sample size vs accuracy tradeoff — Indian job postings were significantly fewer than global ones, making it difficult to determine whether the salary insights were statistically reliable or just noise from limited data.

3. Choosing the right visualization for each insight was harder than the analysis itself — a bar chart, scatter plot and pie chart all tell different stories from the same data, and picking the wrong visual can completely mislead the reader even when the underlying numbers are correct.
# The Analysis

## 1. What are the most demanded skills for the top 3 most popular data roles?
To find the most demanded skills for the top 3 most popular data roles.
I filtered out those positions by which ones were the most popular, and got the top 5 skills for those top 3 roles. This query highlights the most popular job titles are there top skills, showing which skill I should pay attention to depending on the role's I'm targeting.

View my notebook with detailed steps here:
[2_skill_count.ipynb](Project\2_skill_demand.ipynb)

### Results
![Visualization of Top Skills for Data Nerds](Project\Images\Nerd.png)

### Insights
#### 1. SQL and Python are core skills across all data roles in India, making them essential for entry into the data job market.
#### 2. Skill demand is role-specific: Analysts focus on Excel/BI tools, Engineers on cloud & big data (AWS, Spark), and Scientists on Python-driven modeling.
#### 3. India’s data job market is highly practical and tool-driven, prioritizing job-ready skills over purely theoretical knowledge.

## 2. How are in-demand skills trending for Data Analyst?

View my notebook with detailed steps here: [3_skills_trend](Project\3_skills_trend.ipynb)

### Results

![Trending Top Skills for Data Analyst in India](Project\Images\skills.png)

*Line graph visualization the trending top skills for data analysts in the India in 2026.*

### Insights 
#### 1. SQL shows consistently high demand with relatively low volatility, indicating it is a stable, non-negotiable core skill for Data Analysts in India regardless of short-term market fluctuations.
#### 2. Python and Excel display converging trends toward the later months, suggesting a growing expectation for analysts to combine technical programming with traditional data handling and business-oriented tools.
#### 3. Power BI and Tableau remain comparatively lower but gradually rising, reflecting increasing adoption of visualization tools, though they still lag behind core analytical and programming skills in overall demand.

## 3. How well do jobs and skills pay for Data Analysts?

### Salary Analysis for Data Nerds

View my notebook with detailed steps here: [4_Salary_Analysis](Project\4_salary_analysis.ipynb)

### Results 

![Salary Distribution for Data Jobs in the India](Project\Images\Salary_distribution.png)

*Box plot visualization the salary distribution for the top 6 data job titles*

### Insights
#### 1. Machine Learning Engineers and Data Scientists show the widest salary ranges, indicating high variability driven by experience, company type, and specialization, with strong upside potential at higher skill levels.
#### 2. Data Engineers (especially senior roles) exhibit higher median salaries with multiple high-end outliers, reflecting strong demand in India for scalable data infrastructure and cloud expertise.
#### 3. Data Analysts and Software Engineers have comparatively lower and tighter salary distributions, suggesting more standardized pay bands and higher competition at entry-to-mid levels in the Indian job market.

## 4. How well do jobs and skills pay for Data Analyst

View my notebook with detailed steps here: [5_Top10_Paying_and_IN-Demand_skills](Project\5_Highest_Demand_And_most_Popular.ipynb)

### Results

![The Highest Paid and Most In-Demand Skills for Data Analyst In India](Project\Images\skill_comp.png)

*Two Separate bar graph visualizing the highest paid skills and Most In-Demand skills for Data Analyst in India*

### Insights
#### 1. Specialized database skills pay the most — Niche tools like PySpark, MongoDB, and Databricks command median salaries of $150K-$175K, far above everyday analyst tools.
#### 2. High-demand skills don't mean high pay — SQL, Excel, and Python are the most requested skills but only offer around $75K-$100K median salary due to their abundance in the market.
#### 3. R offers the best value among common skills — Despite being in the top 10 most in-demand skills, R delivers a competitive median salary, making it a smart choice for analysts wanting better pay without learning niche tools.

# Conclusion
This project analyzes the Indian Data Analyst job market using real-world job posting data to uncover the gap between the most in-demand skills and the highest paying skills. Through data cleaning, exploration and visualization, key insights were drawn around salary trends, skill demand patterns and regional job market behavior in India. The goal was to help aspiring Data Analysts in India make smarter, data-backed decisions about which skills to prioritize in their learning journey.