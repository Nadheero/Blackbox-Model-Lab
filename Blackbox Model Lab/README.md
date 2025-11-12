# __Blackbox Model Lab: Loan Approval__

## __Information__

In this lab, you will apply ensemble learning techniques to predict loan approval outcomes using a structured dataset. The dataset includes demographic, financial, and credit history features, with the target variable `loan_status` indicating whether a loan was approved (1) or rejected (0). Your task is to explore the data through EDA, clean and preprocess it as needed, and build predictive models using **two** of the following methods: **Bagging**, **Random Forest**, or **Boosting**.

You are expected to document your workflow using markdown, including insights from your EDA, preprocessing decisions, and modeling rationale. After training both models, evaluate their performance using relevant metrics such as accuracy, precision, recall, F1-score, and confusion matrix. Conclude with a comparative analysis of the two models, discussing which performed better and why. This lab emphasizes not only technical execution but also clear communication of your process and findings.


## __Data Dictionary__
| Column                          | Description                                             | Type        |
|----------------------------------|---------------------------------------------------------|-------------|
| person_age                       | Age of the person                                       | Float       |
| person_gender                    | Gender of the person                                    | Categorical |
| person_education                 | Highest education level                                 | Categorical |
| person_income                   | Annual income                                           | Float       |
| person_emp_exp                   | Years of employment experience                          | Integer     |
| person_home_ownership            | Home ownership status (e.g., rent, own, mortgage)       | Categorical |
| loan_amnt                        | Loan amount requested                                   | Float       |
| loan_intent                      | Purpose of the loan                                     | Categorical |
| loan_int_rate                    | Loan interest rate                                      | Float       |
| loan_percent_income              | Loan amount as a percentage of annual income            | Float       |
| cb_person_cred_hist_length       | Length of credit history in years                       | Float       |
| credit_score                     | Credit score of the person                              | Integer     |
| previous_loan_defaults_on_file  | Indicator of previous loan defaults                     | Categorical |
| loan_status (target variable)    | Loan approval status: 1 = approved; 0 = rejected        | Integer     |

