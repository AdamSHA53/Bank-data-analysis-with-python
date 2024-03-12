# Bank-data-analysis-with-python
## Overview
This project focuses on analyzing a dataset containing bank customer data, including information such as job, marital status, age, balance, and other basic details. The analysis aims to gain insights into customer behavior and preferences, as well as to build predictive models for classification tasks such as customer segmentation and prediction of subscription to a term deposit.

## Dataset
The dataset used in this project is stored in a CSV file and contains the following columns:
- `Job`: Occupation of the bank customer.
- `Marital`: Marital status of the customer (married, single, divorced).
- `Age`: Age of the customer.
- `Balance`: Balance in the customer's account.
- `Education`: Level of education of the customer (e.g., primary, secondary, tertiary).
- `Housing`: Housing loan status of the customer (yes/no).
- `Loan`: Personal loan status of the customer (yes/no).
- `Contact`: Type of communication contact with the customer (telephone, cellular, unknown).
- `Day`: Day of the month when the contact was made.
- `Month`: Month of the year when the contact was made.
- `Duration`: Duration of the last contact in seconds.
- `Campaign`: Number of contacts performed during this campaign for this customer.
- `Pdays`: Number of days that passed by after the client was last contacted from a previous campaign (-1 means client was not previously contacted).
- `Previous`: Number of contacts performed before this campaign for this customer.
- `Poutcome`: Outcome of the previous marketing campaign (failure, nonexistent, success).

## Analysis
The analysis includes the following steps:

### Exploratory Data Analysis (EDA)
- Data Cleaning: Handling missing values, removing duplicates, and correcting data types.
- Summary Statistics: Calculating descriptive statistics such as mean, median, and standard deviation.
- Data Visualization: Creating visualizations such as histograms, box plots, and scatter plots to explore the distribution and relationships between variables.

### Machine Learning Models
The following machine learning techniques were applied to the dataset:

- Clustering: Using algorithms such as K-means clustering to identify groups of customers with similar characteristics.
- Support Vector Machines (SVM): Building a classifier to predict customer subscription to a term deposit.
- Decision Trees: Constructing decision trees to understand factors influencing customer behavior and decision-making.
- Random Forests: Building an ensemble of decision trees for improved predictive performance.
- AdaBoost: Applying adaptive boosting to enhance the performance of weak learners.

### Results
- (Include key findings and insights from the analysis)
- (Summarize performance metrics for each machine learning model)
- (Highlight any significant patterns or trends identified)

## Usage
To reproduce the analysis or explore the dataset further, follow these steps:
1. Download the dataset file (`bank_data.csv`) from [https://www.kaggle.com/datasets/prakharrathi25/banking-dataset-marketing-targets].
2. Load the dataset into your Python environment using libraries such as Pandas.
3. Apply the provided analysis techniques using Python code and libraries such as Matplotlib, Seaborn, Scikit-learn, etc.
4. Modify and customize the analysis according to your specific requirements or questions of interest.

## Contributors
- [Your Name](https://github.com/your_username): Project lead and primary contributor.

## License
This project is licensed under the [MIT License](LICENSE).
