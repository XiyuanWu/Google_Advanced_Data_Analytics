# Course 5: Regression Analysis: Simplify Complex Data Relationships

In this course, you will apply your knowledge to modeling variable relationships, with a focus on linear regression, analysis of variance (ANOVA), and logistic regression. From model assumptions to evaluation and interpretation, you will understand relationships in datasets based on PACE. 

## Course 5 content

**Module 1: Introduction to complex data relationships**

In this part of the course, you’ll examine how PACE can serve as a solid foundation for regression analysis. Then, you’ll learn about linear and logistic regression, how they’re similar and different, and when to apply each approach. Finally, you’ll use real data to learn how to apply estimation techniques in Python and study more use-cases of regression.

**Module 2: Simple linear regression**

You will explore examples of ordinary least squares estimation in Python and learn the four main model assumptions of simple linear regression: linearity, normality of residuals, independent observations, and homoscedasticity. You’ll build a model in Python and learn how to evaluate model fit using R squared, holdout samples, and measures of uncertainty, like confidence intervals and p-values. Then, you'll begin to develop a story using numbers and statistics and learn how to communicate the results of your simple linear regression model using Python visualizations.

**Module 3: Multiple linear regression**

In this section, you will build on your knowledge of simple linear regression by extending the concepts into multiple regression. You’ll learn how to test assumptions using math, built-in Python functions, and visualizations during the EDA process. Next, you’ll interpret and evaluate multiple regression results, examine the idea of overfitting, and discuss ways to overcome the effects of overfitting using regularization techniques.

**Module 4: Advanced hypothesis testing**

In this part of the course, you’ll examine a variety of hypothesis tests: Chi-squared, ANOVA, ANCOVA, MANOVA, and MANCOVA. You will also investigate null and alternative hypotheses and how they help articulate testing results.

**Module 5: Logistic regression**

You will explore logistic regression models, with a heavy emphasis on binomial logistic regression. You’ll build binomial, multinomial, and ordinal logistic regression models, and log-linear Poisson regression models. Next, you’ll discover important classification model metrics such as ROC and AUC, precision, recall, and type I and type II errors. 

**Module 6: Course 5 end-of-course project**

As you conclude this part of the Advanced Data Analytics Certificate, you will put everything you’ve learned into one end-of-course project. You’ll be tasked with solving a business problem using the provided data. The concepts and skills you will learn in this part of the course will be critical to your success as a data professional.  

**Dataset columns explanation**

| Column name            | Type  | Description                                            |
|------------------------|-------|--------------------------------------------------------|
| ID                     | int   | A sequential numbered index                            |
| label                  | obj   | Binary target variable (“retained” vs “churned”) for if a user has churned anytime during the course of the month |
| sessions               | int   | The number of occurrence of a user opening the app during the month |
| drives                 | int   | An occurrence of driving at least 1 km during the month |
| device                 | obj   | The type of device a user starts a session with        |
| total_sessions         | float | A model estimate of the total number of sessions since a user has onboarded |
| n_days_after_onboarding| int   | The number of days since a user signed up for the app  |
| total_navigations_fav1 | int   | Total navigations since onboarding to the user’s favorite place 1 |
| total_navigations_fav2 | int   | Total navigations since onboarding to the user’s favorite place 2 |
| driven_km_drives       | float | Total kilometers driven during the month                |
| duration_minutes_drives| float | Total duration driven in minutes during the month       |
| activity_days          | int   | Number of days the user opens the app during the month |
| driving_days           | int   | Number of days the user drives (at least 1 km) during the month |
