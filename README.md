<!DOCTYPE html>
<html>
<head>
    <title>Marketing Campaign Effectiveness</title>
</head>
<body>

<h1>Marketing Campaign Effectiveness</h1>

<p>This repository contains code and analysis for assessing the effectiveness of a marketing campaign conducted by a Portuguese banking institution. The goal is to predict whether a client will subscribe to a term deposit based on direct marketing campaign data.</p>

<p>To access the Jupyter Notebook, follow the link below:</p>
<a href="https://github.com/fcely/MLClassifiers/tree/main/prompt.ipynb">Jupyter Notebook</a>


<h2>Table of Contents</h2>
<ul>
    <li><a href="#introduction">Introduction</a></li>
    <li><a href="#data-collection">Data Collection</a></li>
    <li><a href="#exploratory-data-analysis">Exploratory Data Analysis</a></li>
    <li><a href="#correlation-analysis">Correlation Analysis</a></li>
    <li><a href="#data-preparation">Data Preparation</a></li>
    <li><a href="#feature-engineering">Feature Engineering</a></li>
    <li><a href="#model-selection-and-hyperparameter-tuning">Model Selection and Hyperparameter Tuning</a></li>
    <li><a href="#model-training-and-evaluation">Model, Training, and Evaluation</a></li>
    <li><a href="#model-interpretation">Model Interpretation</a></li>
    <li><a href="#results">Results</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
</ul>

<h2>Introduction</h2>

<p>The project aims to understand the key variables influencing the success of direct marketing campaigns. It includes data preprocessing, feature engineering, and model selection, including Decision Trees, Logistic Regression, K-Nearest Neighbors, and Support Vector Classifier. The models are evaluated for their accuracy and effectiveness in predicting term deposit subscriptions.</p>

<h2>Data Collection</h2>

<p>The data used in this project was obtained from the University of California Irvine repository using the <code>ucimlrepo</code> library. The dataset includes features related to marketing campaigns and a binary target variable indicating subscription to a term deposit.</p>

<h2>Exploratory Data Analysis</h2>

<p>An initial analysis is performed to gain insights into the dataset, such as success rates, peak subscription months, and the impact of various variables on subscription rates. From this analysis it is identify 12% as the success rate for the population, also some key varaibles like month, duration and education that seem to determine the success rate.</p>

<img src="https://github.com/fcely/MLClassifiers/tree/main/images/Exploratory.png" alt="Exploratory">


<h2>Correlation Analysis</h2>

<p>A correlation matrix is generated to identify relationships between numerical variables and assess multicollinearity.</p>

<img src="https://github.com/fcely/MLClassifiers/tree/main/images/correlation.png" alt="Correlation">

<h2>Data Preparation</h2>

<p>The data is split into training and testing sets. Missing data is imputed, and both numerical and categorical features are preprocessed using appropriate techniques.</p>

<h2>Feature Engineering</h2>

<p>Features are categorized into numerical and categorical. Pipelines are defined for data imputation, encoding, and scaling.</p>

<h2>Model Selection and Hyperparameter Tuning</h2>

<p>Several machine learning models are selected, and hyperparameters are tuned using GridSearchCV to optimize model performance.</p>

<h2>Model, Training, and Evaluation</h2>

<p>Each model is trained, and its performance is evaluated using various metrics, including accuracy, classification reports, and confusion matrices.</p>

<h2>Model Interpretation</h2>

<p>The Decision Tree and Logistic Regression models are visualized to understand feature importance and decision-making processes.</p>

<h2>Results</h2>

<p>The results of each model, including hyperparameters, accuracy, classification reports, and confusion matrices, are presented. The models are compared to determine their effectiveness. It was interesing to see that the accuracy of all models was very close around 89%</p>

<h2>Usage</h2>

<p>To run this code, you'll need Python and the required libraries installed. Use Jupyter Notebook or a code editor to execute the provided code.</p>

<h2>Contributing</h2>

<p>Contributions are welcome! If you have any suggestions or improvements, please feel free to open an issue or submit a pull request.</p>

<h2>License</h2>

<p>This project is licensed under the <a href="LICENSE">FCely License</a>.</p>


</body>
</html>
