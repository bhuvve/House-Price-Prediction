<!DOCTYPE html>
<html>
<head>
  <style>
    /* Define custom CSS styles for the README */
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      background-color: #f4f4f4;
      color: #333;
      padding: 20px;
    }
    
    h1 {
      font-size: 36px;
      text-align: center;
      color: #4682b4;
      border-bottom: 2px solid #4682b4;
      padding-bottom: 10px;
      margin-bottom: 20px;
    }
    
    h2 {
      font-size: 28px;
      color: #2e8b57;
      margin-top: 30px;
      margin-bottom: 15px;
    }
    
    p {
      font-size: 16px;
      margin-bottom: 15px;
    }
    
    pre {
      background-color: #f0f0f0;
      padding: 10px;
      border-radius: 5px;
      overflow-x: auto;
    }
  </style>
</head>
<body>

<h1><img src="IMG/logo.png" alt="House Logo" height="50"> House Sale Price Prediction</h1>

<h2>Data Preprocessing</h2>
<!-- Existing preprocessing content here -->

<h2>Regression Model Training</h2>
<p>
  For regression model training, the following steps were undertaken:
</p>

<h3>Step 1: Regression Models and Metrics</h3>
<p>
  In the `Task 2_Regression.ipynb` file within the "Code" folder, regression models were implemented and metrics such as MAE, MSE, RMSE, R2 Score, and RMSE (Cross-Validation) were evaluated.
</p>

<h3>Step 2: Model Evaluation</h3>
<p>
  Various regression models like Linear Regression, Ridge Regression, Lasso Regression, Elastic Net, Support Vector Machines, Random Forest Regressor, XGBoost Regressor were compared based on their performance metrics. See the image 'jpg1' in the "IMG" folder.
</p>

<!-- Add additional steps like ElasticNet model selection, model comparison images, underfitting, overfitting checks, etc. -->

<h3>Step 3: Model Deployment using Streamlit</h3>
<p>
  The selected Elastic Net model with the best parameters was used to create a `model.pkl` file. Additionally, an `app.py` file was created for deployment using Streamlit.
</p>
<p> RUN THE MODEL USING CMD "streamlit run app.py"
</p>

<h2>Visualizations</h2>
<p>Here are some visualizations from the project:</p>

<p>1. Comparison of House Prices and RMSE Cross-Validation score with Elastic Net best params:</p>
<img src="IMG/jpg1.jpg" alt="Visualization 1">

<p>2. Performance metrics of Elastic Net model with best parameters (Decreased RMSE):</p>
<img src="IMG/jpg2.jpg" alt="Visualization 2">

<p>3. Models' RMSE Scores (Cross-Validated) - Descending Order:</p>
<img src="IMG/jpg3.jpg" alt="Visualization 3">

<p>4. Comparison of Elastic Net and Gradient Boosting Regressor:</p>
<img src="IMG/jpg4.jpg" alt="Visualization 4">

<p>5. Underfitting and Overfitting Checks:</p>
<img src="IMG/jpg5.jpg" alt="Visualization 5">


<h2>File Structure</h2>

<pre>
- Code
  - Task 1_Preprocessing.ipynb
  - Task 2_Regression.ipynb
  - app.py
- DATA
  - sample_dataset.csv
  - preprocessed_data.csv
  - X.npy
  - y.npy
  - X_test.npy
  - X_train.npy
  - y_test.npy
  - y_train.npy
- IMG
  - jpg1
  - jpg2
  - jpg3
  - jpg4
  - jpg5
</pre>

<p>
  This README provides an overview of the steps involved in the House Sale Price Prediction project, including data preprocessing, regression model training, evaluation, and deployment using Streamlit.
</p>

</body>
</html>
