<h1>Telecom Customer Churn Analysis and Prediction</h1>

  <h2>Overview</h2>
    <p>This repository contains code for analyzing and predicting customer churn in a telecom dataset. Customer churn
        refers to the phenomenon where customers switch from one telecommunications service provider to another.
        Predicting churn is crucial for telecom companies to retain customers and sustain their business.</p>

  <h2>Dataset</h2>
    <p>The dataset used in this analysis is available as a CSV file: <code>Telecom-Customer-Churn.csv</code>. It includes
        various features such as customer demographics, contract details, services used, and churn status.</p>

  <h2>Exploratory Data Analysis (EDA)</h2>
    <p>The Jupyter Notebook <code>Telecom_Churn_EDA.ipynb</code> performs exploratory data analysis to understand the
        distribution of variables, identify correlations, and visualize patterns related to churn. The analysis covers
        demographics, contract information, distribution of services, and the interaction of churn with key variables.</p>

  <h2>Predictive Modeling</h2>
    <p>The notebook <code>Telecom_Churn_Prediction.ipynb</code> focuses on predictive modeling using machine learning
        algorithms. The following models are implemented and evaluated:</p>
    <ol>
        <li>Logistic Regression</li>
        <li>Random Forest</li>
        <li>Support Vector Machine (SVM)</li>
        <li>ADA Boost</li>
        <li>XG Boost</li>
    </ol>
    <p>The accuracy, confusion matrix, and feature importance are analyzed for each model.</p>

  <h2>Usage</h2>
    <ol>
        <li>Ensure you have the necessary Python libraries installed: <code>numpy</code>, <code>pandas</code>,
            <code>seaborn</code>, <code>matplotlib</code>, <code>scikit-learn</code>, <code>xgboost</code>.</li>
        <li>Run the Jupyter Notebooks (<code>Telecom_Churn_EDA.ipynb</code> and <code>Telecom_Churn_Prediction.ipynb</code>)
            in a compatible environment.</li>
    </ol>

  <h2>Results and Conclusion</h2>
    <p>The analysis reveals insights into customer churn patterns and provides predictive models to anticipate churn. The
        SVM model achieved the highest accuracy, suggesting its effectiveness in predicting customer churn. Further
        details and observations are documented in the notebook.</p>

