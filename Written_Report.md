# Kickstarting with Excel

## Overview of Project

### Purpose

#### Help Louise to understand the results of other artistic works to assimilate how different aspects can affect the future of her own work "Fever". Evaluating the results of the theater depending on the date on which it was launched and of the plays depending on the proposed goals. This, so that Louise can take certain steps to her own advantage by understanding how the release date and goals can affect the results of her work.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

#### Based on the "Kickstarter" database, create a pivot table by clicking the insert pivot table tab. Once created, I pressed this option, I selected the parent category and the years as filters, this to subsequently obtain the data by the months of each year and with the desired category, which in this case is theater. Then, I selected the results of each theater as a column and the sum of these by months as the filling of the cells within the table. Finally, I chose with rows the date of creation, in order to obtain the months of release of each theater. All this would result in a pivot table that would show me, according to the month, what was the sum of each possible result (successful, failed, etc.).

1.1 y 1.1.2

##### To get only the theater data, I clicked on the parent category filter and selected that option.

1.2

##### To get the successful theater results first, I clicked on the column labels filter and selected the descendant based on outcomes option.

1.3

#### Selecting the pivot table results, I inserted a line chart from the insert tab, so you can easily see theater results based on their release date.

1.4

### Analysis of Outcomes Based on Goals

#### Based on the KickStarter tab, I created a table that separates the projects of this tab by row according to their goal, after that I created different columns that would represent the sum of these projects (plays) according to their result, using the COUNTIFS function, to filter the sum of these projects as previously described as can be evidenced in the following image. Then I added the total of projects in the different categories according to the goal.

2.1

##### After that, I divided the sum of each category of results over the total of projects according to their goal, this to know their percentage.

2.2

##### Selecting the table results, I inserted a line chart from the insert tab, so you can easily see plays results based on their goal.

2.3

### Challenges and Difficulties Encountered

#### One of the difficulties encountered was that when carrying out the processes I always had to take into account that I was selecting the category of project that was being asked of me in the exercise to do the analysis, because in some cases the data of the different types of projects were still the same measures of central tendency and I was a bit confused. Another difficulty encountered is the use of $ to use the same row or column when performing calculations in the excel data sheet, and several times I forgot to use it and the calculations went wrong.

## Results

### What are two conclusions you can draw about the Outcomes based on Launch Date?

#### May was the month with the most successful theater releases. However, it was also the month with the highest number of failed launches, with nearly half as many successful as failed.

#### There is a high percentage drop in successful launches between May and September. A worrying percentage drop if one takes into account that in the same months the failed launches maintained a stable trend between 47 and 52, until a drop in September to 34.

### What can you conclude about the Outcomes based on Goals?

#### From the results based on the goals of the plays, I can conclude that the successful projects are completely inversely proportional to the unsuccessful ones, since there are none canceled, which makes each category the percentage filling of the other. Also, it can be concluded that the projects with goals between 45,000 and 49,999 were completely unsuccessful and that those between less than 1,000 and 4,999 and between 35,000 and 44,999 show a satisfactory percentage greater than 60%, making these projects the most likely to be satisfactory if only the goal set is taken into account.

### What are some limitations of this dataset?

#### One of the limitations of this database is that for the economic data used as the goal, the data is used and the appropriate currency exchange is not taken into account or was not made, or the change is not evident, leaving aside the equivalences of currencies, which can represent a change possibly power. However, it would be difficult to do it because depending on the release dates, there would be different exchange rates. Another obvious limitation of the database would be to only use quantitative and not qualitative data during the analysis, because there may be contextual reasons depending on the project that have led each one to be successful, failed and canceled.

### What are some other possible tables and/or graphs that we could create?

#### It would be interesting to obtain the exchange rate according to the launch date of each work to the dollar and in this way evaluate again (once the currency conversion has been made) the result of each work according to the established goals. It would also be relevant to study the Percentage Funded based on the launch date and the closing date, this to know how many days the project was on and know if this affected the funded percentage.
