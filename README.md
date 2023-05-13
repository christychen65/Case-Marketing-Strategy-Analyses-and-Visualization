# Case-Study-Marketing-Strategy-Analyses-and-Visualization

### Table of contents
* [Introduction](#1)
* [1. Prepare](#2)
* [2. Limitations](#3)
* [3. Process](#4)
* [4. Analyze](#5)
* [5. Share & Act](#6)

## Introduction
Bellabeat is a wellness femtech company founded by Urška Sršen and Sandro Mur in 2014. It manufactures health-focused smart products that collect data on activity, sleep, stress, and reproductive health and empower women with knowledge about their own health and habits. Since it was founded in 2013, Bellabeat has grown rapidly and quickly positioned itself as a tech-driven wellness company for women. Their products include Bellabeat app, tracker (which can be worn as a bracelet, necklace, or clip), wellness watch, water bottle, and Bellabeat membership.

* Our task is to analyze smart device usage data in order to gain insight into how people are already using their smart devices. Then, We will use this information to provide high-level recommendations for how these trends can inform Bellabeat marketing strategy.

* Our key stakeholders are Urška Sršen, Sando Mur, and Bellabeat marketing analytics team.

<a id="2"></a>
## 1. Prepare
The dataset used in this case study is available <b><a href="https://www.kaggle.com/datasets/arashnic/fitbit">on Kaggle</a></b>
: This dataset generated by respondents to a distributed survey via Amazon Mechanical Turk between March 12, 2016 to May 12, 2016. <b><mark>Thirty eligible Fitbit users</mark></b> consented to the submission of personal tracker data, including minute-level output for physical activity, heart rate, and sleep monitoring.
Besides, the dataset includes information about daily activity, steps, and heart rate that can be used to explore users’ habits. 

* We will use the <b><mark>dailyActivity_merged</mark></b>, <b><mark>dailySteps_merged</mark></b>, <b><mark>sleepDay_merged</mark></b>, <b><mark>dailyCalories_merged</mark></b>, <b><mark>weightLogInfo_merged</mark></b>, <b><mark>dailyIntensities_merged</mark></b>, and <b><mark>hourlyIntensities_merged</mark></b> data in the following analysis.


<a id="3"></a>
## 2. Limitations

* This dataset does not contain information such as age and occupations. It may be difficult to customize marketing strategies based on customers' needs.
* Given that 33 Fitbit users participated in the survey, the sample size is small and the result may lead to a biased outcome.
* This survey took place 6 years ago. The findings may not be helpful for today.

<a id="4"></a>

## 3. Process

* First, let's load packages and files in R.
```
#Loading packages
library(tidyverse)
library(lubridate)
library(ggplot2)
library(dplyr)
library(tidyr)
```

* #### **Recommendations**
1. Since Bellabeat is a a high-tech manufacturer of health-focused products for women, we assume that the vast majority of our consumers would be women. And according to the findings above, we could design our products as fashion accessories that would make people feel comfortable wearing it in any occasions.

2. The Bellabeat app or the smart devices should allow users to set a sleep schedule and a sleep focus. The sleep focus will be activated automatically based on the sleep scehdule set in the app. Also, our app should include a goal setting option to help customers meet their goals, and if their alarm setting does not meet the goal, recommendations or warnings should be provided.

3. Emphasize on the fact that how underweight or overweight can impact our health. Although only 8 users used Fitbit to track their weights, the importance between weight and health should not be neglected. We should encourgae customers to use more features on our apps, track and reflect on those data in order to live a healthy lifestyle.
4. 
