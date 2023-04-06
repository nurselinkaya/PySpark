## Fraud Detection using PySpark and Random Forest Classifier
This code implements a fraud detection system using PySpark and Random Forest Classifier. The data used is the credit card fraud detection dataset from Kaggle.

### Requirements
PySpark 2.4.0 or higher

Python 3.5 or higher

pandas

### Usage
To run this code, first make sure you have all the requirements installed. Then follow these steps:

- Download the dataset from Kaggle and place it in the input folder as "../input/creditcardfraud/creditcard.csv".
- Open the Jupyter Notebook or Python editor and run the code.
- The code will output the accuracy of the model for fraud detection.
### Code Overview
The code is divided into the following sections:

#### Import Libraries and Dataset
In this section, we import the necessary libraries and the dataset required to implement the fraud detection system using PySpark and Random Forest Classifier.

#### Data Preprocessing
In this section, we convert the data types of the columns to double and drop any missing values.

#### Model Training
In this section, we use PySpark's Random Forest Classifier to train the model on the preprocessed data.

#### Model Evaluation
In this section, we evaluate the model using MulticlassClassificationEvaluator from PySpark.

#### Conclusion
This code implements a fraud detection system using PySpark and Random Forest Classifier with an accuracy score for the model. This code can be used as a starting point for developing more sophisticated fraud detection systems.
