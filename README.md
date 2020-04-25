<b> Overview </b>

The aim of this project is to analyze the conversion rates between an old and new website for an e-commerce company in order to check if the website change makes sense. Therefore, by analyzing the results of an AB Test, the goal is to help the company understand if they should implement the new page, keep the old page, or perhaps run the experiment longer to make their decision.

This project has three main parts:

1. Probability

2. Part II - A/B Test

A hypothesis testing was conducted assuming the new page is better than the old page at a Type I error rate of 5%.

The difference between the convertion rate of both pages was bootstrapped and a sampling distribution was determined and plot. 

3. Part III - Regression

Logistic regression was then performed to confirm results of the previous steps. Null and alternative hypotheses associated with this regression model were stated and verified using statsmodel.

Next, along with testing if the conversion rate changes for different pages, I added an effect based on which country a user lives. Statistical output using logistic regression was provided to check if country had an impact on conversion.

<b> Tools </b>

Ir order to complete this project, I've used:

1. Python (Numpy, Pandas, Matplotlib, StatsModels, Scipy)
2. Jupyter Notebook

<b> Conclusion </b> 

There was no statistic evidence that the new page had a better conversion rate than the old one. Besides that, the user's country had no impact the conversion rate.

