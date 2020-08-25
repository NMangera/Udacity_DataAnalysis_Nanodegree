# Communicate Data Findings

The final project focuses on the visualization of data. Topics include chart junk, use of color, data/ink ratio, the lie factor, and other encodings.

 **A. Determine Objectives**

The task is to analyse data pertaining to loans made on the p2p lender platform Prosper, using visualuisation to aid the exploration of interest rate determination.

**B.  Outline of Steps**

1. Decide what questions to pose

2. Extract the data  

3. Import data into environment  

4. Create visualisations to aid and augment exploration 

5. Draw conclusions

**C. What Question(s) To Ask?** 

The main research question is stated as:

What affects a borrower’s APR or interest rate?

**D. Key findings**

Considered individually, the majority of the numerical features investigated are weakly correlated with borrower APR. That being said, the categorical features Credit Grade & Prosper Score did appear to correlate with borrower APR, with higher ranked categories suggestive of a lower rate of interest. Given Credit Grade & Prosper Score are a composite (index) of the other variables, and are used to determine borrower APR, the result appears plausible.

The length of a loan (Term) also affects borrower APR, with shorter loans exhibiting lower interest rates.

Surprisingly, the variable DebtToIncomeRatio has a low correlation with borrower APR. The feature also contains outliers, which when exploring was truncated to gain an understanding of the bulk of distribution, and on closer inspection, appears to be a normal distribution with a slight skew.
