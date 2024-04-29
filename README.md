# Hosptal ER Dashboard

<img src="https://github.com/EddyBoror/Hospital-Emergency-Room/blob/Analysis-Projects/Hospital_ER.webp" width="1700" height="450" />


# Project Overview

The next project was something new and thrilling for me. I was excited to dive into a medical dataset and explore the unknown areas to learn more about how the variables and values in this dataset varied from those in my earlier works. In addition, this project allowed me to become more familiar with Power BI, a tool I hadn't used aside from Tableau, for dashboard building and visualization. My goal was to create a user-friendly, interactive dashboard for a hospital emergency room that would allow users to see patient satisfaction ratings and average age in a simulated dataset.

<be>

# Issues

- The dataset's quality was effective, and no problems were found when analyzing it.

- I created more variables to improve the depth of the analysis.

- I created new metrics to enable comparisons in addition to more perceptive calculations.


# Data Sources
I obtained the proxy dataset from Data.world, which comprises various datasets contributed by the community. It's important to note that the information within the dataset is not real, as it's made up by the data world community to avoid HIPAA violations and is solely used for project development purposes.

[Download here](https://data.world/markbradbourne/rwfd-real-world-fake-data/workspace/file?filename=Hospital+ER.csv)

<br>

# Tools

- Power BI: Building interactive dashboards for comprehensive data representation.

<br>

# Data Cleaning/ Preparation /

In the initial data preparation phase, I performed the following tasks in Power BI through Power Query:

1. Data Transformation
   
Added a new column to reflect dates in weekday format:

<img width="526" alt="image" src="https://github.com/EddyBoror/Hospital-Emergency-Room/assets/61037075/342defc0-2dff-4af6-9347-6a25554f8a45">

Added a new AM and PM Column for slicer feature used in the interactive dashboard

<img width="128" alt="image" src="https://github.com/EddyBoror/Hospital-Emergency-Room/assets/61037075/03ea51d3-4ce3-4abc-a98a-194bbeb9ef3a">



<br>

# Exploratory Data Analysis

### Insight 1

![PBIDesktop_pgaLvTNtBZ](https://github.com/EddyBoror/Hospital-Emergency-Room/assets/61037075/33203ad9-855e-43aa-ab39-bd6d9e619ec1)

This is my first encounter with a decomposition tree visualization, and I found it interesting to incorporate into my analysis. As you can see the  decomposition tree chart is showing off the total # of patients within the dataset. But it can also branch off to discuss the race out of the total patient numbers, into which gender was the highest of that patient category and which department referred them, and lastly, on what day was the highest number of patients going into the ER throughout the week. All this I’m showing off right now in real time. I cannot do this on Tableau without recording it. 

The analysis visualization shows the dataset contains a higher amount of patients with caucasian demographic. The gender is split evenly among the 1063 number of patients. If we drill down to the department that referred them to the ER we see that Gneral practice and Orthopedics were among the top numbers in the dataset. Lastly, we can see that Saturday and Thursdays were the least amount of busy days throughout the week. 

### Insight 2

<img width="1039" alt="image" src="https://github.com/EddyBoror/Hospital-Emergency-Room/assets/61037075/7e907da1-a5da-4672-b2f7-b878f67cbd70">


The bar chart illustrates age groups by race in the dataset. African Americans rank as the second highest demographic, with the largest age group being 66 years and older. Interestingly, the second largest age group comprises patients aged 0-18, preceding the 19-65 age group.


# Power BI Interactive Dashboard

![PBIDesktop_ow7FuQcV99](https://github.com/EddyBoror/Hospital-Emergency-Room/assets/61037075/e0b836fc-2d1a-4d73-9030-26e949fe6686)

<br>

Emergency room (ER) staff can see a detailed overview of patient demographics and referral patterns through the ER Patient Demographics and Referral Analysis Dashboard. The dashboard includes visualizations such as average wait time, a patient satisfaction measure, and gender slicers for filtering data by male and female patients. Real-time insights on the patient experience are provided by these indicators. A line graph showing patient age by age group is also included on the dashboard, enabling personnel to see which age groups are most frequently visiting the emergency room. Understanding the racial background of patients and referral sources is made easier with the help of bar charts, which further break down patient race within patient numbers and department referrals. Last but not least, a heatmap that shows patient race by month and correlates it with the average patient age aids staff in seeing patterns in demographic and age distribution across time. Based on demographic trends and referral sources, the dashboard's interactive features enable emergency room staff to make well-informed decisions about patient care methods and resource allocation.


The analysis visualization reveals that the dataset predominantly consists of patients from the Caucasian demographic. Gender distribution is evenly split among the 1,063 patients. Upon further examination of the referring departments, General Practice and Orthopedics emerge as the top sources of referrals to the ER. Additionally, the data indicates that Saturdays and Thursdays experienced the least activity compared to other days of the week.

# Conclusion Analysis

Working with this proxy healthcare dataset has provided me with valuable insights into data analysis within a different field, and I thoroughly enjoyed the process of analyzing the data and creating the dashboard. It's fascinating to see the wealth of information that can be uncovered through visualization and interactive tools. I look forward to applying this experience to real-world scenarios in the future and creating more impactful dashboards.
