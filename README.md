# AB_Testing_Conversion_Rate

### Overview
This repository contains Python code for performing A/B testing on a dataset from Kaggle. The dataset includes the results of an A/B test conducted on two different designs of a website page (old_page vs. new_page). The goal of the analysis is to determine if there is a statistically significant difference in conversion rates between the two designs.

### Scenario
Let's imagine that you work on the product team at a medium-sized online e-commerce business. The UX designer has developed a new version of the product page, aiming to improve the conversion rate. The product manager (PM) has informed you that the current average conversion rate is 13% and that a 2% increase would be considered a successful improvement, resulting in a target conversion rate of 15%.

### Steps
The analysis is performed in the following steps:

- Designing the experiment
- Collecting and preparing the data
- Visualizing the results
- Testing the hypothesis
- Conclusions

### Description of files
- [ab_data.csv](https://www.kaggle.com/datasets/zhangluyuan/ab-testing?select=ab_data.csv): consists of 294,478 rows, each representing a user session, and includes the following columns:

| Columns  | Description |
| ------------- | ------------- |
| user_id | The user ID of each session |
| timestamp | Timestamp for the session |
| group | The group the user was assigned to for that session {control, treatment} |
| landing_page | The design each user saw on that session {old_page, new_page} |
| converted | Whether the session ended in a conversion or not (binary, 0=not converted, 1=converted) |

### List of python libraries used
`statsmodels` `pandas` `scipy` `numpy` `matplotlib` `seaborn`

### Snapshots
![image](https://github.com/yangfuchun/AB_Testing_Conversion_Rate/assets/100629848/eeffc4f8-f520-4303-8018-a360284649cb)



