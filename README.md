# Dissertation-Federated-Learning

About Dataset:
The dataset was sourced from a publicly available data source and was selected due its comprehensive and varied set of financial features that are relevant to the business use case. It contains a total of 32,000 rows and 9 features/dimensions.

The dataset includes key demographic and financial attributes such as age, income, and employment length which are important in determining an individual’s financial stability and their ability to repay the loans. Additionally, the dataset also provides information about the loan specific characteristics such as loan amount, interest rate of the loan, and the percentage of income allocated to the loan payments, which are directly related to the loan attributes and performance. The unique feature of this data is that it also includes the previous default history of an individual which is crucial as it offers valuable insights into their credit behaviour. In addition to these features, this dataset also accounts for home ownership statuses. By utilizing Federated Learning, we can leverage this rich dataset while ensuring privacy and security of the data. This makes it an ideal choice for the project enabling predictive analytics capabilities and mitigate default risks effectively when used by businesses.

About Federated Learning Implementation:

The Federated Learning system has been implemented using two methods:
1) Flower framework: Using a pre-built framework for federated learning, to simulate training of binary classification model using Logistic Regression.
2) Custom code: A custom-built federated learning model to simulate training of binary classification model using a TensorFlow Keras Neural Network model with 11 inputs, a hidden layer with 8 nodes, and one output layer.
