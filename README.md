# Food-Claims-Analysis-On-Power-BI
Vivendo is a fast food chain in Brazil with over 200 outlets. The legal team wants to improve how long it takes to reply to customers and close claims.

*Data Exploratory Analysis*

**Claim_id:** There are 2000 unique values that match the description. There are no missing values. Therefore, no changes was made to this column.
 
**Time_to_close** There are 256 unique values that range between 76 and 518. No missing values, Therefore, no changes were made

**Claim_amount** The value in this column is between 1637.94 and 76106.8. The column contain the Brazilian dollar symbol, which was removed and the data type changed to Numeric.

**Amount_paid** This column value ranges between 1516.72 and 52498.75, which is in line with the description given. There were 36 missing values. The missing values were replaced with the median value of the remaining data, which is 20105.7.

**Location** The column is in line with the description with four unique values, which are RECIFE SAO LUIS  FORTALEZA and NATAL. No missing value.

**Individuals_on_claim** The values in this column were between 2 and 15. No missing value; therefore, no changes were made. This is consistence with the description given.

**Linked_cases** This column contains TRUE or FALSE with 26 missing values. The missing value was replaced with FALSE, as given in the description.

**Cause** The column contains vegetable, meat, unknown and VEGETABLES. 16 values were found to be VEGETABLES which require Trimming and changing of case. The inconsistent values were replaced with vegetable, as given in the description.
