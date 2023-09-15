# Food-Claims-Analysis-On-Power-BI
Vivendo is a fast food chain in Brazil with over 200 outlets. The legal team 
Customers often claim compensation from the company for food poisoning. Therefore, the legal team, which has offices in four locations and is responsible for processing these claims, wants to improve how long it takes to reply to customers and close claims.
The head of the legal department wants me to report how each location differs in the time it takes to close claims.




## Data Exploratory Analysis

**Claim_id:** There are 2000 unique values that match the description. There are no missing values. Therefore, no changes was made to this column.
 
**Time_to_close** There are 256 unique values that range between 76 and 518. No missing values, Therefore, no changes were made

**Claim_amount** The value in this column is between 1637.94 and 76106.8. The column contain the Brazilian dollar symbol, which was removed and the data type changed to Numeric.

**Amount_paid** This column value ranges between 1516.72 and 52498.75, which is in line with the description given. There were 36 missing values. The missing values were replaced with the median value of the remaining data, which is 20105.7.

**Location** The column is in line with the description with four unique values, which are RECIFE SAO LUIS  FORTALEZA and NATAL. No missing value.

**Individuals_on_claim** The values in this column were between 2 and 15. No missing value; therefore, no changes were made. This is consistence with the description given.

**Linked_cases** This column contains TRUE or FALSE with 26 missing values. The missing value was replaced with FALSE, as given in the description.

**Cause** The column contains vegetable, meat, unknown and VEGETABLES. 16 values were found to be VEGETABLES which require Trimming and changing of case. The inconsistent values were replaced with vegetable, as given in the description.


### Analysis of number of claims in each location
![visualization that shows the number of claims in each location](https://github.com/AbbeySegun/Food-Claims-Analysis-On-Power-BI/blob/main/task%202.PNG))
 The visuals above revealed that RECIFE has the highest number of claims while SAO LUIS came second. However, the category are not balanced because fewer claims came from NATAL and FORTALEZA while other locations have higher claims.

### Distribution of time to close for all claims
![distribution of time to close for all claims](<img width="558" alt="task 3" src="https://github.com/AbbeySegun/Food-Claims-Analysis-On-Power-BI/assets/105546483/baa413b1-9f94-4ce9-8185-0f0cc81d11ff">)
From the claim chart distribution with the time taken, it can be deduced that most of the values fail between 100 and 200 days. This implies that the most number of claims falls within the range of 100 to 200 days. However, there are outliers that are above 200 and those that fail below 100.

The distribution of the number of times to close is symmetric.

### Relationship between time to close and location
![relationship between time to close and location](<img width="547" alt="task 4" src="https://github.com/AbbeySegun/Food-Claims-Analysis-On-Power-BI/assets/105546483/f2d9490a-ff80-4d02-bf51-16d34b17bea1">)
Checking the relationship between Time taken to Close claims and location, the above revealed that the claims in each location take about 184 to 188 days to close(on average). Due to the higher number of claims closing days in SAO LUIS, most of the claims there take an average of 188 days to close when compared to others.

The legal team should focus more on reducing claim closing time in those higher locations.
