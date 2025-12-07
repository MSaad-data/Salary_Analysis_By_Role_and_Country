Salary_Analysis_By_Role_and_Country_Excel_Project

Excel-based salary analysis for major data roles across countries. Includes formula-driven metrics, pivot tables, and a unified slicer for dynamic filtering. Helps users compare salary trends, role distribution, and key insights for data-driven decisions.

## Dataset used

 <a href="https://github.com/MSaad-data/Salary_Analysis_By_Role_and_Country/blob/main/Salary_Analysis_By_Role_and_Country.xlsx">Dataset view</a>

The dataset used in this project comes from Luke Barousse’s “Excel for Data Analytics” YouTube course. It is publicly available and used here only for learning and practice purposes. This dataset contains many columns, but for this project, I focused on three key columns: 

job_title_short	

job_country	

salary_year_avg

The goal of this project is to analyze data-related jobs across different countries. By looking at job titles like Data Analyst, Data Engineer, and Data Scientist, and the countries they are in, we can understand which countries have more opportunities and what the typical yearly salaries are. 
This information can help anyone interested in developing a career in data, whether they are looking for full-time jobs, freelancing gigs, or just want to understand the demand for different data roles globally.

This project marks the start of my learning in **Exploratory Data Analysis** (EDA). 
EDA is the process of examining data to understand patterns, trends, and basic statistics before doing more advanced analysis. 
For this project, I focused on the basics of EDA by using **COUNT**, **SUM**, **AVERAGE**, **MINIMUM**, and **MAXIMUM** on a dataset of data-related jobs. I applied these operations to understand how many jobs exist, the total salaries, the average yearly salary, and the salary ranges for different roles and countries.

I selected three fields in the **United States**: Data Analyst, Data Engineer, and Data Scientist. I performed manual calculations using Excel formulas:

COUNT – =COUNTIFS(...) to count the number of jobs in a given field and country.

SUM – =SUMIFS(...) to calculate the total salary for each field.

AVERAGE – =AVERAGEIFS(...) to find the average salary.

MINIMUM – =MINIFS(...) to find the lowest salary in each category.

MAXIMUM – =MAXIFS(...) to find the highest salary.

I created three separate tables for the United States, one for each field, and manually calculated these metrics to better understand the data. This process helps to learn the core operations of EDA and prepares the dataset for further analysis and visualization. Screenshots of each table are included below for reference.

**Data Analyst**
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/7def685a-3333-42e4-a11b-6ff83295cdba" />

**Data Engineer**
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/a10a1567-c2f8-42be-a578-f49b428f752a" />

**Data Scientist**
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/b9f96296-1b91-4f88-87ab-c78f3d64a3e8" />

For this project, I performed basic Exploratory Data Analysis (EDA) to examine patterns and trends in data-related jobs in the United States. I used COUNT, SUM, AVERAGE, MINIMUM, and MAXIMUM along with IF and IFS formulas to create three tables for Data Engineer, Data Scientist, and Data Analyst. From these tables, I learned how many jobs exist for each role, the total and average yearly salaries, and the salary ranges. 

For example, Data Scientists have fewer jobs than Data Analysts, but their average salary is higher, indicating higher demand or specialized skills. Data Engineers have moderate job counts and salaries, showing a balance between demand and pay. This process taught me how to uncover patterns in the data, like which roles pay more, which have more openings, and how salaries vary, giving a clearer understanding of the data job market. 

By doing this manually in Excel, I strengthened my understanding of basic EDA operations and how they reveal insights about trends, distributions, and potential gaps in the market.

## Using Pivot Tables for Analysis

Even though I created manual tables using formulas, I used pivot tables to make the analysis more flexible and interactive. Pivot tables allow me to quickly view and compare any job title in any country without creating multiple manual tables. 

With **slicers**, I can filter the data easily and examine different roles or countries in seconds. Pivot tables help keep the Excel file organized and avoid making it heavy or cluttered, especially when analyzing large datasets or multiple dimensions. This makes reviewing and comparing trends much faster and easier than using only formulas.

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/7f931e98-71a0-484a-8bd9-877ee427f361" />


This analysis shows the salary data for Data Analyst, Data Engineer, and Data Scientist roles in the United States. You can change the country or the job role using the slicer, and all pivot tables will update. This makes it easy to explore different roles and countries without creating extra tables. The goal is to see how each role behaves in terms of total salaries, average pay, minimum and maximum salaries, and number of jobs.

The total salary numbers give an idea of the size of each role in the job market. Data Analysts have a total of 412 million dollars. Data Engineers have a total of 386 million dollars. Data Scientists have a total of 638 million dollars. Data Scientists have the highest total, which can happen if a role pays more, has more jobs, or both. This shows that companies invest more in advanced analytics roles.

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/4db21d8e-8b2c-4699-8764-8f8071107084" />

The average salaries show the typical pay for each role. Data Analysts earn 94 thousand dollars on average. Data Engineers earn 134 thousand dollars. Data Scientists earn 139 thousand dollars. This shows a clear order where more technical roles pay more.

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/2bd8f709-75c6-420b-b3ac-06d06902ffd4" />

The minimum salaries show the lowest pay for each role. Data Analysts start at 25 thousand dollars. Data Engineers start at 23 thousand dollars. Data Scientists start at 30 thousand dollars. These lower values may include internships, junior roles, or smaller companies. They show that the dataset has a mix of experience levels.

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/beb621bd-023f-4a49-901e-d57e2e1f5070" />

The maximum salaries show the highest pay for each role. Data Analysts reach 375 thousand dollars. Data Engineers reach 525 thousand dollars. Data Scientists reach 960 thousand dollars. These numbers likely come from senior or leadership roles. The wide gap between minimum and maximum salaries shows a variety of pay levels in the market.

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/1517169b-1673-44d6-8938-c757c6afee07" />

The job counts show how many roles exist in the dataset. There are 8,339 Data Analyst jobs, 4,742 Data Engineer jobs, and 6,685 Data Scientist jobs. Analysts are the most common. Engineers are the least. Scientists are in the middle. This matches common patterns in the job market.

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/111ce9c6-30bb-45ca-aabc-4f8e4c6024b7" />

Overall, this analysis gives a clear view of salaries and job counts in the United States. The slicer allows anyone to check other countries or roles quickly. Pivot tables make the analysis simple, flexible, and easy to update. This helps users understand salary trends and job patterns quickly.




