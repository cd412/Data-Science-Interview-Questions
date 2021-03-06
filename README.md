# Data-Science-Interview-Questions
Please add to this list! Questions will be added regularly

(Also, do not post questions that are not allowed to be shared)

## Statistics
* What are the attributes of a normal distribution?
    * Symmetrical bell-shaped curve
    * Mean = Median = Mode
    * The 68-95-99.7 (empirical) rule
    * SOURCE: https://en.wikipedia.org/wiki/Normal_distribution
    
* What is four attributes of a good estimator?
    * Unbiassedness - expected value is equals the population parameter being estimated
    * Consistency - an estimator, approaches the parameter closer and closer as the sample size n increases
    * Efficiency - the variance of the estimator is small
    * Sufficiency - the estimator conveys as much information as is possible about the parameter. No additional information can improve the estimate
    * SOURCE: John E. Freund's Mathematical Statistics with Applications (8th Edition)
    * SOURCE: http://www.tutorhelpdesk.com/homeworkhelp/Statistics-/Properties-Of-Good-Estimator-Assignment-Help.html
    
## Programming
* How do you select all records from a table in SQL?
    * `SELECT * FROM table_name;`
    * SOURCE: https://www.tutorialspoint.com/sql/sql-select-query.htm
    
* What is the meaning of inheritance in object oriented programming?
    * "is-a" relationship
    * New objects by directly acquiring the attributes and behaviors of other objects and then extending or specializing them. 
    * For example, `mountain_bike` inherits from `bicycle`
    * SOURCE: https://www.learncpp.com/cpp-tutorial/111-introduction-to-inheritance/

## Data Science 
* How do you handle missing values in an input variable?
    * Impute based on the mean, median, mode, or logical reasoning
    * Impute based on a predictive model
    * Eliminate the records if there are a small number of missing values
    * Eliminate the column if there are a large number of missing values or the column is not significant
    * SOURCE: https://towardsdatascience.com/how-to-handle-missing-data-8646b18db0d4
    
* What are the assumptions about input variables when doing linear regression?
    * Weak exogeneity - predictor variables are fixed and are not random variables
    * Linearity - response variable is a linear combination of the regression coefficients and the predictor variables
    * Constant variance (a.k.a. homoscedasticity) - variance does not increase as input variables increase; no fanning in residuals
    * Independence of errors
    * No multicolinearity - input variables cannot be perfectly correlated with each other
    * SOURCE: https://en.wikipedia.org/wiki/Linear_regression#Assumptions

* What is the F-Score metric in a classification problem?
    * The harmonic mean of the precision and recall.
    * F-Score = (2 * recall * precision) / (recall + precision)
    * This makes it possible to compare models with low precision and high recall or vice versa.
    * SOURCE: https://towardsdatascience.com/understanding-confusion-matrix-a9ad42dcfd62
    
