# DataMining_Coursework
This is my MSc's Data Mining subject's Course work


**Question 1: Regression**
**Dataset**

The provided dataset contains the salaries of different Data Science job roles in different
companies in different regions.
The feature in the dataset are:
work_year: The year the salary was paid.
experience_level: The experience level in the job during the year
employment_type: The type of employment for the role
job_title: The role worked in during the year.
salary: The total gross salary amount paid.
salary_currency: The currency of the salary paid as an ISO 4217 currency code.
salaryinusd: The salary in USD
employee_residence: Employee's primary country of residence in during the work year as an ISO
3166 country code.
remote_ratio: The overall amount of work done remotely
company_location: The country of the employer's main office or contracting branch
company_size: The median number of people that worked for the company during the year


**Task**

Your task is to use this dataset to predict the salary of a data science role in USD given a set of
features. While you achieve this task, you need to address the following sub tasks.
1. Perform EDA (Explotary Data Analysis) on the dataset provided
2. Identifying required features and the output
3. Missing value imputation
4. Outlier detection and removal
5. Feature selection or feature extraction as demanded by the data
6. Normalization
7. Building at two ML models that are capable of predicting the salary. You need to optimize
these models individually using techniques like hyper-parameter tuning, regularization etc.
8. All the models have to be evaluated using suitable evaluation techniques.





**Question 2: Clustering
Dataset**


You are given the data for years 2015 and 2019 from World Happiness Report which includes
various socio-economic and well-being indicators that help measure the happiness level of countries.
Below is a brief description of its key features:
Country: Name of the country.
Happiness Score: A measure of overall happiness on a scale from 0 to 10, based on survey
responses.
GDP per Capita: Economic output per person, adjusted for purchasing power.
Social Support: The perceived availability of social networks and support in times of need.
Healthy Life Expectancy: Average number of years a person is expected to live in good health.
Freedom to Make Life Choices:Perceived ability of individuals to make their own life decisions.
Generosity: The tendency of people in the country to donate to charities or help others.
Perceptions of Corruption: Level of trust in government and business, with higher values
indicating greater corruption concerns.
Dystopia Residual: A theoretical benchmark that accounts for unexplained variations in happiness
across countries.

**Task**


1. Perform Exploratory Data Analysis (EDA) to understand patterns and detect anomalies.
2. Outlier Detection and Removal (if required) by identifying and handling numerical outliers.
3. Feature Scaling and Transformation through normalization or standardization for
consistency.
4. Clustering Model Development by implementing K-Means clustering for 2015 and 2019
and optimizing hyperparameters.
5. Cluster Evaluation using suitable metrics to assess clustering performance.
6. Model Drift Analysis by comparing clusters across different years to detect structural
changes.
a. Measure centroid shifts and cluster membership changes over time.
b. Use Kullback-Leibler (KL) Divergence or other suitable metrics to quantify drift.
7. Visualization of Results using PCA for dimensionality reduction and plotting cluster
changes over time.
8. Conclusion and Insights by summarizing findings, explaining cluster variations, and
linking them to socio-economic trends.
