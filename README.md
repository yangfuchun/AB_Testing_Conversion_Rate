# AB_Testing_Conversion_Rate

This repository contains Python code for performing A/B testing on a dataset from Kaggle. The dataset includes the results of an A/B test conducted on two different designs of a website page (old_page vs. new_page). The goal of the analysis is to determine if there is a statistically significant difference in conversion rates between the two designs.

### Scenario
Let's imagine that you work on the product team at a medium-sized online e-commerce business. The UX designer has developed a new version of the product page, aiming to improve the conversion rate. The product manager (PM) has informed you that the current average conversion rate is 13% and that a 2% increase would be considered a successful improvement, resulting in a target conversion rate of 15%.

### Steps
The analysis is performed in the following steps:

Designing the experiment
Collecting and preparing the data
Visualizing the results
Testing the hypothesis
Conclusions

### Dataset
The dataset used for the A/B test is stored in the ab_data.csv file. It consists of 294,478 rows, each representing a user session, and includes the following columns:

user_id: The user ID of each session
timestamp: Timestamp for the session
group: The group the user was assigned to for that session {control, treatment}
landing_page: The design each user saw on that session {old_page, new_page}
converted: Whether the session ended in a conversion or not (binary, 0=not converted, 1=converted)


#### Step 1: Designing the Experiment
In this step, we formulate a hypothesis and determine the variables and sample size needed for the A/B test. The code provided demonstrates how to calculate the required sample size based on the desired statistical power, alpha value, and expected effect size.

#### Step 2: Collecting and Preparing the Data
In this step, we explore the dataset, clean the data if necessary, and sample the required number of observations for each group. The provided code demonstrates how to load the dataset, perform basic data exploration, handle missing values, and sample the required number of observations.

#### Step 3: Visualizing the Results
This step involves visualizing the conversion rates for the control and treatment groups. The code provided shows how to calculate and visualize the conversion rates using bar plots.

#### Step 4: Testing the Hypothesis
In this step, we perform statistical tests to evaluate the significance of the observed differences in conversion rates between the control and treatment groups. The code demonstrates how to conduct a Z-test, calculate confidence intervals, and perform logistic regression analysis.

#### Step 5: Conclusions
Based on the results of the A/B test, the conclusion is drawn regarding the effectiveness of the new design in improving the conversion rate. The provided code displays the conclusions based on the statistical analysis.

Please refer to the Jupyter Notebook or Python script in this repository for the complete code implementation and detailed explanations of each step.




