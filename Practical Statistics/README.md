# Analyze A/B Test Results

The chapter on practical statistics covers fairly dense material on Notation, Correlation, Outliers, Bias, Probability, Bayes Theorem, Distributions, Central Limit Theorem, Bootstrapping, Confidence Intervals, Hypothesis Testing, A/B Tests, Linear Regression, Logistic Regression and more..

To goal of the project is to familiarise oneself with A/B testing. 

 **A. Determine Objectives**
 
For this project, I will be working to understand the results of an A/B test run by an e-commerce website. The company has developed a new web page in order to try and increase the number of users who "convert," meaning the number of users who decide to pay for the company's product. My goal is to help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.

**B. Outline of Steps** 

1. Decide what questions to pose

2. Extract the data  

3. Import data into environment  

4. Use probability, the results of A/B Tests and Regression to draw insights

5. Create visualisations to aid and augment exploration 

6. Draw conclusions


**C. What Questions To Ask?**

1. What is the probability of an individual converting regardless of the page they receive?

2. Given that an individual was in the control group, what is the probability they converted?

3. Given that an individual was in the treatment group, what is the probability they converted?

4. What is the observed difference in conversion rate between the two landing pages?

5. What is the probability that an individual received the new page?

6. What is the convert rate for  𝑝𝑛𝑒𝑤  under the null?

7. What is the convert rate for  𝑝𝑜𝑙𝑑  under the null?

8. What proportion of the p_diffs are greater than the actual difference observed in ab_data.csv?

9. What is this value called in scientific studies? What does this value mean in terms of whether or not there is a difference between the new and old pages?

10. What is the p-value associated with ab_page? Why does it differ from the value you found earlier?

11. Why it is a good idea to consider other factors to add into your regression model. Are there any disadvantages to adding additional terms into your regression model?

12. Does the country in which users live appear to have an impact on conversion rates?

13. What is the interaction between the country in which a user resides and the page to which they were exposed?

**D. Key Findings**
