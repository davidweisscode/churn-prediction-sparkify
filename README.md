# churn-prediction-sparkify
Machine learning project modeling user churn of a hypothetical music streaming service

Data Science Nanodegree - Capstone Project: PySpark
Customer Churn Prediction for the Sparkify Music Streaming Service

Head over to Medium to read my blogpost at

https://davidweisspost.medium.com/churn-prediction-with-pyspark-52ddece92ba4

The Capstone project for [Udacity's Data Scientist Nanodegree](https://www.udacity.com/course/data-scientist-nanodegree--nd025). This project involves predicting **Customer Churn for a hypothetical music streaming app Sparkify**, using Spark's MLlib to engineer features and build a classification model. The dataset used here is a medium-sized (248 MB, with 544,000 rows) version of the whole dataset (which is 12 GB). <br>
This project is worked on [IBM Cloud's Watson Studio](https://www.ibm.com/se-en/cloud/watson-studio), uploading the data cluster, with a Python 3.7/Spark 3.0 enabled Jupyter Notebook. <br>

Using `pyspark`, the project broadly involves the following:

- Loading and cleaning the data
- Exploratory Data Analysis
- Feature Engineering - appropriate features are selected based on the EDA
- Modelling - two different classification models are tested and evaluated
- Model Tuning - Hyperparameter tuning using grid search
- Concluding Remarks

## <a name="installations"></a> Installation

- Python 3.6+
- `pyspark.*`
- Jupyter - available through [this link](https://jupyter.org/install), or IBM Watson Studio (Lite)
