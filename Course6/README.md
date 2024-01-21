# Course 6: The Nuts and Bolts of Machine Learning

This course covers the fundamentals of supervised machine learning, and introduces learners to unsupervised learning through K-means and other clustering models. Learners will use different classification techniques such as decision trees, random forests, and gradient boosting to approach a realistic business problem. 

Dataset columns explanation

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
