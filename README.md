


INTERVIEW QUESTION ANSWERS 

1. **What are the different types of missing data?**

MCAR (Missing Completely at Random) Missingness is entirely random and not related to any observed or unobserved data.
MAR (Missing at Random): Missingness depends on some observed data but not the missing values themselves.
MNAR (Missing Not at Random): Missingness depends on the missing values themselves.


2How do you handle categorical variables?

* **Label Encoding** — assign each category a number (good for ordinal variables).
* **One-Hot Encoding** — create binary columns for each category (good for nominal variables with no order).



 3.What is the difference between normalization and standardization?

Normalization (Min-Max scaling):Scales data into a range like \[0,1].
Standardization (Z-score scaling): Scales data so it has mean 0 and standard deviation 1.

 4. H0W do you detect outliers?

Visual methods — boxplots, scatter plots.
  Statistical methods — using IQR (values outside 1.5 \* IQR), or Z-scores (values with absolute Z-score > 3).

5.Why is preprocessing important in ML?

 It improves data quality, removes noise, handles missing values, and scales features, helping the model train faster and perform better.



 6. What is one-hot encoding vs label encoding?

One-hot encoding — converts a categorical column into multiple binary columns.
Label encoding — converts categories into integer labels (can introduce unintended ordinal relationships).

 7. How do you handle data imbalance?
Resampling Techniques — Oversampling minority class, undersampling majority class.
Synthetic Techniques — SMOTE to generate synthetic samples.
Algorithm-level approaches — Adjusting class weights or using specialized metrics (e.g. F1-score).


 8.Can preprocessing affect model accuracy?

Yes. Proper handling of missing data, encoding of categories, scaling of features, and removing outliers all improve model accuracy and convergence. Poor preprocessing can introduce bias and reduce model performance.



