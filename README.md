# Project_3_ab_testing
A/B tests are very commonly performed by data analysts and data scientists. It is important that you get some practice working with the difficulties of these.  For this project, i will be working to understand the results of an A/B test run by an e-commerce website. The company has developed a new web page in order to try and increase the number of users who "convert," meaning the number of users who decide to pay for the company's product. me goal is to work through this notebook to help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.
# I will work in three parts:
Part I - Probability.
Part II - A/B Test.
Part III - A regression approach.
# Conclusions
Part I:
The probability of an individual was calculated regardless of which page they receive is 11.96% The account for the individual in the control group was 12.04% and the account for the individual in the treatment group was 11.88% And that all the accounts are very close in terms of the individual, regardless of the page, and the two groups of control and treatment are very similar. On this, there is no evidence that the new page may lead to a change in transformations.
part II:
Null hypothese is H0: p_new - p_old <= 0 ,
Alternative hypothese is H1: p_new - p_old > 0.
P-Value: The probability of observing our statistic or a more extreme statistic from the null hypothesis. Type I error rate of 5%, and Pold > Alpha, we fail to reject the null. Therefore, the data show, with a type I error rate of 0.05, that the old page has higher probablity of convert rate than new page.
Part III:
As in this logistic regression model too, we find that the values do not show a substantial difference in teh conversion rates for control group and treatment group. This indicates that we can acceot the Null Hypothesis and keep the existing page as is. We can accept Null Hypothesis as there is no significant difference in conversion rates. We can reject alternate hypothesis.These results are based on given dataset. There may be limitations due to incorrect data or missing columns etc.
