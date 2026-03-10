# PedsNutrition
Group project: Building an A-Z Reproducible Pipeline for Precision Nutrition Analysis
Project objectives:
For this project, you will be asked to design and execute a reproducible precision nutrition project that:
1.Follows all steps of CRISP-DM framework
2.Applies growth analysis methods
3.Follows the principles of transparent and reproducible workflows
4.Produces an interpretable precision nutrition insight or conclusions

You will work in groups of 3-4 students and you will be asked to define a precision nutrition research question. Each week corresponds to one stage of the project. You will have structured in-class work time with instructor feedback.

Dataset:
The dataset intentionally includes missing data, implausible age values, outliers in zBMI. Identifying and handling these issues is part of the assignment.
The data that you will need can be accessed here.
The code that you can use for your assignment can be found here.
You can modify the code provided, but you should save a copy with your changes.
Requirements:
Each student must:
•Create a GitHub account at https://github.com
•Join a group repository (one per group)
•Contribute commits (visible contribution history required)
•Groups must submit a link to their repository.

Repositories can be public or private and shared with instructor.

Detailed description:
1. Scientific Understanding
You must define:
•The research question
•The outcome variable
•Why this question matters biologically and/or clinically
•Who the target population is
2. Data Understanding
•Describe the dataset structure
•Identify variable types and values
•Identify missingness patterns
•Explore outliers
3. Data Preparation
•Clean growth data using WHO cut-offs (if applicable)
•Handle implausible age values
•Decide how to treat outliers
•Decide how to handle missing data (complete case, imputation, etc.)
•Document your decision
4.Growth Analysis Component can be used as step 4&5-Modeling and Evaluation and in addition provide a statistical analysis plan if necessary for assessing your research question
5.Discuss deployment & implementation considerations:
•Could this model realistically be used in practice?
•What are ethical implications?
•What are the risks of misuse?

Example:
Evaluate whether zBMI patterns at 24 months are associated with systemic inflammation measured by C-reactive protein (CRP).
Exposure: zBMI trajectory patterns - Outcome: CRP concentration (mg/L)

Data Cleaning Strategy: Remove implausible age values, apply WHO cut-offs to identify implausible zBMI values, examine CRP for extreme outliers, log-transform CRP if skewed, assess missingness patterns.

Statistical Modeling: Linear regression, check assumptions (eg linearity, residual normality, homoscedasticity, multicollinearity).

Evaluation: RMSE, R²

Interpretation-Implementation: Adiposity and low-grade inflammation, Could zBMI screening identify children at risk of chronic inflammation?
