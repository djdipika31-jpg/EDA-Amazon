Amazon Sales Data Analysis and Order Status Prediction
Project Overview
This project focuses on analyzing Amazon sales data using Python and Machine Learning techniques. The Jupyter Notebook performs Exploratory Data Analysis (EDA) to understand sales patterns, product categories, pricing, customer behavior, and order statuses.

The project includes data preprocessing, missing-value handling, outlier detection, feature engineering, data visualization, and feature selection. A Random Forest Classifier is implemented to predict order status based on available sales and order-related attributes.

The objective is to transform raw sales data into meaningful insights and demonstrate how machine learning can support data-driven decision-making.

Objectives
Perform Exploratory Data Analysis on Amazon sales data.
Understand sales distribution, product categories, and order status patterns.
Handle missing values and identify price outliers.
Apply categorical encoding and feature scaling techniques.
Visualize sales trends and relationships using different charts.
Perform feature engineering and feature selection.
Demonstrate data augmentation and class balancing techniques.
Build a Random Forest classification model for order status prediction.
Evaluate model performance using accuracy, precision, recall, F1-score, and a confusion matrix.
Technologies Used
Technology	Purpose
Python	Data analysis and model development
Pandas & NumPy	Data manipulation and numerical operations
Matplotlib & Seaborn	Data visualization
Plotly	Interactive visualizations
Scikit-learn	Preprocessing and machine learning
imbalanced-learn	Handling class imbalance using SMOTE
NLTK & nlpaug	Text augmentation
Jupyter Notebook	Development environment
Project Workflow
Data Loading and Inspection
Exploratory Data Analysis
Data Cleaning and Preprocessing
Missing Value and Outlier Handling
Data Visualization
Feature Engineering
Feature Selection and Dimensionality Reduction
Data Augmentation and Class Balancing
Random Forest Model Training
Model Evaluation and Feature Importance Analysis
Machine Learning Model
The project uses a Random Forest Classifier to predict the order status.

Target Variable: Status
Train-Test Split: 80% Training and 20% Testing
Number of Estimators: 200
Class Balancing: Balanced Class Weights
Evaluation Metrics: Accuracy, Precision, Recall, F1-Score, and Confusion Matrix
Project Structure
Amazon-Sales-Analysis/
│
├── EDA_Amazon.ipynb
├── amazon_sales_data 2025.csv
└── README.md
How to Run
Clone or download this repository.
Install the required Python libraries.
pip install pandas numpy matplotlib seaborn plotly scikit-learn imbalanced-learn nlpaug nltk
Open EDA_Amazon.ipynb using Jupyter Notebook or Google Colab.
Ensure the Amazon sales dataset is available.
Execute the notebook cells sequentially.
Review the visualizations, analysis results, and model evaluation metrics.
Expected Outcomes
Meaningful insights into Amazon sales data.
Identification of sales patterns and relationships.
Improved understanding of data preprocessing and feature engineering.
A trained machine learning model for order status prediction.
Evaluation results to assess the model's classification performance.
Conclusion
This project demonstrates the application of data analysis and machine learning techniques to Amazon sales data. Through visualization, preprocessing, feature engineering, and classification, the notebook provides a structured approach to understanding sales information and predicting order status. It also serves as a practical implementation of Python-based data science concepts.

