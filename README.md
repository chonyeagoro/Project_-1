# Project_-1

This project was done in Pandas (Jupyter Notebook)

Analysis Goal

This analysis dives into the world of data careers, focusing on job roles, salaries, company locations, and experience levels. It's designed to help new entrants in the data field understand the current job market and salary expectations.

Structure of the Study

We follow a straightforward six-step analysis approach: asking questions, preparing the data, processing it, conducting the analysis, sharing findings, and recommending actions. Here’s a brief outline:

Objective: We start by clearly defining what we aim to achieve with this analysis.

Data Source: Next, we explain where our data comes from and why it’s reliable.

Data Prep: We detail how we've cleaned and organized the data for analysis.

Analysis: We present our analysis, supported by visual aids, to highlight key trends and figures.

Findings: We summarize our main discoveries and offer insights for data professionals.

Next Steps: Lastly, we suggest areas for further research or action based on our findings.

Goal of this Project
1. To see the trend of  the  job market between 2020-2023.
2. To Identify  the Top  10 Job Titles in the Data field.
3. To Compare the salary trends  based on the Job Titles.
4. To Identify  what the top 5 jobs have been between 2020-2023
5. To find out the highest number number of employees based on Job Category.
6. To Identify how experience level relates to specific job titles.

Columns Used for the Analysis

work_year: Indicates the year the salary information was gathered.

job_title: Describes the specific role, such as ‘Data Scientist’, ‘Data Engineer’, or ‘Data Analyst’.

job_category: Groups job titles into broader segments for simplified analysis.

salary_currency: Identifies the currency used for salary payments, including but not limited to USD and EUR.

salary: Lists the annual gross income for the role in the respective local currency.

salary_in_usd: Converts the gross annual salary to US Dollars (USD), facilitating a standardized comparison of salaries worldwide.

employee_residence: Specifies the employee’s country of residence.

experience_level: Categorizes the employee’s level of professional experience into segments like ‘Entry-level’, ‘Mid-level’, ‘Senior’, and ‘Executive’.

employment_type: Details the nature of the employment contract, which may be ‘Full-time’, ‘Part-time’, or ‘Contract’.

work_setting: Describes the employment setting, which could be ‘Remote’, ‘In-person’, or ‘Hybrid’.

company_location: Denotes the country in which the employing company is based.

company_size: Reflects the scale of the employing organization, typically classified as small (S), medium (M), or large (L).


Research Questions 
1. Provide a list of  the top 10 job titles in the United States to get a better understanding on what these titles were compared to the rest.
2. Find the distribution of the mean salary for the top 5 job titles in the given four years and then  represent the result distribution in percentages.
3. Analyze the data set provided and provide the top 5 job titles based on the job category count in the 4  years given.
4. How have the number of jobs in the job category evolved annually across different company locations from 2020 to 2023?
5. How does the average salary of Data Analysts in the United States vary by company size, work setting, and experience level??

Data Set Analysis Process

Grouping data by 'work_year', 'company_location', and 'job_category' and counting occurrences helped us understand:

Yearly Trends: How the interest in different data jobs has  changed over  each year.

Location Popularity:  Enabled us to know where certain data jobs were more common.

Career Insights: Showed us  the growth in various job titles and categories, therefore,  providing a guide with career decisions.

Popular Data Jobs:  Helped Identify the different data roles that are in demand.


Grouping data by 'year', 'job_location', and 'job_category' and counting occurrences helped us see:

Trends Over Time: How the growth of different data jobs changed each year.

Where Jobs Are: Which country had more data jobs based on the job category.

Popular Roles: What types of data jobs are common and how these trends have changed over time.

Job Insights: Showed us where these jobs were located which also highlighted  the progressive growth or lack thereof of the job categories. This provided a great insight as far as career path decisions.

Challenges Encountered
- Trying to figure out what type of graph would best represent the data. 
- Not having enough data in 2020 and 2021.
- There were changes in prevailing job titles as the years progressed.
- We couldn’t plot any global data due to a large majority  of the data jobs  provided were within the United States.

How could we have Solved the Challenges

- Research what types of graphs would be compatible with the data that were are trying to visualize (ex: bar and line graphs can be used to show the relationship between values).
- In retrospect, it might have been beneficial to consider alternative datasets to enrich our understanding of the years 2020 and 2021. While our analysis for 2022 and 2023 showed a comprehensive representation of values, the earlier years suffered from a scarcity of data. This could be attributed to either an inherent lack of available information or possibly a more pronounced evolution in data science methodologies post the COVID-19 pandemic.
- Since a majority of the job titles were located in the United States, we decided to focus on our analysis on the jobs located there.

Conclusions

1. Based on our analysis, we found out that Data Engineer was the top Job title across the the four years.
2. Data Scientist job has the highest amount of seniors among the top 10 job titles (having 1540 seniors) with Data Engineering having the second highest (having 1534 seniors).
3. United States has the most number of jobs in the data field when compared to other countries globally.
4. Data Analyst job had the most amount of entry-level employees (having 119 entry-levels).
5. Based on the analysis, we can conclude that there is a substantial growth in data  field job market when observing the trend (ex: Data Scientist had 19 positions in 2020 and then in 2023 there were 1538 positions).
6. The trend also shows that there’s an increase in salary (ex: Machine Learning (ML) engineer in 2020 made $145k and then in 2023 they made $205k).

Data Source

This dataset, titled “Jobs and Salaries in Data Science,” is sourced from https://www.kaggle.com/datasets/hummaamqaasim/jobs-in-data/download?datasetVersionNumber=6. It compiles data from both internal survey submissions and openly disclosed job salaries. 



