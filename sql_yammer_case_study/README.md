
## SQL Case Study : Drop in yammer user engagement

A drop in the measure of user engagement was observed in yammer users in th 1st week of August, 2014.

#### Hypotheses:
A few hypotheses to explain the drop were put forth:
1. A new API : Users and automated software may be still using an old set of APIs to connect to yammer, while a new release may have required the users to move to the new API for successful engagement
2. Bug : A bug in the measure of engagement could have occurred
3. Server side : Network infrastructure, network performance , dropped queries, and a periodic change in authentication passwords could have been another reason
4. Competing product : a competing product with better features and ease of migration from yammer could have been introduced


### ANALYSIS and VISUALIZATION: 
The analysis of the problem was done using SQL queries embeded in a report in ModeAnalytics, a platform for running SQL queries and  visualization
First the drop in the yammer user engagement was visualized. Then, it was determined that there was no sharp drop in daily sign ups for yammer users. Cohorts of retained users were created based on the number of weeks their user account was activated. Then the engagement was queried and visualized based on the platform/devices. Finally, the engagement was measured in terms of click-throughs in weekly digest vs. daily emails.

## Link to report : https://modeanalytics.com/krajeshjdata/reports/224e12c3359a

### CONCLUSION : 
Had there been a decline in due to competing product, the number of signs ups would have also decline and the trends in daily sign up did not exhibit any decline (Fig. 2)
There was a decline in users engagement for users who were activated for 10 weeks. Compared to computers, mobile platforms such as smartphones and tablets showed a decline
Further click-through of digest email showed decline. 

### RECOMMENDATION :
Therefore, the recommendation to the product team was to look into the areas of mobile platforms and weekly digests that brought about a  drop in engagement

