# TikTokData Exploration - Google Advanced Analytics Course Project 1
This is the first Project from the Google Advanced Data Analytics Course. I have chosen to use the TikTok dataset provided by google.

## Scenario
TikTok’s data team is in the earliest stages of the claims classification project. The following tasks are needed before the team can begin the data analysis process:
- Build a dataframe for the TikTok dataset
- Examine data type of each column
- Gather descriptive statistics

## Project Overview
The code for the project can be found here: 
Several key task were performed such as: 
- Loading necessary packages (NumPy, Pandas)
- Importing TikTok dataset and converting into a Pandas dataframe
- Identifying relevant data structures and summarizing data
- Combining or modifying data structures to create meaningful variables

  ## Key Data Takeaways
  - Dataset Overview:
    - Contains 19,382 records with TikTok Metrics such as video views, likes, shares, downloads.
    - Key attributes investigated include claim_status and author_ban_status.
    - Missing several values within columns displayed as NaN.
      
  - key observations:
    - The Percentage of data is split between "claims" and "opinion" is 51% for claims(9,608 users) and 49%(9476 users) for opinions
    - Videos from "Banned" or "Under-review" users have a higher "claim" classification. These users also have a significantly higher count of likes, shares and comments in the "claim" category. In the "Opinion" classifcation the opposite is true, Active users have more engagement overall than the "Banned" or "Under-review" users.

  ## Technical Skills:
  1. **Data Exploration:**
     - Computing summary statistics (mean, median, min, max) in relevant categories.
     - Utilizing Pandas to filter, group, and transform data for actionable insights.
     - Understanding data distributions and trends in the dataset
  2. **Programming and Libraries:**
     - Proficency in Python
     - Utilized key Python libraries such as **Pandas** and **NumPy**
  3. **Problem Solving:**
     - Structuring and debugging Python code to perform analytical tasks
     - Understanding questions proposed in project statement and emails
     - Interpreting data and designing workflows to achieve correct results
