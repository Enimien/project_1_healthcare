# Fitbit Tracker DataSet Analysis

The data set used for this analysis is available on Kaggle: 

https://www.kaggle.com/datasets/haseeb85/fitbit-fitness-tracker-data?select=Fitabase+Data+4.12.16-5.12.16

## Task:

Analyze FitBit fitness tracker data to gain insights into how consumers are using the FitBit app and give recommendations to the public on how to live a better and healthier life based on the results that we found using the data.

## About the Dataset:

Data is publicly available on Kaggle. 
33 FitBit users consented to the submission of personal tracker data.
Data collected includes physical activity recorded in hours, heart rate, sleep monitoring, daily activity, steps and calories.

## Limitations:

There are limited users (33 unique IDs) and limited period of time (a month). In addition, the sample size may not be representative of the population.
The dataset is not catogorized for analysis (unspecified for gender, age, region, etc.).

## Tools:

Python is used for data merging, data cleaning, and visualization.

## CSV file used:

dailyCalories_merged.csv

dailyIntensities_merged.csv

hourlyCalories_merged.csv

hourlyIntensities_merged.csv

sleepDay_merged.csv

## Questions:

1. What is the average daily step count for users?
2. How does physical activity vary across different days of the week?
3. What time of day do users typically reach their peak activity levels?
4. How many active minutes do users accumulate daily, and how does this compare to recommended levels?
5. Do the activities during the day affect individuals sleep quality? How?

## Visualization Interpretations:

<img width="944" alt="Screenshot 2024-06-17 at 8 18 46 PM" src="https://github.com/Enimien/project_1_healthcare/assets/166356675/718dbd58-c859-47e2-9aba-bcabaaf3dd98">
<img width="649" alt="Screenshot 2024-06-17 at 8 23 41 PM" src="https://github.com/Enimien/project_1_healthcare/assets/166356675/69f5bd35-0bb2-4217-9ad3-6a78e503a278">

<img width="902" alt="Screenshot 2024-06-17 at 8 24 43 PM" src="https://github.com/Enimien/project_1_healthcare/assets/166356675/de6327bc-e8fa-4a43-91a2-b251303dd584">

![image](https://github.com/Enimien/project_1_healthcare/assets/166356675/9629c20a-8239-4d97-8b99-a88334ad6b70)
<img width="930" alt="image" src="https://github.com/Enimien/project_1_healthcare/assets/166356675/67b5b471-d4b1-40b7-8d37-fb98ecb8b893">

<img width="886" alt="image" src="https://github.com/Enimien/project_1_healthcare/assets/166356675/db3f7d7f-5a91-4bb8-a4ef-c1e234bad2da">
<img width="948" alt="image" src="https://github.com/Enimien/project_1_healthcare/assets/166356675/cc54558e-5ba1-41df-8775-abe9712a46a5">

**Description:** The pie chart shows that a large portion of users' daily activity time is spent in sedentary and lightly active states. These two categories together make up the majority of the pie chart, very active and fairly active minutes make up a smaller portion of the pie chart. The line chart shows peak activity times in the late morning and late afternoon, with low activity during typical sleep hours and early afternoon rest periods, this resonates the findings in question in earlier questions. The two charts complements each other suggest the same pattern, and provide insights for designing features such as targeted reminders or fitness programs during peak low activity times to encourage users to do more moderate to vigorous activities in their daily routine and potentially boost overall health.

<img width="795" alt="image" src="https://github.com/Enimien/project_1_healthcare/assets/166356675/97c79981-74dd-49dc-a251-0baa58e42664">
<img width="1522" alt="image" src="https://github.com/Enimien/project_1_healthcare/assets/166356675/38982f34-0ed1-42e4-b0f0-80821c93ed82">

**Description:**
There's really strong correlation between 'Total Minutes In Bed' and 'Total Minutes Asleep', the x value is 0.87.
The more calories you burnt during the day, the faster you will get to asleep.

##  Conclusions / Recommendations:

1. Importance of staying active.
2. The resulting plot visually represent the average total steps taken on each day of the week, showing that Saturday and Tuesday have the highest total steps across different days.
3. The pattern in question 4 can provide insights for designing interventions to increase daily physical activity, encouraging users to incorporate more moderate to vigorous activities into their daily routines could help balance the high proportion of sedentary and light activities. For example, targeted reminders or fitness programs during peak low-activity times.
4. The more calories burnt during the day, the less time you will take to fall asleep. If you have sleep issues, we would recommend users to try be more active during the daytime.
