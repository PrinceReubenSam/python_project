# Data Analyst Job Market Insights  
##  Overview  
This project was created to **showcase my proficiency in Python** while analyzing the **data job market**, with a strong focus on **data analyst roles**.  
The motivation behind this analysis is to gain clarity on which skills matter most for landing optimal opportunities, both in terms of **demand** and **salary potential**.  

Using job data sourced from **Luke Barousse's Python Course**, I examine job titles, salaries, locations, and required skills.  
Through Python-based analysis, I aim to answer key questions about the evolving data job landscape.  
---

##  Key Questions  
This project investigates the following:  

1. Which skills are most in demand for the **top three data roles**?  
2. What are the trending/in-demand Skills for Data Analysts?  
---

## 🛠 Tools & Technologies  

- **Python** – Core programming language for analysis  
- **Pandas** – Data manipulation and analysis  
- **Matplotlib** – Data visualization  
- **Seaborn** – Advanced and styled data visualizations  
- **Jupyter Notebooks** – Interactive analysis and documentation  
- **Visual Studio Code** – Script execution and code development  
- **Git & GitHub** – Version control and project sharing
- **ChatGPT** - For further assistance

---
## Data Preparation and Cleanup
This section outlines the steps taken to prepare the data for analysis, ensuring accuracy and usability.

### Import & Clean Up Data
I start by importing necessary libraries and loading the dataset, followed by initial data cleaning tasks to ensure data quality, to focus my analysis on the U.S. job market, I apply filters to the dataset, narrowing down to roles based in the United States.
<img width="1756" height="748" alt="code1" src="https://github.com/user-attachments/assets/1cea52b9-6abe-4299-a11c-698fbeb6c590" />

## The Analysis  

Each Jupyter notebook explores a key aspect of the data job market.  

### 1. Most Demanded Skills for Top 3 Roles  
I identified the three most common job titles, then extracted the top five skills for each.  
This shows which skills are most valuable depending on the role.  

Detailed steps: [2_Skill_Demand.ipynb](Project/2_Skills_Count_Analysis.ipynb)
### Data visualization codes
<img width="1988" height="938" alt="code2" src="https://github.com/user-attachments/assets/31e72d7f-9813-4940-805f-170d9009a199" />

### Result

<img width="620" height="472" alt="image" src="https://github.com/user-attachments/assets/7fde191f-4154-47b0-9a2f-cd953a6d69eb" />

##  Insights  

- **SQL** is the top skill for Data Analysts and Data Scientists, appearing in over half of job postings.  
- **Python** dominates for Data Engineers (68%) and is also highly valued for Data Scientists (72%) and Data Engineers (65%).  
- Data Engineers often need specialized tools (**AWS, Azure, Spark**), while Analysts and Scientists rely more on general tools like **Excel** and **Tableau**.

  ### 2. Trending Skills for Data Analysts  

To track 2023 trends, I filtered **Data Analyst** roles and grouped skills by posting month.  
This revealed the **top five skills per month**, showing how their demand shifted over the year.  

 Detailed steps: [3_Skills_Trend.ipynb](Project/3_Skills_Trend_Analysis.ipynb)  

### Data visualization codes  

<img width="1696" height="862" alt="code3" src="https://github.com/user-attachments/assets/aa9f5800-8f6c-47c6-b826-d13bbda4e46e" />

### Result

<img width="363" height="265" alt="image" src="https://github.com/user-attachments/assets/531bce03-7049-484e-9cb1-fd5e0ac651fd" />

## insights

- SQL remains the top skill but declines about 10 percentage points (≈64% → ≈54%).
- Excel falls mid-year then rebounds, peaking ≈45% in Jul/Aug and finishing near ≈40%.
- Python and Tableau are stable around 30–35%, with Tableau rising late to ≈33%.
- Power BI is lowest (≈18–23%) but shows a small year-end uptick.
  
- #### Takeaway: prioritize SQL + Python/Excel, add Tableau for visualization; Power BI is secondary.
