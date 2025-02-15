# Stellar Classification (SDSS17)
## Abstract
Stellar classification is a fundamental process in astronomy that is used to categorize stars based on their spectral characteristics.
In this study, supervised machine learning algorithms are implemented to solve the stellar classification, which is a multiclass classification problem, using Knime Analytics Platform. Therefore, classification models were developed in order to decide whether an astronomical object is a Star, Galaxy or Quasar. 
To achieve this, the project deals with the class imbalance problem, and the understanding of the most important features, using feature selection approaches. 
The performance is then evaluated to find the optimal classification algorithm that would be used to classify stellar objects.

## Details
- This project has been developed for the Master’s Degree in Data Science @ UniMiB.
- The dataset selected to address our goal is the “Stellar Classification Dataset - SDSS17”, available on [Kaggle](https://www.kaggle.com/datasets/fedesoriano/stellar-classification-dataset-sdss17).
- The platform used is KNIME Analytics Platform, a free and open source data analytics, reporting and integration platform, which ensures users remain on the bleeding edge of data science. KNIME integrates various components for machine learning and data mining through its modular data pipelining "Building Blocks of Analytics" concept.
- Classification models: XGBoost, Random Forest, kNN, J48 Decision Tree, Logistic Regression, Naive Bayes, Multi-Layer Perceptron, Support Vector Machine (SMO).
- The performance is evaluated in terms of Accuracy, Precision, Recall, F1 measure and ROC-Curve.
- Feature selection is implemented using both univariate and multivariate filters, and wrapper too.
