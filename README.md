## Causal Analysis - Experiment Testing Using

### Technique Used: R, T Test and Linear Regression
### Question 1 - Use data_Q1.csv
- (a) If the control and treatment groups are similar across tenure, premium_user, and num_posts_before metrics.

- (b) Does getting reddit gold increase likelihood that the user will post (use the posted metric as the dependent variable and treated as the independent
variable)? Use a simple linear model (not a logit) for the analysis

- (c) What sorts of users are more likely to increase their contribution? (use the tenure and the first_timer variables)

- (d) Is the SUTVA assumption likely to be violated in the experiment?

### Question 2 - Use data_Q2.csv
- (a) Use a t-test to see if there is a statistical difference in the pre-period between schools in the treatment (bal = 1) and control (bal = 0). This will check if randomization has been done correctly. To do this, calculate the average normalized test score(norm) for the pre period (pre = 1) for math (test_type = 0). Is there a statistical difference between students who got the Balsakhi program and
- (b) Calculate the average test scores for the post period (post = 1) for math for treatment and control. Is there a statistical difference between students in the two groups of schools? Use a ttest model to test the increase. Perform the same analysis for language test scores.
- (c) Can you conclude if the Balsakhi program increase test scores in reading and mathematics?
- (d) Is the SUTVA assumption viloated in the example?

