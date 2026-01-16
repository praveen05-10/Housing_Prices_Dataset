# Housing_Prices_Dataset
The dataset is first loaded and checked to understand its size, structure, and data types.
Missing values are identified in each column to understand data quality issues.
A visual inspection is done using a bar chart to see which features contain missing data and their severity.
Numerical columns with missing values are handled by replacing them with the median value to avoid the effect of outliers.
Categorical columns with missing values are handled by replacing them with the most frequent value (mode).
Columns that contain extremely high percentages of missing values are removed because they do not contribute meaningful information.
The dataset is validated again to ensure no missing values remain.
The final cleaned dataset is compared with the original to confirm improvement in data quality without losing important records.
