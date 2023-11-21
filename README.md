<!DOCTYPE html>
<html>
<head>
  <style>
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      color: #333;
    }
    h1 {
      font-family: 'Times New Roman', Times, serif;
      color: #2e6da4;
      border-bottom: 2px solid #2e6da4;
      padding-bottom: 5px;
    }
    h2 {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      color: #4cae4c;
    }
    h3 {
      font-family: 'Arial Black', Gadget, sans-serif;
      color: #d9534f;
    }
    p {
      font-size: 16px;
    }
    ul {
      list-style-type: circle;
    }
    pre {
      background-color: #f5f5f5;
      padding: 10px;
      border-radius: 5px;
    }
    img {
      max-width: 100%;
      height: auto;
      display: block;
      margin: 20px 0;
      box-shadow: 0 0 5px rgba(0, 0, 0, 0.3);
    }
  </style>
</head>
<body>

<h1><img src="IMG/logo.png" alt="House Logo" height="50"> House Sale Price Prediction</h1>

<h2>Data Preprocessing</h2>
<p>
  This project focuses on predicting house sale prices. Below are the steps taken for data preprocessing:
</p>

<h3>Step 1: Installation of Required Libraries</h3>
<p>
  The initial step involves installing necessary libraries from the <code>requirements.txt</code> file.
</p>

<h3>Step 2: Data Cleaning</h3>
<p>
  The dataset stored in the "DATA" folder as <code>sample_dataset.csv</code> underwent thorough cleaning. Steps included outlier removal, handling duplicate entries, and eliminating unwanted columns.
</p>

<h3>Step 3: Preprocessed Data</h3>
<p>
  Post-cleaning, the preprocessed data was saved as <code>preprocessed_data.csv</code> in the "DATA" folder.
</p>

<h3>Step 4: Data Splitting</h3>
<p>
  The dataset was split into training and testing sets (<code>X_train</code>, <code>y_train</code>, <code>X_test</code>, <code>y_test</code>), which were stored in NumPy data format in the "DATA" folder.
</p>


<h2>Regression Model Training</h2>
<p>
  For regression model training, the following steps were undertaken:
</p>

<h3>Step 1: Regression Models and Metrics</h3>
<p>
  In the <code>Task 2_Regression.ipynb</code> file within the "Code" folder, regression models were implemented, and metrics such as MAE, MSE, RMSE, R2 Score, and RMSE (Cross-Validation) were evaluated.
</p>

<!-- Rest of your content -->

</body>
</html>
