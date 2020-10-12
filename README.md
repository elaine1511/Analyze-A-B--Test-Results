# Analyze-A-B-Test-Results
## Overview
For this project, I worked to understand the results of an A/B test run by an e-commerce website. My goal is to work through the notebook to help the company understand if they should implement the new page, keep the old page, or perhaps run the experiment longer to make their decision.
To complete this 3rd project, I'll need the following softwares:
- Python (Numpy, Pandas, Matplotlib, StatsModels, Scipy)
- Jupyter Notebook
## Table of contents
### Part I-Probability
Some statistics were computed to find out the probabilities of converting regardless of page. These were used to analyze if one page or the other led to more conversions.
### Part II-A/B Test
- Using hypothesis testing to assume the old page is better unless the new page proves to be definitely better at a Type I error rate of 5%.
- Conclusions were drawn on conversions for both pages by calculating p-values.
### Part III-Regression
- Logistic regression was performed to confirm results of the previous steps. Null and alternative hypotheses associated with this regression model were stated and verified using statsmodel.
- Then I added an effect based on which country a user lives. Statistical output using logistic regression was provided to check if country had an impact on conversion.
