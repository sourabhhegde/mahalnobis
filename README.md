# Mahalnobis Distance
What is Mahalanobis Distance?
Mahalanobis Distance is a multivariate distance metric that measures how far a data point is from the center of a distribution while accounting for correlations between variables and their variances.


# How We Used Mahalanobis Distance in Our Medical Dataset
In our project, we applied Mahalanobis distance to detect outliers in a medical dataset containing vitals and lab results.

Key points:

Features such as height, blood pressure, and lab values were used.

We noticed distributional differences between male and female patients.

So, we computed Mahalanobis distance separately for each gender using gender-specific mean vectors and covariance matrices.

This allowed for more accurate and fair outlier detection, as it respected biological variation across genders.

This approach helped us:

Identify abnormal readings more reliably

Preserve valuable data by avoiding naive deletion of data points


