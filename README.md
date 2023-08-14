# PredictingEmployeeProductivity
The garment industry is one of the key examples of the industrial globalization of the modern era.

It is a highly labour-intensive industry with lots of manual processes. Satisfying the huge global demand for garment products is mostly dependent on the production and delivery performance of the employees in the garment manufacturing companies.

So, it is highly desirable among the decision-makers in the garments industry to track, analyze, and predict the productivity performance of the working teams in their factories.

## Data Dictionary
* `date`: Date in MM-DD-YYYY
* `day`: Day of the Week
* `quarter`: A portion of the month. A month was divided into four quarters
* `department`: Associated department with the instance
* `team_no`: Associated team number with the instance
* `no_of_workers`: Number of workers in each team
* `no_of_style_change`: Number of changes in the style of a particular product
* `targeted_productivity`: Targeted productivity set by the Authority for each team for each day.
* `smv`: Standard Minute Value, it is the allocated time for a task
* `wip`: Work in progress. Includes the number of unfinished items for products
* `over_time`: Represents the amount of overtime by each team in minutes
* `incentive`: Represents the amount of financial incentive (in BDT) that enables or motivates a particular course of action.
* `idle_time`: The amount of time when the production was interrupted due to several reasons
* `idle_men`: The number of workers who were idle due to production interruption
* `actual_productivity`: The actual % of productivity that was delivered by the workers. It ranges from 0-1.