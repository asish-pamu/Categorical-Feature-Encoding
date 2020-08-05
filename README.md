#Categorical-Feature-Encoding
Encoding the categorical data (binary, nominal, ordinal) for binary classification for a synthetically created dataset. 

Data Description:
The data contains binary features (bin_*), nominal features (nom_*), ordinal features (ord_*) as well as (potentially cyclical) day (of the week) and month features. The string ordinal features ord_{3-5} are lexically ordered according to string.ascii_letters
We are provided with 3 datasets, i.e., training dataset, test dataset and sample submission dataset.Training dataset consist of 600,000 records and test datasets consist of 400,000 records.
Both training and test dataset contains 25 features that include
•	1 id variable
•	5 binary features
•	5 low- and 5 high-cardinality nominal features
•	3 low- and 3 high-cardinality ordinal features
•	2 cyclical features namely day, month
•	1 target variable
