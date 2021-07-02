# Marketing_CustomerValueAnalysion using Logistic Regression
Engagement Rate 
The first thing that we are going to look at is the aggregate engagement rate. This engagement rate is simply the percentage of customers that responded to the marketing calls
#To calculate Engagement rate , we we are grouping by the newly created field,
#Engaged, using the groupby function of a pandas DataFrame. Then, we are counting
#the number of records (or customers) in each Engaged group with the count
#function. By dividing by the total number of customers in the DataFrame and
#multiplying by 100.0, we get the engagement rate.

Sales Channels
To find any noticable changes between sales channel and engagement
Total Claim Amounts the differences in the distributions of Total Claim Amount between the engaged and non-engaged groups

 model output, we can see that Income, Monthly Premium Auto, Months Since Last Claim, Months Since Policy Inception, 
 and Number of Policies variables have significant relationships with the output variable, Engaged. For example, 
 Number of Policies variable is significant and is negatively correlated with Engaged. This suggests that the more policies that the customers have,
 the less likely they are to respond to marketing calls. As another example, the Months Since Last Claim variable is significant and is negatively correlated with the
 output variable, Engaged. 
 This means that the longer it has been since the last claim, the less likely that the customer is going to respond to marketing calls.
