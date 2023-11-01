# wine_quality_analysis
Wine Quality Classification

This project is focused on classifying the quality of red wine using machine learning. It's a Python-based project, and here's a simple description of the project:

•	Data Import: The project starts by importing data from an Excel file containing various attributes of red wine.

•	Data Preprocessing: The data is explored, checked for missing values, and filled with the mean value where necessary. This ensures that the data is clean and ready for analysis.

•	Data Visualization: The distribution of continuous values in the dataset is visualized using histograms. This helps to understand the data's characteristics.

•	Quality vs. Alcohol Content: A bar plot is created to visualize the relationship between the quality of wine and its alcohol content.

•	Redundant Features: The project identifies and removes redundant features by creating a correlation heatmap to ensure that the data used for classification is relevant.

•	Classification Task: The goal is to predict whether a wine is of "best quality" (quality > 5) or not. The dataset is divided into features (attributes) and a target variable. Machine learning models (Logistic Regression, XGBoost, and Support Vector Machine) are trained to classify wine quality based on these features.

•	Model Evaluation: The project evaluates the models' accuracy, both during training and on a separate validation dataset. It also visualizes confusion matrices and provides classification reports to assess model performance.

This project serves as a practical example of using machine learning to classify red wine quality based on its attributes..
