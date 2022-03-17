# Capstone Project Wellness Technology Company
This is a case study from Google Data Analytics Certification program for the wellness technology company. In this case study, I analyzed the public data [FitBit Fitness Tracker Data](https://www.kaggle.com/arashnic/fitbit) (CC0: Public Domain, dataset made available through [Mobius](https://www.kaggle.com/arashnic))that explores smart device users’ daily habits in order to gain insight into how consumers use non-Bellabeat smart devices, and applied the insights to one [Bellabeat](https://bellabeat.com/) product.

#### Scenario
You are a junior data analyst working on the marketing analyst team at Bellabeat, a high-tech manufacturer of health-focused products for women. Bellabeat is a successful small company, but they have the potential to become a larger player in the global smart device market. Urška Sršen, cofounder and Chief Creative Officer of Bellabeat, believes that analyzing smart device fitness data could help unlock new growth opportunities for the company. You have been asked to focus on one of
Bellabeat’s products and analyze smart device data to gain insight into how consumers are using their smart devices. The insights you discover will then help guide marketing strategy for the company. You will present your analysis to the Bellabeat executive team along with your high-level recommendations for Bellabeat’s marketing strategy.

Business task: Task: analyze smart device usage data in order to gain insight into how consumers use non-Bellabeat smart devices and apply the insight to Bellabeat’s product to design marketing strategy.

### Data Visualization

![totaltimeinbed_vs_timeasleep](https://github.com/CindyGuanYG/capstone_project_wellness_tech/blob/main/Totaltimeinbed_totalasleep.jpg)
![Count_Total_Minutes_Asleep](https://github.com/CindyGuanYG/capstone_project_wellness_tech/blob/main/Count%20Total%20Minutes%20Asleep%20in%20Categories.jpg)
![SedentaryMinutes_TotalSteps](https://github.com/CindyGuanYG/capstone_project_wellness_tech/blob/main/sedentaryminutes_totalsteps.jpg)
![calories_vs_totalsteps](https://github.com/CindyGuanYG/capstone_project_wellness_tech/blob/main/calories_totalsteps.jpg)
### Questions
1. What are some trends in smart device usage?

The total steps, calories burned, total minutes asleep, total time in bed, hourly intensity, and sedentary minutes are six key elements that people recorded with their smart devices and used in this analysis. The correlation between total steps and calories burned is positive (0.5915681). The correlation between total minutes asleep and total time in bed burned is strong and positive (0.9304575). However, the graph of count total minutes asleep shows that there are many sleep records of the participants are under 7 hours (420 minutes) each day. This needs to be improved because adults need 7 or more hours of sleep per night to maintain wellness based on [CDC](https://www.cdc.gov/sleep/data_statistics.html). 

Also, the data shows that the mean of daily total step is 7,638 and the third quartile is 10,727. Based on [Lifestyle Coach Facilitation Guide: Post-Core of CDC](https://www.cdc.gov/diabetes/prevention/pdf/postcurriculum_session8.pdf), the goal of daily total steps to maintain wellness is 10,000. Only the total steps from 75th percentile (Q3) and above in this data reaches the goal of 10,000.

Moreover, the hourly intensity shows that the participants (8 unique Id in this case) have more intensities at 5:00 PM to 7:00 PM. It is reasonable because most people are off work at that time, yet increasing the sample size will help defining the trend better. The data from the dailyActivity_merged.csv file shows the mean sedentary minutes of the participant is 991.2 (16.52 hr).  

2. How could these trends apply to Bellabeat customers?

Based on the trends above, the Leaf (classic wellness tracker) of Bellabeat is good products for keeping track of sleep and activity.  The Leaf tracker connects with the app has sleep goal to maintain a good sleep habit. The Leaf tracker is able to keep track of light sleep and deep sleep. It also has goal for steps and active hours for exercise to achieve wellness goal. Bellabeat Leaf tracker can keep track of activity like walking and calories burned. Leaf has the inactivity alert feature, which it will remind the user to move more or less often, by vibrating consecutively when the user has been inactive. The user needs to do a certain number of steps to not have the Leaf tracker reminds. It will be better if Bellabeat can extend on this feature, such as reminding the user to stand up instead of walk when ones sedentary time is long. Since there is job position requires the person to stay in the same location most of time and cannot satisfy the requirement of steps, it will help the user to burn more calories even in the work environment when the user stands up instead of sitting.

3. How could these trends help influence Bellabeat marketing strategy?

These trends could help influence Bellabeat marketing strategy by allowing Bellbeat to advertise its products are capable to do the same as other fitness trackers and more for women. Bellabeat Leaf tracker connects to the Bellabeat app to track activity, sleep, and stress. Based on [Office on Women's Health (OASH)](https://www.womenshealth.gov/a-z-topics/insomnia), stress and hormonal changes can cause insomnia for women. The Leaf keeps track of stress with Bellabeat app will be helpful to evaluate stress level. In addition, Bellabeat app offers meditation and period tracking.

### Recommendations
* The data demonstrates that **total steps and total minutes asleep of the participants need to be improved**. Bellabeat can develop a **feature of daily planner with recommendation** in the app, so the Bellabeat user can input her daily schedule into the app, and the Leaf tracker that connects to the app will alert when it is the best time to exercise or sleep. 

 * The **inactivity alert** should be mentioned not only on the feature page , it should be also in the **Leaf’s introduction website page** since **reducing the sedentary minutes are needed**.

### Further Analysis Suggestions
* Bellabeat can ask their users’ permissions to collect the data of total time in bed and total time asleep to measure the correlation and compare with the correlation found from FitBit track data to check the effectiveness of Bellabeat product.

