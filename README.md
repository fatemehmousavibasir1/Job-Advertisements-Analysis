# Job-Advertisements-Analysis
This project analyzes job advertisements data from the **Quora** platform to gain insights into various aspects, including the increase in remote work post-COVID-19, the distribution of job postings throughout the day, and payment trends in the data field.

The project consists of several Jupyter Notebooks, each handling a specific part of the analysis process. Below are the steps and corresponding notebooks.

## Project Steps

### Step 1: Job Advertisements Offering Remote Work After COVID-19
- **Objective**: Calculate how much the rate of job advertisements offering remote work has increased compared to before the first official COVID-19 case in Iran.
- **Definition**: The "rate of job advertisements offering remote work" refers to the ratio of job ads offering remote work to the total number of ads.
- **Method**: We compare the rate of remote job ads before and after the official COVID-19 case date in Iran (February 19, 2020).

### Step 2: Job Posting Time Distribution Analysis
- **Objective**: Categorize the 24-hour day into four periods (dawn, morning, noon, night) and count how many job advertisements were posted in each period.
- **Method**: The 24-hour day is divided into four categories:
  - **Dawn**: 12:00 AM to 6:00 AM
  - **Morning**: 6:00 AM to 12:00 PM
  - **Noon**: 12:00 PM to 6:00 PM
  - **Night**: 6:00 PM to 12:00 AM

### Step 3: Data Payment Analysis
- **Objective**: Analyze the payment companies offer to individuals working in the data field.
- **Method**: Filter job postings related to the data field by using a set of predefined keywords in the job titles.
  - Analyze the salary distribution of these job postings.

---

## Tools & Libraries

This analysis utilizes the following tools and libraries:

- **Python**: The analysis is conducted using Python.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib / Seaborn**: For visualizations.
- **NumPy**: For statistical analysis.

--
