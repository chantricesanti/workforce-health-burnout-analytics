# Workforce Health and Burnout Analytics

This project analyzes how post-pandemic work arrangements relate to employee burnout, social isolation, job satisfaction, and overall well-being. Using the **Post-pandemic Remote Health Impact Survey 2025** dataset from Kaggle, the analysis explores whether remote, hybrid, and onsite work environments differ in their effects on burnout risk and employee thriving.

## Dataset

The dataset contains **3,157 employee survey records** collected in **June 2025**. It includes information on work arrangement, burnout level, work-life balance, social isolation, mental health status, physical health issues, hours worked per week, job role, industry, region, salary range, age, and gender.

## Project Objectives

- Identify which factors most strongly predict employee burnout level
- Evaluate whether work arrangement is associated with burnout risk
- Analyze how remote, hybrid, and onsite work arrangements relate to social isolation and work-life balance
- Examine whether job satisfaction changes differently across burnout levels as working hours increase
- Identify factors associated with employee thriving

## Methods

The analysis uses a mix of statistical modeling, feature selection, and exploratory analysis methods, including:

- Feature selection
- L1 regularization
- Mutual information
- Random forest feature importance
- Wilcoxon rank-sum tests
- Spearman correlation
- Chi-square tests of independence
- Kruskal-Wallis tests
- Post-hoc Dunn tests
- Ordinal logistic regression
- Logistic regression
- Polynomial interaction modeling
- Data visualization

## Key Findings

Work arrangement was one of the strongest and most consistent predictors of burnout risk. Remote employees showed the highest likelihood of burnout risk, while onsite employees showed the lowest, with hybrid employees falling between the two. Social isolation also showed a meaningful relationship with burnout, although its effect was weaker than work arrangement.

The analysis also found that work-life balance scores were relatively similar across remote, hybrid, and onsite employees, while social isolation differed significantly by work arrangement. Remote workers reported the highest levels of isolation, hybrid workers reported moderate levels, and onsite workers reported the lowest levels.

For job satisfaction, the effect of working hours depended on burnout level. Low-burnout employees tolerated longer hours better, while high-burnout employees showed declining satisfaction as hours increased. This suggests that organizations should avoid one-size-fits-all workload policies and instead consider burnout-responsive approaches to work design.

## Tools

- R
- Statistical modeling
- Data visualization
- Regression analysis
- Survey data analysis

## Project Role

I implemented the analysis for Research Question 1, which examined which factors most strongly predicted employee burnout level. I applied feature selection and statistical validation methods including L1 regularization, mutual information, random forest feature importance, Wilcoxon rank-sum tests, Spearman correlation, and ordinal logistic regression to identify the most consistent predictors of burnout.
