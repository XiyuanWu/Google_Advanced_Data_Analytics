# Course 4: The Power of Statistics

Learn descriptive and inferential statistics, basic probability and probability distributions, sampling, confidence intervals, and hypothesis testing.

## Course 4 content

**Module 1: Introduction to statistics**

In this section of the course, you’ll learn about the foundational role of statistics in data science. This section focuses on fundamental concepts of descriptive statistics, such as measures of central tendency, dispersion, and position. 

**Module 2: Probability**

You will learn about fundamental concepts in probability. The first half of this section covers basic rules of probability (complement, addition, multiplication), conditional probability, and Bayes's theorem. The second part concentrates on three probability distributions: the binomial, Poisson, and normal distributions. 

**Module 3: Sampling**

In this section of the course, you’ll learn about the concept of sampling and its applications in data work. The section begins with an overview of inferential statistics and the relationship between sample and population. This is followed by a summary of the sampling process, and the benefits and drawbacks of specific sampling methods. You’ll also learn about sampling distributions for both means and proportions.

**Module 4: Confidence intervals**

This section explores how data professionals use confidence intervals to describe the uncertainty in their estimates. First, you’ll get an overview of the general procedure for constructing a confidence interval. This is followed by an explanation of how to properly interpret a confidence interval. Finally, you’ll be presented with detailed examples of how to construct a confidence interval for both means and proportions. 

**Module 5: Introduction to hypothesis testing**

This section of the course describes how data professionals use hypothesis testing to help determine whether their results are statistically significant. First, you’ll get an overview of the general procedure for conducting a hypothesis test, and guidelines for interpreting the results. Then, you’ll examine detailed examples of how to conduct both one-sample and two-sample tests. 

**Module 6: Course 4 end-of-course project**

In this section of the course, you will produce a tangible artifact that you can add to your professional portfolio and present to future employers. For this project, you will use your knowledge of statistics to conduct a statistical test that’s based on a workplace scenario. 

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
