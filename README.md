# Kickstarter-Analysis-Challenge-1

## Overview of Project
To analyze the Kickstarter data set for Louise to help compare how other campaign outcomes have performed based on their launch dates and funding goals.

### Purpose
To analyze theater kickstarters, comparing their campaign outcome results to the time of year the campaign was launched to see if there is an optimal time of year to launch a kickstarter. Also, to analyze how all campaign outcomes resulted based on the amount of their inital fiancial target goal broken down in to monetary tiers. 

## Analysis and Challenges
In order to deliver a more acurate analysis on ideal starting campaing goals we would have to convert all the currencies in the data set to be the same. There are about 10 different currencies used therefore our results are not displaying comparable values when looking at optimal fiancial target goals.    

### Analysis of Outcomes Based on Launch Date
From the historical data provided it can be determined that May is the ideal month to start a theater funding campaign and the months of June and July have a signifigantly greater sucess rates than the rest of the year as well. It can also be concluded that starting a campaign in December is the least likey start month to have a successful outcome for theatrical campaings. 

![Theatre_Outcomes_vs_Launch](https://user-images.githubusercontent.com/95573310/196800803-ff92b8c7-486d-41c9-98da-f1d66fa6fb60.png)

### Analysis of Outcomes Based on Goals
The line graph displays that overall the lower the goal of a campaign the higher the success rate up to $15000. After the $15000 threshold the fail rate signifigantly increases. The other observation that can be made is that the ammount of campaigns greatly reduces when the goal is set at $15000 or above which is intuitive in the sense that the higher the goal the less likely to accomplish that goal. 

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/95573310/196800864-6dec906e-6643-47bc-b899-7277268fdcb8.png)

### Challenges and Difficulties Encountered
For the most part this challenge was pretty straight forward. I did need a slight refreshener in writing the code for the countif function when creating the "Outcomes Based on Goals" sheet. 

## Results
Based on the two graphs that were created and the data set it can be concluded that the ideal campaign start date for theaters should be in the month of May followed by June and July, respectively. Also the optimal target goal for kickstarter campaigns should be between $1000 and $5000 and not exceed a goal of $15000 to ensure a higher success rate. Also when looking at the descriptive statistics sheet the mean goal of successful campaigns is right at $5049 and the standard deviation is $7749 reaffirming that a majority of successful campaigns is when the goal is under $15000. 
