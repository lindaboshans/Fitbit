# Fitbit Data Analysis: Activity, Heart Rate, and Sleep Quality

This repository is where I dive into the intriguing relationship between activity levels, resting heart rate, and sleep quality using my own Fitbit data. This project was driven by a curiosity and a desire to understand the impact of physical activity on two crucial aspects of health: cardiovascular efficiency and sleep.

## Project Insights and Objectives:
### Key Questions Explored:
How does activity level influence resting heart rate?
Can activity level predict sleep quality?

## Project Goals:
**Master Web Scraping**: Learn to efficiently extract Fitbit data using the API.

**Data Processing and Feature Engineering**: Clean and enhance the dataset by introducing innovative metrics such as:

**Exercise Efficiency**: Calculated as total active calories burned per total active zone minutes, aiming to quantify workout intensity.
**Sleep Efficiency**: Determined by the ratio of total sleep minutes to total time in bed, multiplied by 100, to evaluate the ease of falling asleep.
**Sleep Score**: Based on Fitbit's ideal sleep stage percentages (Awake 10%, REM 20%, Deep 18%, Light 52%), this metric offers a comprehensive view of sleep quality.
Detailed methodologies for these calculations are documented within the accompanying Jupyter notebook.

**Exploratory Data Analysis (EDA)**: Investigate patterns, distributions, and potential correlations within the data.

**Activity Level Categorization**: Utilize PCA for clustering activities into low, medium, and high activity levels.

**Linear Regression Analysis**: Assess the influence of activity levels on resting heart rate and sleep quality.

## Findings and Reflections:
The analysis revealed that, contrary to popular belief, there is no significant correlation between activity levels and resting heart rate in my case, although a trend toward a slightly lower resting heart rate was observed with higher activity levels. Additionally, sleep efficiency and sleep score did not show a linear dependency on activity level or exercise efficiency. These findings challenge the conventional wisdom that increased physical activity directly leads to lower resting heart rates and improved sleep quality. It's important to note that factors such as stress, diet, and lifestyle, which were not accounted for in this analysis, also play a significant role in influencing these health metrics. Moreover, the conclusions drawn from this single-subject study may not be broadly applicable to a larger population.

This project not only provided me with valuable skills in data extraction, cleaning, and analysis but also offered insights into the complex interplay between physical activity, heart health, and sleep. It underscores the importance of considering a wide range of factors when evaluating health outcomes and highlights the nuanced nature of personal health data analysis.
