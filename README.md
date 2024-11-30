# Sleep-Quality-Analysis/DSA210 Project

# Analyzing the Impact of Daily Habits on Sleep Quality

## Project Overview
For the next three months, I will study how my daily habits affect the quality of my sleep. I will focus on factors such as screen time, stress levels, calorie intake, smoking, physical activity, eating patterns, caffeine consumption, sleep schedule, natural light exposure, and activities before bed.

My goal is to discover which of these habits have the biggest impact on my sleep and see if changing them can lead to noticeable improvements. I will collect data on my daily routines and compare it to measures like how long I sleep and how rested I feel. I also plan to test if specific changes in my habits make a real difference in my sleep quality.

## Objectives
- **Understanding Sleep Quality:** To examine how daily habits like screen time, stress, calorie intake, smoking, exercise, and caffeine affect the quality of my sleep.
- **Identifying Key Factors:** To find out which habits have the biggest impact on my sleep and figure out what changes I can make for better results.
- **Improving Daily Routines:** To use insights from the data to adjust my lifestyle and improve how well I sleep.
- **Building Skills:** To apply data analysis and statistical techniques to a real-life problem and strengthen my skills in data science.

## Motivation
- **Personal Development:** Sleep is a vital part of health and well-being. By understanding how my daily habits affect my sleep quality, I aim to make meaningful changes that improve both my short-term rest and long-term health.
- **Data-Driven Approach:** Collecting and analyzing data on my lifestyle choices will provide a scientific basis for identifying patterns and optimizing my daily routines for better sleep.
- **DSA 210 Course and Practical Application:** This project gives me the opportunity to apply theoretical knowledge from the course to a real-life problem, enhancing my skills in data analysis and statistical methods.
- **Long-Term Benefits:** The insights gained from this project will not only help me improve my sleep quality but will also offer valuable guidance for achieving a more balanced and healthy lifestyle overall.

## Dataset
The dataset for this project consists of daily records I will collect over three months. The data includes the following attributes:
- **Date:** The specific day of the record.
- **Screen Time:** Time spent using electronic devices before bed (minutes).
- **Stress Levels:** Self-reported stress levels on a scale of 1 to 10.
- **Daily Calorie Intake:** Total calories consumed throughout the day (kcal).
- **Smoking:** Number of cigarettes smoked per day.
- **Physical Activity:** Duration of exercise or physical activity (minutes).
- **Eating Habits:** Timing and nutritional balance of meals.
- **Caffeine Consumption:** Amount of caffeine consumed (mg) and time of intake.
- **Sleep Schedule:** Bedtime, wake-up time, and total hours slept.
- **Natural Light Exposure:** Hours spent outdoors or exposed to daylight.
- **Pre-Sleep Activities:** Activities like reading, meditation, or screen usage before sleep.
- **Sleep Quality:** Self-rated sleep quality on a scale of 1 to 10.

The data will be recorded daily in an organized Excel file. This will help maintain consistency and allow for easy tracking and updates. Before starting the analysis, the dataset will undergo a cleaning process to address any gaps or errors, ensuring that the results are accurate and meaningful.

## Data Considerations
- **Outliers:** External factors such as illness, excessive fatigue, or significant life events will be flagged as potential outliers, as they may temporarily impact sleep quality.
- **Consistency in Data Collection:** Data will be recorded consistently each day, avoiding gaps or irregular entries that could affect the analysis.
- **Changes in Routine:** Any significant changes in daily habits, such as shifts in work schedules, dietary patterns, or physical activity levels, will be documented to account for their potential influence on the results.
- **Environmental Factors:** Variations in external conditions, like changes in sleeping environment or seasonal differences in natural light exposure, will also be noted to provide context for the findings.

## Tools and Technologies
- **Python:** For handling data cleaning, processing, and overall analysis.
- **Pandas:** To manage and manipulate the dataset efficiently, enabling preprocessing and preparation for analysis.
- **Matplotlib and Seaborn:** To create clear and insightful visualizations, such as trends and correlations between habits and sleep quality.
- **SciPy:** For conducting hypothesis testing to identify significant predictors of sleep quality and validate findings.

## Analysis Plan
### Data Collection:
The collected data will be imported into a Pandas DataFrame for analysis. During preprocessing, any missing or incomplete entries will be addressed, and all variables will be standardized to ensure consistency across the dataset. This step is critical to ensure the data is accurate and ready for exploration and modeling.

### Visualization:
- **Scatter Plots:** To observe relationships between variables, such as screen time vs. sleep quality.
- **Heatmaps:** To show correlations between all collected variables and identify the strongest associations.
- **Time Series Plots:** To track changes in sleep quality and other habits over the three-month period.

### Hypothesis Testing:
- **H₀:** Daily habits have no significant effect on sleep quality.
- **Hₐ:** Changes in one or more daily habits significantly affect sleep quality.
Regression analysis will be performed to identify which variables are the strongest predictors of sleep quality and to evaluate their statistical significance.

### Trend Analysis:
Trends over the three months will be examined to detect patterns or periods of improvement and decline in sleep quality. Particular attention will be given to how factors like caffeine consumption or stress align with variations in sleep quality metrics.

## Example Analysis
An example visualization could include a scatter plot illustrating the relationship between screen time before bed and sleep quality. In this case, the x-axis would represent screen time (in minutes), while the y-axis would display self-reported sleep quality (on a scale of 1 to 10). This type of plot would help determine whether increased screen usage before bedtime is associated with poorer sleep quality or has minimal impact.

## Conclusion
By the end of this project, I aim to uncover which daily habits have the most significant effect on my sleep quality. The insights gained will allow me to adjust my routines and make more informed decisions to improve both the duration and quality of my sleep. Beyond personal benefits, this project will demonstrate how data science techniques can be applied to analyze and optimize everyday behaviors, offering a practical approach to improving overall well-being.
