# Preview
Here I have conducted an in-depth analysis of Fitbit fitness tracker data using Microsoft Excel to perform data cleaning, data transformation, exploratory data analysis (EDA), and customer segmentation. The project focuses on identifying behavioural patterns, deriving actionable insights, and evaluating potential customer segments to support strategic marketing initiatives and data-driven business decision-making for WeFit and its subsidiaries.

## Project Objective
The primary motive of this project is to analyze Fitbit user activity and sleep patterns to identify distinct customer segments based on their fitness habits, activity levels, and lifestyle behaviours. The analysis aims to identify potential customers for WeFit's subsidiaries — LeanFit, FitWear, and Sleepy-Nights — while uncovering meaningful usage trends and translating them into actionable business insights to support targeted marketing strategies, customer acquisition, and informed decision-making.

## Datasets used
-  <a href="https://github.com/haldarankur/Excel-Data-Analysis/blob/main/FitBit_Dataset.zip">Fitbit Dataset</a>

## Questions (KPIs)
LeanFit – Customer Segmentation
- Identify customers with an average BMI above 25.
- Identify customers with an average heart rate exceeding 185 BPM.

FitWear – Customer Segmentation
- Identify customers who wore their fitness trackers for more than 20 days.
- Identify customers recording an average of more than 30 very active minutes.
- Identify customers recording an average of more than 60 fairly active minutes.

Sleepy-Nights – Customer Segmentation
- Identify customers spending more time in bed but getting comparatively less sleep.
- Identify customers exhibiting irregular sleep schedules and inconsistent sleep patterns.

WeFit – Daily Activity Analysis & Dashboard
- Identify all unique user IDs from the daily activity dataset.
- Calculate the number of days each user wore their fitness tracker.
- Classify users into Active, Moderate, and Light categories based on usage days.
- Calculate the mean distance travelled by each user.
- Segment users into Pro, Intermediate, and Beginner categories based on mean distance.
- Calculate the total steps recorded by each user.
- Calculate the total calories burned by each user.
- Calculate each user's Very Active, Fairly Active, and Lightly Active Minutes.
- Repeat the analysis (user count, usage, activity, distance, steps, and calories) based on distinct dates.
- Create charts and visualizations using the filtered data to build a management dashboard.


<b>TAKE A GLANCE AT THE <a href="https://github.com/haldarankur/Excel-Data-Analysis/blob/main/fitbitanalysis.xlsx" target="_blank">
  FINAL DATA →
</a>
</b>

## Process
-  Import and inspect the Fitbit datasets to understand their structure and identify relevant data fields.
-  Clean and preprocess the datasets to ensure data consistency and accuracy.
-  Analyze BMI and heart rate metrics to identify potential customers for LeanFit.
-  Evaluate tracker usage frequency and activity levels to identify potential customers for FitWear.
-  Examine sleep duration and patterns to identify potential subscribers for Sleepy-Nights.
-  Extract unique user IDs and calculate individual tracker usage days from the Daily Activity dataset.
-  Segment users into Active, Moderate, and Light categories based on tracker usage frequency.
-  Calculate mean distance and classify users into Pro, Intermediate, and Beginner categories.
-  Calculate total steps, calories burned, and Very Active, Fairly Active, and Lightly Active Minutes for each user.
-  Repeat the activity analysis using distinct dates to determine daily usage and activity trends.
-  Create charts and visualizations from the processed data to develop an interactive management dashboard.

## Dashboard
<img width="520" height="278" alt="Screenshot 2026-11-13 020631" src="https://github.com/user-attachments/assets/7034898b-97ea-4baa-84d0-0368f9a38f9f" />

<img width="497" height="275" alt="Screenshot 2026-11-13 020923" src="https://github.com/user-attachments/assets/bbb8acbd-1684-4ba8-be08-413d111db154" />

<img width="485" height="274" alt="Screenshot 2026-11-13 021252" src="https://github.com/user-attachments/assets/996a6105-dbbf-4818-9bba-93ba825ae751" />

<img width="582" height="229" alt="Screenshot 2026-11-13 022228" src="https://github.com/user-attachments/assets/4832e21f-8b54-41b2-b238-d649687a6974" />

<img width="640" height="229" alt="Screenshot 2026-11-13 031001" src="https://github.com/user-attachments/assets/a8e8a872-8437-45e0-bd3a-c19f58101a58" />

<img width="410" height="243" alt="Screenshot 2026-11-13 031736" src="https://github.com/user-attachments/assets/99fa3dae-88b3-43f1-93cd-605147954ffe" />

<img width="603" height="275" alt="Screenshot 2026-11-13 032035" src="https://github.com/user-attachments/assets/f12b65e4-b8ab-4846-9aa8-9b375bd401d0" />


## Project Insight
1. "Task1_LeanFit"
- Identified 1 potential customer (Customer ID: 4558609924) meeting both the BMI above 25 and maximum heart rate above 185 BPM criteria.
- The identified customer recorded an average BMI of approximately 27.21 and a maximum heart rate of 199 BPM.

2. "Task2_FitWear"
- Identified 8 customers as already actively engaged in fitness based on tracker usage and very active minutes.
- Identified 1 potential customer interested in getting into fitness based on tracker usage and fairly active minutes exceeding 60 per day.
- The remaining 24 customers did not satisfy the defined qualification criteria.

3. "Task3_SleepDay"
- Out of 24 users, 12 recorded insufficient average sleep, 11 fell within the recommended sleep category, and 1 recorded excess sleep.
- Approximately 54% of the analyzed users fell outside the recommended sleep-duration range, indicating potential opportunities for Sleepy-Nights.

4. "Task4_ActivitySummary"
- Analyzed 33 unique users, classifying 29 as Active, 3 as Moderate, and 1 as Light based on tracker usage.
- Categorized users into 7 Pro, 17 Intermediate, and 9 Beginner fitness tiers based on mean distance travelled.
- Recorded 7.17 million total steps and approximately 2.17 million calories burned across the analyzed users.
- Identified 19,895 Very Active Minutes, 12,751 Fairly Active Minutes, and 181,244 Lightly Active Minutes.
- Date-wise analysis covered 31 distinct dates, with all dates classified as Active and 30 categorized as Intermediate and 1 as Beginner based on mean distance.


## Final Conclusion
This project demonstrates how Fitbit fitness tracker data can be transformed into meaningful business insights through data cleaning, analysis, and customer segmentation. The findings helped identify potential customer segments for LeanFit, FitWear, and Sleepy-Nights while uncovering valuable patterns in individual fitness activities, tracker usage, and sleep duration. Furthermore, the activity analysis provided a consolidated view of user engagement, fitness levels, and daily activity trends through measurable KPIs. Overall, the analysis highlights the potential of data-driven decision-making in developing targeted marketing strategies, improving customer engagement, and supporting business growth across WeFit and its subsidiaries.
