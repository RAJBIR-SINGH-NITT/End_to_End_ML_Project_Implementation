# End_to_End_ML_Project_Implementation
An end-to-end ML pipeline predicting the Algerian Forest Fire Weather Index. It covers thorough EDA to clean structural data flaws, feature engineering using standard scaling, and Ridge regression model training. The system features a Flask web application with an HTML frontend for real-time inference, fully ready for cloud deployment.


# Algerian Forest Fires - FWI Prediction Platform

An end-to-end machine learning project that predicts the Fire Weather Index (FWI) for Algerian forest regions using historical meteorological data. This project covers the entire lifecycle from raw data analysis to a fully interactive Flask web application.

# Project Workflow

# 1. Exploratory Data Analysis (EDA)
* Cleaned and preprocessed a dataset tracking forest fire metrics across two Algerian regions.
* Cleaned up structural inconsistencies, including trailing whitespaces in column names and misplaced data rows.
* Handled missing values and cast features into their correct data types.
* Visualized correlations between features to identify key drivers of fire risk.

# 2. Feature Engineering
* Handled categorical components like Classes and Region to make them usable for regression.
* Removed redundant features exhibiting high multicollinearity.
* Used standard scaling to normalize numerical features, ensuring stable and optimal model convergence.

# 3. Model Training & Evaluation
* Trained and compared multiple regression algorithms, including Linear Regression, Lasso, Ridge, and ElasticNet.
* Evaluated performance metrics to ensure accurate prediction capabilities while avoiding overfitting.
* Pickled the top-performing Ridge Regressor alongside the trained StandardScaler for real-time inference.

# 4. Web Application Development
* Built a backend architecture using Flask to serve the prediction pipeline.
* Designed an intuitive HTML frontend containing a structured input form.
* Structured application logic to accept incoming user payloads, scale data points dynamically, and return real-time FWI metrics.

# Tech Stack

* Language: Python
* Machine Learning & Analytics: Scikit-Learn, Pandas, NumPy
* Web Framework:Flask, Jinja2
* Environment Management:Virtualenv
