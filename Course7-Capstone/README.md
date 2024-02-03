# Course 7: Google Advanced Data Analytics Capstone

**Salifort Motors Workforce Analysis: Employee Turnover Forecast**

## Background Infomation

Salifort Motors is a fictional French-based alternative energy vehicle manufacturer. Its global workforce of over 100,000 employees research, design, construct, validate, and distribute electric, solar, algae, and hydrogen-based vehicles. Salifort’s end-to-end vertical integration model has made it a global leader at the intersection of alternative energy and automobiles.

As a data specialist working for Salifort Motors, you have received the results of a recent employee survey. The senior leadership team has tasked you with analyzing the data to come up with ideas for how to increase employee retention. To help with this, they would like you to design a model that predicts whether an employee will leave the company based on their department, number of projects, average monthly hours, and any other data points you deem helpful.

---

## Decision tree

Although I had used the `plot_tree()` function to draw the tree inside the notebook, but the graphviz version is also available. The document is uploaded [here](./decision_tree). If you are interested, go to [Graphviz Online](https://dreampuf.github.io/GraphvizOnline/), paster all the text, and you should see a well-constructed decision tree. 

### Example output: 
![](./graphviz.svg)
Download image [here](./graphviz.svg).

## Versions

This project has been approached with two distinct analytical versions to enhance the robustness of our insights and recommendations.

**Basic Analysis (Version 1):** Utilizing a single Decision Tree model, established a foundational understanding of the factors contributing to employee turnover. This model served as a starting point, offering initial clarity on key variables and their impact.

**Advanced Analysis (Version 2):** Building upon the basic analysis, implemented Random Forest and XGBoost models to refine our predictive accuracy. These advanced models leveraged ensemble learning and gradient boosting respectively to capture more complex patterns in the data, providing a deeper and more nuanced understanding of turnover drivers.

## Insights

### Suggestions/Recommendations

- **Refine Workload Management:** Balance workloads across all models and ensure that no employee consistently endures excessive hours. This is crucial since all models indicate a link between high average monthly hours and turnover.
- **Foster Professional Growth:** Strengthen career advancement frameworks to provide clear and attainable growth opportunities. Our analysis across all models confirms that lack of promotion is a strong turnover predictor.
- **Boost Job Satisfaction and Performance:** Develop programs to increase job satisfaction and address performance-related issues, as highlighted by the decision tree model. The insights from the more complex RF and XGB models support these findings and suggest that deeper, more nuanced factors may also play a role.
- **Project Allocation Scrutiny:** Monitor the number of projects assigned to employees. The decision tree model identified a higher project count as a risk factor for turnover, a pattern that was less pronounced but still observable in RF and XGB models.

### Conclusion

The comparative analysis of the decision tree, random forest, and XGBoost models underscores several key factors influencing employee turnover. While the decision tree offered foundational insights, the RF and XGB models unveiled a richer, more detailed landscape of turnover predictors. The nuanced differences between these models suggest that a multi-faceted approach to retention strategies might be necessary, considering not only the quantity but also the quality and complexity of workload and career development opportunities.

### Feedback

The collective findings from the three models offer a robust starting point for strategic interventions. However, it is vital to recognize the limitations inherent in quantitative models and the need for human judgment in interpreting these results. Integrating quantitative insights with qualitative feedback will provide a more holistic view of employee turnover. It is also recommended to maintain a dynamic approach to retention strategies, revisiting and revising them regularly to adapt to an evolving workforce and organizational context.

---

## Dataset columns explanation

*Note: Some column names could be better; I replaced some columns with better ones. Typically, 0 means False/No, and 1 means True/Yes.*


| Column name               | Type  | Description                                                  |
|---------------------------|-------|--------------------------------------------------------------|
| satisfaction_level        | int64 | The employee’s self-reported satisfaction level [0-1]        |
| last_performance_rating   | int64 | Score of employee's last performance review [0-1]            |
| number_of_projects        | int64 | Number of projects the employee contributes to               |
| avg_monthly_hours         | int64 | Average number of hours the employee works per month         |
| years_at_company          | int64 | How long the employee has been with the company (years)      |
| had_work_accident         | int64 | Whether the employee had an accident at work (yes or no)     |
| has_left_company          | int64 | Whether the employee has left the company (yes or no)        |
| promoted_in_last_5_years  | int64 | Whether the employee was promoted in the last 5 years        |
| department                | str   | The department where the employee works                      |
| salary_level              | str   | The salary category of the employee (low, medium, or high)   |

## Answer Key

[Exemplar](./Exemplar_%20Course%207%20Salifort%20Motors%20project%20lab.ipynb) provided by Google also uploads. 



