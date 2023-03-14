# Sleep-Efficiency-Prediction
Predicting good or poor sleep efficiency as an indicator of sleep quality.

## Introduction 
The importance of sleep is paramount to health. Insufficient sleep can reduce physical, emotional, and mental well-being and can lead to a multitude of health complications among people with chronic conditions. Physical activity and sleep are highly interrelated health behaviors. Our physical activity during the day (ie, awake time) influences our quality of sleep, and vice versa. 

## Data Source.
The dataset for this project was gotten from kaggle. The link is; https://www.kaggle.com/datasets/equilibriumm/sleep-efficiency/code

## Dataset description
The dataset contains information about a group of test subjects and their sleep patterns. Each test subject is identified by a unique "Subject ID" and their age and gender are also recorded. The "Bedtime" and "Wakeup time" features indicate when each subject goes to bed and wakes up each day, and the "Sleep duration" feature records the total amount of time each subject slept in hours. The "Sleep efficiency" feature is a measure of the proportion of time spent in bed that is actually spent asleep. The "REM sleep percentage", "Deep sleep percentage", and "Light sleep percentage" features indicate the amount of time each subject spent in each stage of sleep. The "Awakenings" feature records the number of times each subject wakes up during the night. Additionally, the dataset includes information about each subject's caffeine and alcohol consumption in the 24 hours prior to bedtime, their smoking status, and their exercise frequency.

## Conclusion
Of the seven regression algorithms, Random Forest Regressor is the best. So, I carried out hyperparameter tuning inorder to further improve the model and made my predictions.
