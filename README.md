# Dissertation: Building a Homomorphic Encryption enabled Federated Learning model and analysing the effect of incremental data and noise

About Dataset:
The dataset was sourced from a publicly available data source and was selected due its comprehensive and varied set of financial features that are relevant to the business use case. It contains a total of 32,000 rows and 9 features/dimensions.

The dataset includes key demographic and financial attributes such as age, income, and employment length which are important in determining an individual’s financial stability and their ability to repay the loans. Additionally, the dataset also provides information about the loan specific characteristics such as loan amount, interest rate of the loan, and the percentage of income allocated to the loan payments, which are directly related to the loan attributes and performance. The unique feature of this data is that it also includes the previous default history of an individual which is crucial as it offers valuable insights into their credit behaviour. In addition to these features, this dataset also accounts for home ownership statuses. By utilizing Federated Learning, we can leverage this rich dataset while ensuring privacy and security of the data. This makes it an ideal choice for the project enabling predictive analytics capabilities and mitigate default risks effectively when used by businesses.

About Federated Learning Implementation:

The Federated Learning system has been implemented using two methods:
1) Flower framework: Using a pre-built framework for federated learning, to simulate training of binary classification model using Logistic Regression.
2) Custom code: A custom-built federated learning model to simulate training of binary classification model using a TensorFlow Keras Neural Network model with 11 inputs, a hidden layer with 8 nodes, and one output layer. A custom code was developed to study the effect of incremental data and effect of noise on the trained model.

About Dataset files-
There are two dataset files, namely,
1) **credit_risk_dataset.csv** : Raw data file downloaded directly from source (https://www.kaggle.com/datasets/laotse/credit-risk-dataset?select=credit_risk_dataset.csv)
2) **dataset.csv**: Cleaned data file used in Tensorflow code

About Code files-
There are four code files, namely,
1) **EDA** : Exploratory Data Analysis code
2) **Federated learning code - Final.ipynb** : FLower framework code
3) **FE_HL_Updated_13_07_2024_without_noise.ipynb** : Tensorflow code without the effect of noise
4) **FE_HL_Updated_13_07_2024_with_noise.ipynb** : Tensorflow code with the effect of noise
   
